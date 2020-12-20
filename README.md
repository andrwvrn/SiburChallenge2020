# SiburChallenge2020

[Задача 2. Сопоставление названий](https://sibur.ai-community.com/competitions/4/tasks/12)

# Внешние данные

1. https://www.kaggle.com/peopledatalabssf/free-7-million-company-dataset (`data/companies_sorted.csv`)
2. https://pypi.org/project/china-cities/

Предобработка внешних данных в `notebooks/External_data_preprocessing.ipynb`. Для ее запуска необходимо скачать файл по ссылке из пункта 1 и распаковать в папку `data`. После предобработки получаем два файла: `data/train_external.csv` и `data/test_external.csv`, которые далее используются в `solution.ipynb`.
