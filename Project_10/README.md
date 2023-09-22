# Регрессия
## Определение стоимости автомобилей

[md](https://github.com/MironRodionoff/yandex_practicum/blob/main/Project_10/README.md)    
[ipynb](https://github.com/MironRodionoff/yandex_practicum/blob/main/Project_10/Project_10.ipynb)

## Описание проекта

Сервис по продаже автомобилей разрабатывает приложение для привлечения новых клиентов.  В нём можно быстро узнать рыночную стоимость своего автомобиля. В нашем распоряжении исторические данные: технические характеристики, комплектации и цены автомобилей. Нам нужно построить модель для определения стоимости.

Цели проекта: Построить модель для предсказания стоимости автомобиля на основании имеющихся данных.

Этапы работы:

* Предобработка данных 
	* удаление дубликатов
	* заполнение пропусков с помощью KNN Imputer
	* обработка аномалий
* Обучение моделей:
	* Линейная Регрессия
	* RandomForest Regressor
	* CatBoost Regressor
	* LGBM Regressor
* Вывод

## Навыки и инструменты

- **python**
- **pandas**
- **sklearn**
- **numpy**
- **matplotlib**
- **seaborn**
- **phik**
- **tqdm**

- **catboost**
- **LGBM**  

## Вывод

В ходе исследования были применены следующие методы:

* Токенезация
* Лемматизация
* Очистка текста от символов и бранных слов
* Векторизация для n-грамм. (1 леммa)

Проверены следующие модели:

	* Линейная Регрессия 
	* RandomForest Regressor (RMSE 1303)
	* CatBoost Regressor (RMSE 1479)
	* LGBM Regressor (RMSE 1583)

**Параметры рекомендуемых моделей:**  
>RandomForestRegressor (max_depth=18, n_estimators=400)  
>CatBoostRegressor (iterations=150, learning_rate=0.2, max_depth=14)  
>LGBMRegressor ('learning_rate': 0.3, 'max_depth': 13)