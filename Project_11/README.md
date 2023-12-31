
# Временные ряды
## Построить модель, предсказывающую количество заказов такси на следующий час.

[md](https://github.com/MironRodionoff/yandex_practicum/blob/main/Project_11/README.md)    
[ipynb](https://github.com/MironRodionoff/yandex_practicum/blob/main/Project_11/Project_11.ipynb)



## Описание проекта

Нам нужно:

Загрузить данные и выполнить их ресемплирование по одному часу.  
Проанализировать данные.  
Обучить разные модели с различными гиперпараметрами. Сделать тестовую выборку размером 10% от исходных данных.  
Проверить данные на тестовой выборке и сделать выводы.  
Количество заказов находится в столбце num_orders (от англ. number of orders, «число заказов»).  
Значение метрики RMSE на тестовой выборке должно быть не больше 48.  

## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **pyplot**
- **sklearn**
- **seaborn** 
- **statmodels** 
- **catboost**
- **LGBM**  

## Вывод

В ходе исследования проделали следующие шаги:

* Ресемплирование
* Анализ сезонности, общего тренда, тренда внутри дня и недели, шумов
* Добавленение новых признаков (месяц, день, день недели, отстающие показатели, среднее скользящее)
* Оценка важности признаков

Были проверены следующие модели:

Линейная регрессия
Дерево решений
Случайный лес
Catboost
Lightgbm

Проведенное исследование показало, что наилучшие показатели RMSE у следующей модели:
LinearRegression(): 33.72
