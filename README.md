# Student Performance Analysis 📊

Анализ факторов, влияющих на академические результаты студентов, с использованием открытого датасета с **Kaggle**.


## 📌 Цель исследования:

Выявить взаимосвязи между успеваемостью обучающихся и:

✅ Социально-демографическими факторами (пол, этническая принадлежность);

✅ Условиями обучения (уровень образования родителей, тип питания);

✅ Прохождения подготовительных курсов.


## 📂 Описание данных:

**📌 Источник**: [Student Study Performance Datase](https://www.kaggle.com/datasets/bhavikjikadara/student-study-performance/data)

**Ключевые признаки**:

| Признак | Описание |
| --- | --- |
| `gender` | Пол студента (`male` / `female`) |
| `race_ethnicity` | Этническая группа (`group A-E`) |
| `parental_level_of_education` | Образование родителей |
| `lunch` | Тип питания (`standard` / `free/reduced`) |
| `test_preparation_course` | Подготовка к тесту (`completed` / `none`) |
| `math_score` | Оценка по математике |
| `reading_score` | Оценка по чтению |
| `writing_score` | Оценка по письму |


## 🛠️ Технологии:

- **Язык**: Python 3.8+
- **Библиотеки**:
    
    ```bash
    pandas, numpy, matplotlib, seaborn, scipy, category_encoders, sklearn
    ```
    
- **Среда**: Jupyter Notebook / Google Colab


## 🗂️ Структура анализа:

**1️⃣ Разведовательный анализ данных (EDA):**

🔹 Проверка данных: пропущенные значения, выбросы;

🔹 Описательная статистика;

🔹 Анализ распределений оценок;

🔹 Корреляционный анализ;

**2️⃣ Визуализация данных:**

📌 Гистограммы;

📌 Круговые диаграммы;

📌 Boxplot'ы для сравнения групп;

**3️⃣ Проверка статистических гипотез:**

🧪 Тест на нормальность (Шапиро-Уилка);

🧪 Пол влияет на успеваемость по математике? (*U-критерий Манна-Уитни*);

🧪 Образование родителей влияет на успеваемость (*Критерий Краскела-Уоллиса*);

🧪 Этническая группа влияет на успеваемость? (*Критерий Краскела-Уоллиса*);

🧪 Тип питания влияет на успеваемость? (*U-критерий Манна-Уитни*);

🧪 Прохождение подготовительных курсов влияет на успеваемость? (*U-критерий Манна-Уитни*).


## 🚀 Запуск проекта:

1. Запустите Jupyter Notebook:
    
    ```bash
    jupyter notebook spa_eda.ipynb
    ```
    


## 📊 Ключевые результаты:

✔ **Пол влияет на успеваемость:** мальчики показывают лучшие результаты по математике, но хуже по чтению и письму;

✔ **Образование родителей влияет:** студенты, чьи родители имеют высшее образование, получают более высокие оценки;

✔ **Тип питания влияет:** учащиеся с стандартным питанием показывают лучшие результаты по всем предметам;

✔ **Подготовка к тестам помогает:** прохождение подготовительного курса повышает оценки;

✔ **Этническая принадлежность влияет на успеваемость:** средние оценки значительно различаются между этническими группами.

📌 **`Подробные выводы и графики — в Jupyter Notebook`**


## 📄 Автор:

**👤 Автор**: Тарасенко Александр Эдуардович

**📧 Контакты**: aleksandr.tarasenko2021@gmail.com
