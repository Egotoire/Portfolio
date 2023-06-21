# [Определение стоимости автомобилей]()
Сервис по продаже автомобилей с пробегом «Не бит, не крашен» разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. В вашем распоряжении исторические данные: технические характеристики, комплектации и цены автомобилей.

## Цель исследования:
Нужно построить модель для определения стоимости.

**Заказчику важны:**
- качество предсказания;
- скорость предсказания;
- время обучения.

## Итог исследования:
В целом, все модели предсказывают довольно быстро - меньше секунды, но все же для заказчика важна скорость предсказания и метрика, потому лучшая модель - XGBoost с параметрами: max_depth: 13, learning_rate: 0.1.

## Стек технологий:
Python, Pandas, Matplotlib, NumPy, Scikit-learn, Seaborn, CatBoost, XGBoost, LightGBM, градиентный бустинг, численные методы