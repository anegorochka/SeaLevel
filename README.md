# SeaLevel

## Цель
На основе данных об уровне моря за последние десятилетия постройте вероятностную модель изменения уровня моря.

## Задача исследования
1.	Найди и прочитать данные.
2.	Построить вероятностную модель.
3.	Проверить значимость параметров модели и исключите незначимые.
4.	Проверить адекватность модели с помощью статистических тестов и/или стохастического моделирования, перекрестной валидации.
5.	На основании проведенного исследования скорректировать модель и проверить адекватность скорректированной модели.

## Данные
На сайте NASA Sea Level Change program былнайден датасет с данными об измении Global MeanSea Level (глобального среднего уровня моря на планете) с 1993 года по август 2024. Из него были взяты следующие данные: Year, Fraction of year, GMSL (GIA not applied), mm, Standard deviation of GMSL (GIA not applied), mm, GMSL (GIA applied), mm, Standard deviation of GMSL (GIA applied), mm. 

Для них в Excel были рассчитаны средние значения для каждого года.

## Модели
- Линейная регрессия с помощью sklearn.linear_model
- Аптечная модель
- Простая регрессия
- Регрессия на Х**2
- Логарифмическая модель
- Множественная линейная регрессия

## Библиотеки
Numpy, pandas, seaborn, matplotlib.pyplot, sklearn.linear_model (LinearRegression), scipy.stats (norm), scipy (stats), statsmodels, statsmodels.api, sklearn.model_selection (train_test_split), sklearn (datasets), sklearn (svm), sklearn.metrics (mean_squared_error)


