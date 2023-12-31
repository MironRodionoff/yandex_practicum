
# Защита персональных данных клиентов

[md](https://github.com/MironRodionoff/yandex_practicum/blob/main/Project_09/README.md)    
[ipynb](https://github.com/MironRodionoff/yandex_practicum/blob/main/Project_09/Project_09.ipynb)

## Описание проекта
# Защита персональных данных клиентов
Нам нужно защитить данные клиентов страховой компании «Хоть потоп». Разработаем такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию. Обоснуем корректность его работы.

Цель проекта
Нужно защитить данные, чтобы при преобразовании качество моделей машинного обучения не ухудшилось.
Подбирать наилучшую модель не требуется.


## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **pyplot**
- **sklearn**
- **seaborn** 

## Вывод

Модели показали одинаковые результаты по потерям при обучении на данных до, после кодирования, а также после раскодирования.  
Предложенный способ умножения матрицы признаков на определенную обратимую матрицу показал себя надежным способом шифрования личных данных

