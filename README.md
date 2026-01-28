# TPU Big Data Analytics — Lab 1: CSV Data Analyzer (No Pandas)

Лабораторная работа №1 по курсу **«Аналитика больших данных»**  
Национальный исследовательский Томский политехнический университет (ТПУ), 2025 г.

## Задача
Реализовать обработку CSV-датасета **только средствами стандартной библиотеки Python**:
- Загрузка и валидация данных
- Подсчёт уникальных значений
- Фильтрация по числовому порогу
- Сортировка пузырьком
- Поиск по подстроке
- Обработка исключений
- ООП-архитектура

## Датасет
[Screen Time vs Mental Wellness Survey](https://www.kaggle.com/datasets/adharshinikumar/screentime-vs-mentalwellness-survey-2025)

## Особенности
- Полностью без `pandas`, `numpy`, `scikit-learn`
- Использование только `csv`, `os`, `tabulate`
- Человекочитаемый вывод через `tabulate`
- Надёжная обработка ошибок (файл не найден, кодировка, несоответствие колонок)

## Запуск
```bash
pip install -r requirements.txt
python ScreenTimeAnalyzer.py
