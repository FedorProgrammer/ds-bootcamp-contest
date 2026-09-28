# Avito DS bootcamp
Решение находится в [этом ноутбуке](cookies-bot-detector.ipynb). При желании, его можно открыть в [Google Colab](https://colab.research.google.com/drive/15HO3L-m9IyuNQjJI1zEH-gXpdQ2Dd8ht?usp=sharing).

## Бондаренко Федор Алексеевич
[Github](https://github.com/FedorProgrammer), [stepik](https://stepik.org/users/189216442/profile)

## Общие результаты

| Модель                                    | mean   | std    |
| ----------------------------------------- | ------ | ------ |
| Baseline (`n_events`, `n_unique_items`)   | 0.1156 | 0.0062 |
| Поведенческие признаки (FE)               | 0.5357 | 0.0090 |
| FE + текст (`search_query`, `user_agent`) | 0.5275 | 0.0343 |
| FE, подобранные гиперпараметры            | 0.5443 | 0.0386 |
| FE + текст, подобранные гиперпараметры    | 0.5529 | 0.0536 |