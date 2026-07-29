# Анализ поиска в Яндекс Картинках

## Состав пакета

- `yandex_images_analysis.ipynb` — основной исполняемый Jupyter Notebook.
- `yandex_images_analysis.html` — версия с сохранёнными результатами.
- `data.tsv` — исходные данные.
- `exports/` — CSV-витрины для DataLens.
- `INTERVIEW_NOTES.md` — шпаргалка для самопрезентации.
- `requirements.txt` — зависимости.

## Запуск

1. `pip install -r requirements.txt`
2. `jupyter notebook yandex_images_analysis.ipynb`
3. Выполнить все ячейки сверху вниз.

Ноутбук использует SQLite из стандартной библиотеки Python, поэтому отдельный SQL-сервер не требуется.
