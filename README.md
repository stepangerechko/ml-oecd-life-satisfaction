OECD Life Satisfaction Prediction

Прогнозирование удовлетворённости жизнью по данным OECD


1. Постановка задачи

Тип задачи: Supervised Learning
Подтип: Regression

Цель проекта — предсказать уровень удовлетворённости жизнью (Life Satisfaction) по показателю GDP per capita.

Модель обучается на размеченных данных:
есть входной признак X и целевая переменная y.


2. Данные

Источник:
OECD Better Life Index
GDP per capita (World Bank)

Признак (X):
GDP per capita

Целевая переменная (y):
Life Satisfaction


3. Используемая модель

Linear Regression (Scikit-Learn)

Математическая модель:

y = θ₀ + θ₁x

Алгоритм подбирает параметры θ₀ и θ₁, минимизируя:

MSE (Mean Squared Error)


4. Почему это Machine Learning

Модель не задаётся вручную.

Параметры θ₀ и θ₁ вычисляются автоматически на основе данных.

Это пример обучения с учителем (Supervised Learning).


5. Результат

Наблюдается положительная зависимость между
уровнем ВВП на душу населения и удовлетворённостью жизнью.

Чем выше GDP per capita, тем выше предсказанный уровень Life Satisfaction.


6. Используемый стек
Python
NumPy
Pandas
Matplotlib
Scikit-Learn
