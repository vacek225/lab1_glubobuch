# Лабораторная работа 1. Вариант 3

## Цель

Выполнить предобработку данных, обучить базовые модели машинного обучения и оценить качество многоклассовой классификации на датасете Wine Quality.

## Датасет

Используется Wine Quality из UCI Machine Learning Repository, ID 186: https://archive.ics.uci.edu/dataset/186/wine+quality

Лицензия: CC BY 4.0.

Для запуска ноутбука рядом с `lab1_variant3_Brungardt.ipynb` должны лежать файлы:

- `winequality-red.csv`
- `winequality-white.csv`
- `winequality.names`

Файлы данных не коммитятся в репозиторий и добавлены в `.gitignore`.

## Окружение

Проверенная версия Python: 3.13.2.

Установка зависимостей:

```bash
python -m venv .venv
.venv\Scripts\activate
python -m pip install -r requirements.txt
```

## Запуск

```bash
python -m jupyter lab
```

Если JupyterLab не установлен, можно открыть `lab1_variant3_Brungardt.ipynb` в VS Code или установить JupyterLab отдельно:

```bash
python -m pip install jupyterlab
python -m jupyter lab
```
