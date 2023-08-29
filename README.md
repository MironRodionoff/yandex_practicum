Привет, Никита!  
Я пока в процессе оформления портфолио, решил по очереди добавить в него все свои учебные проекты  
Поэтому их здесь пока 3, решил, что полезно будет сразу узнать твои комментарии к оформлению, чтобы потом было меньше исправлений  
Ссылки в главном ридми ведут на чужой репозиторий, потому что файл заимствован и пока не до конца исправлен (не все проекты загружены)  
Скажи, пожалуйста, будет заметно в будущем, что файл скачан с другого репозитория и если да, то нестрашно ли это? Естественно, все внутреннее оформление я переделаю под себя, просто так меньше заморочек с форматом   
И еще вопрос, есть ли огранчения по времени у выполнения этого проекта? А то ближайшие две недели планирую сконцентрироваться на выпускном проекте, а потом вернуться сюда.  

### Hi, i'm Miron Rodionov / Мирон Родионов 

Telegram: t.me/miru_miron

Email: mir.on.rodionoff@yandex.ru

Here you'll find my projects from the "Data Science Specialist" training program by Yandex.Praktikum

В этом репозитории собраны мои проекты из курса "Специалист по Data Science" Яндекс.Практикума

Краткое описание проектов и ссылки:
| |Название|Краткое описание|Инструменты|Что сделано|
|--|----|----|-|----|
|1.| [Исследование надежности заемщиков]() | Оценка влияния различных характеристик заемщиков на факт погашения кредита в срок| `pandas`, `numpy`,`pymystem3`, `nltk.stem` | Данные очищены от выбросов, дубликтов и пропусков. Проведена аналитика важности признаков для определения категорий клиентов, клиенты разбиты на категории. Составлены портреты идеального и нежелательного заемщика.|
|2.| [Исследование объявлений о продаже квартир]() | Анализ признаков влияющих на стоимость квартир в регионе| `pandas`, `numpy`, `matplotlib`, `seaborn`| Данные максимально сохранены, пропуски заполнены, в том числе с применением случайных величин в диапозоне нормального распределения признаков. По совокупности признаков определены самые близкие к центру квартиры, а также районы с самыми высокими и низкими ценами. Найдена средняя скорость продажи для разных типов недвижимости. Выявлены сезонности в обьеме продаж и колебания цен.|
|3.| [Анализ тарифов мобильного оператора]() | Анализ статистики использования услуг мобильного оператора клиентами с целью определения приоритетного тарифа для фирмы| `pandas`, `numpy`, `matplotlib`, `scipy` | Для анализа доступен маленький обьем данных. Рассмотрены два тарифных плана нижней и верхней ценовой категории. На основании статистического анализа, выявлены характерные особенности поведения клиентов: затраты, продолжительность использования тарифа, лояльность, стабильность. Проверены гипотезы о поведении клиентов в разных регионах и на разных тарифах. Определен и статичстически подтвержден наиболее выгодный для оператора тариф. |
|4.| [Анализ игровой индустрии]() | Исследование продаж компьютерных игр в различных регионах и определение стратегии рекламной компании| `pandas`, `numpy`, `scipy`, `seaborn`, `matplotlib` | Проведен анализ данных о продажах игр по всему миру начиная с 80-х годов. Определены пики популярности и периоды жизни игровых консолей, а также самые популярные кроссплатформенные игры. Проведен анализ корреляции мнения критиков, журналистов и пользователей с реальными продажами. Составлены портреты клиентов по странам с предпочтениями к платформам, жанрам, конкретным продуктам. Проверены гипотезы о самых популярных жанрах и платформах. |
|5.| [Модель рекомендаций тарифных планов]() | Модель рекомендаций пользователям альтернативных тарифных планов| `pandas`, `sklearn`, `numpy`, `seaborn`, `matplotlib`, `datetime`| На основании использования клиентами услуг действующего тарифного плана, настроена модель рекомендации. Использовались RandomForestClassifier, DecisionTreeClassifier, LogisticRegression. Гипермараметры подбирались с помощью кроссвалидации GridSearchCV.| 
|6.| [Отток банковских клиентов]() | Модель для предсказания оттока банковских клиентов| `pandas`, `numpy`, `sklearn`, `seaborn`, `matplotlib`,`datetime`| Датасет очищен, признаки кодированы с помощью StandardScaler, использованы RandomForestClassifier, GradientBoostingClassifier, LogisticRegression. Гиперпараметры подобраны кроссвалидацией, применен апсемплинг для устранения дисбаланса классов, для оценки моделей использовалась ROC кривая, F1, accuracy.|
|7.| [Предсказание прибыли нефтедобывающей компании]() | Модель предсказаний прибыли компании и выбор прибыльных регионов для разработки нефти| `pandas`, `numpy`, `matplotlib`, `scipy`, `sklearn` |В избранном регионе собраны характеристики для скважин: качество нефти и объём её запасов. Построена модель для предсказания объёма запасов в новых скважинах, использована LinearRegression с метрикой RMSE. Определены скважины с самыми высокими оценками значений добычи. Рассчитаны точки безубыточности, риски убытков, выбран регион с максимальной суммарной прибылью отобранных скважин.|
|8.| [Предсказание выработки золотодобывающей компании]() | Модель предсказания качества очистки золотоносной руды| `pandas`, `numpy`, `seaborn`, `matplotlib`, `scipy`, `sklearn` | Проведен анализ корректности расчета исходной эффективности обогащения сырья. Выявлены аномалии в техпроцессе, данные очищены от выбросов. Найдены параметры концентрации металлов на всех этапах очистки, определено влияние размера гранул сырья на процесс обогащения и выхода продукта. Предсказаны параметры процесса по данным о сырье. Использовались: LinearRegression, RandomForestRegressor, Lasso c метрикой SMAPE на кроссвалидации, а также проверкой на константной и Dummy модели.|
|9.| [Защита персональных данных]() | Алгоритм защиты (обезличивания) персональных данных клиента, и модель предсказание факта выплаты страховой премии| `pandas`, `numpy`, `sklearn` | Подготовленный датасет превращен в матрицу и перемножен на случайную несингулярную обратную квадратную матрицу, с отделением целевого признака. Таким образом выполнено формирование ключа щифрования. На зашифрованном датасете произведены предсказания с использованием LinearRegression с проверкой по коэфициенту детерминации R2. |
|10.| [Предсказание цены автомобиля]() | Модель предсказания цены подержанных автомобилей| `pandas`, `numpy`, `seaborn`, `matplotlib`, `scipy`, `sklearn`, `catboost`, `lightgbm`, `xgboost` |  Проведен EDA и статанализ, данные очищены от выбросов. Через корреляционную матрицу выявлены важные признаки, лишние признаки удалены. Обучены RandomForestClassifier, CatBoostClassifier, LGBMRegressor, XGboost с подбором параметров с помощью GridSearchCV. Отладка и сравнение по среднеквадратичной ошибке RMSE. |
|11.| [Временные ряды для предсказания количества заказов такси]() | Модель предсказания заказов такси на следующий час |`pandas`, `numpy`, `statsmodel`, `matplotlib`, `sklearn`,`scipy`, `xgboost`, `catboost`, `seaborn`| Проведен анализ времнного ряда по дням в рамках года, определен тренд и сезонность в течении недели и дня. Собрана модель для предсказания на несколько часов вперед в течении дня. Тестировались  SARIMA, XGBoost, CatBoost, GradientBoostingRegressor, LinearRegression метрикой RMSE.|
|12.| [Классификация токсичных комментариев]() | Модель классификации токсичных комментариев| `pandas`, `numpy`, `torch`, `transformers`, `sklearn`, `pymystem3` | Данные очищены от разделителей, приведены к регистру, проведена векторизация TfidfVectorizer. Список стопслов загружен из nltk. Параметры подобраны кроссвалидацией, использовалась логистическая регрессия, BERT не использовалась по соображениям экономии ресурсов.|
|13.| [SQL. Пргнозирование спроса на авиабилеты]() | Статистический анализ спроса на авиабилеты, при проведении музыкальных фестивалей| `pandas`, `numpy`, `squarify`, `seaborn`, `matplotlib` |Проведен статистический анализ данных, проверены гипотезы «Средний спрос на билеты во время фестивалей не отличается от среднего спроса на билеты в обычное время»; «Средний спрос на билеты во время фестивалей отличается от среднего спроса на билеты в обычное время». Пороговое значение alpha 0.05. Для оценки использовался критерий Мынна_Уитни |
|14.| [CV.Определение возраста по фотографии]() | Модель предсказания возраста по фотографии| `pandas`, `numpy`, `tensorflow`, `matplotlib` | Модель обучена на обогащенных данных с помощью кроссвалидациина на 10 эпохах на ResNet50 с использованием алгоритма оптимизации Adam(lr=0.0001). Часть данных была обрезана, развернута, сделана ЧБ.|
|15.| [Прогнозирование оттока клиентов оператора связи]() | Модель оттока клиентов оператора связи| `pandas`, `numpy`, `seaborn`, `matplotlib`, `calendar`, `datetime`, `sklearn`, `catboost`, `lightgbm`| Проведена очистка данных, балансировка признаков, предотвращена утечка целевого признака. Пропуски заполнены с обогащением датасета новыми фичами. Проведена работа с мултиколлинеарностью. На кроссвалидации CatBoostClassifier удалось получить  ROC-AUC = 0,89.|
|16.| [Часто применяемые функции]() | Библиотека частых функций | `разделение выборок`, `апсемплинг`, `даунсемплинг`, `гистограммы и диаграммы`| Собраны функции для разделения выборок, подсчета метрик, кроссвалидации, графики и гистограммы.|

