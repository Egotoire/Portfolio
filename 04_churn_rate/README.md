# [Прогнозирование оттока клиента Банка]()
Из банка стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.
Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Предоставлены исторические данные о поведении клиентов и расторжении договоров с банком.

## Цель исследования:
Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Вам предоставлены исторические данные о поведении клиентов и расторжении договоров с банком.

Построить модель с предельно большим значением F1-меры, нужно довести метрику до 0.59.

## Итог исследования:
**Для полученных данных, чтобы получить наибольшие и необходимые значения F1-меры, необходимо использовать:**

1. Модель случайного леса
2. Увеличение обучающей выборки
3. Подбор порога вероятности положительного класса
4. В таком случае метрики на протестированной модели получили данные значения:
    - F1-мера - **0.636058**
    - Площадь под кривой ROC - **0.8617**
    - Полнота - **0.697789**
    - Точность - **0.584362**