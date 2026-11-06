# California Housing — Линейная регрессия и метрики качества

Учебный проект по модулю **04 Machine Learning (Тема 02: Линейная регрессия и метрики)**.
Целевая переменная — `MedHouseVal` (медианная стоимость жилья в сотнях тысяч долларов).

## Структура проекта

- `california_housing_regression.ipynb` — основной ноутбук с полным циклом: EDA, разбиение `train/test`, константный baseline, ручная реализация линейной регрессии и метрик на NumPy, обучение `LinearRegression` (`scikit-learn`), диагностика остатков и разбор ошибок.
- `requirements.txt` — зависимости проекта.
- `data/` — папка для локального датасета `train.csv` (если файл не положен локально, ноутбук автоматически загружает датасет через `sklearn.datasets.fetch_california_housing`).

## Быстрый запуск

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

