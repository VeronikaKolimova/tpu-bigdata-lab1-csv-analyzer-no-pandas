# TPU Big Data Analytics — Lab 1: CSV Data Analyzer (No Pandas)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VeronikaKolimova/tpu-bigdata-lab1-csv-analyzer-no-pandas/blob/main/Lab_01.ipynb)

Лабораторная работа №1 по курсу **«Аналитика больших данных»**  
Национальный исследовательский Томский политехнический университет (ТПУ), 2025 г.  


## Описание
Реализация обработки CSV-датасета **только средствами стандартной библиотеки Python** (без `pandas`, `numpy`, `scikit-learn`):

- Чтение и валидация данных из CSV
- Подсчёт уникальных значений в колонке
- Фильтрация по числовому порогу (`>`, `<`)
- Сортировка пузырьком по любой колонке
- Поиск по подстроке в строковой колонке
- Обработка исключений (файл не найден, кодировка, несоответствие колонок)
- ООП-архитектура: класс `ScreenTimeAnalyzer`
- Человекочитаемый вывод через `tabulate`

Проект демонстрирует глубокое понимание базовых структур данных, алгоритмов и инженерной дисциплины.

---

## Датасет

Используется открытый датасет с Kaggle:  
 [**Screen Time vs Mental Wellness Survey (2025)**](https://www.kaggle.com/datasets/adharshinikumar/screentime-vs-mentalwellness-survey-2025)

> **Внимание**: файл данных **не включён в репозиторий** в соответствии с лицензией Kaggle (CC BY-NC-SA).  
> Для запуска необходимо добавить датасет вручную (инструкция ниже).

---

##  Запуск

### В Google Colab (рекомендуется):
1. Нажмите на кнопку **«Open In Colab»** выше.
2. В правой панели нажмите **«+ Add data»**.
3. Найдите датасет: `screentime-vs-mentalwellness-survey-2025`.
4. Добавьте его — файл появится по пути:  
   `/kaggle/input/screentime-vs-mentalwellness-survey-2025/Screen Time vs MentalWellness.csv`
5. Запустите все ячейки ноутбука.

### Локально (через Jupyter):
1. Установите зависимости:
   ```bash
   pip install -r requirements.txt
