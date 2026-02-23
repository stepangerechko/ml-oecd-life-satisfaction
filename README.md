OECD Life Satisfaction Prediction

Прогнозирование удовлетворённости жизнью по данным OECD

1. Постановка задачи

Тип задачи: Supervised Learning
Подтип: Regression

Цель — предсказать уровень удовлетворённости жизнью (Life Satisfaction) по показателю GDP per capita.

Модель обучается на размеченных данных (есть вход X и целевая переменная y).


2. Данные

Источник данных:
OECD Better Life Index
GDP per capita (World Bank)

Признак (X):
GDP per capita

Целевая переменная (y):
Life Satisfaction


3. Используемая модель

Linear Regression (Scikit-Learn)

Модель имеет вид:

y = θ0 + θ1x

Алгоритм минимизирует MSE (Mean Squared Error).


4. Почему это Machine Learning

Модель не задаётся вручную.
Параметры θ0 и θ1 подбираются автоматически на основе данных.

Это пример обучения с учителем (supervised learning).


5. Результат

Модель показывает положительную зависимость между GDP и уровнем удовлетворённости жизнью.


6. Стек

Python
NumPy
Pandas
Matplotlib
Scikit-Learn
