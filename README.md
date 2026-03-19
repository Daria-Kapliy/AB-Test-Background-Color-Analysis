## AB-Test-Background-Color-Analysis
Анализ результата проведения A/B теста по внедрению нового цвета фона.

Проводят ли люди больше времени на сайте, если его фон черный, а не белый?

---

## Описание проекта

Цель — определить, приводит ли тестовый вариант интерфейса (группа B) к улучшению конверсии по сравнению с контрольным вариантом (группа A).

---

## Описание данных

[Датасет](https://www.kaggle.com/datasets/adarsh0806/ab-testing-practice/data) с сайта kaggle

### Основные признаки:
- `Group` — принадлежность к экспериментальной группе (A или B)
- `Converted` — факт совершения целевого действия (0 или 1)
- `Time Spent` — время, проведённое на сайте
- `Page Views` — количество просмотренных страниц
- `Device` — тип устройства пользователя
- `Location` — локация пользователя

---

## Структура проекта

```text
AB-TEST-BACKGROUND-COLOR-ANALYSIS/
│
├── notebooks/
│   ├── 01_data_overview.ipynb
│   ├── 02_EDA.ipynb
│   ├── 03_conversion_analysis.ipynb
│   ├── 04_statistical_tests.ipynb
│   ├── 05_segment_analysis.ipynb
│   ├── 06_conclusions.ipynb
│
├── raw_files/
│   └── ab_testing.csv
│
├── processed_files/
│   └── ab_testing_processed.csv
│
├── requirements.txt
└── README.md
