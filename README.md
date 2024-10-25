# ds-projects
Проекты DS



|Название проекта             |Задачи проекта                              |Описание проекта    |Ключевые слова| Выводы, статус проекта|
|:----------------------------|:-------------------------------------------|:------------------------------------------------------|:-------------|:-----------------|
|[Машинное обучение для текстов](https://github.com/Nataly-nb/ds-projects/blob/main/%D0%9C%D0%B0%D1%88%D0%B8%D0%BD%D0%BD%D0%BE%D0%B5%20%D0%BE%D0%B1%D1%83%D1%87%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%B4%D0%BB%D1%8F%20%D1%82%D0%B5%D0%BA%D1%81%D1%82%D0%BE%D0%B2/%D0%9C%D0%B0%D1%88%D0%B8%D0%BD%D0%BD%D0%BE%D0%B5%20%D0%BE%D0%B1%D1%83%D1%87%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%B4%D0%BB%D1%8F%20%D1%82%D0%B5%D0%BA%D1%81%D1%82%D0%BE%D0%B2.ipynb)| Определение токсичности комментариев|Интернет-магазин запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Требуется инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.|Обработка естественного языка, NLP, nltk, tf-idf| Найдена модель со значением метрики качества F1 >= 0.75: Логистическая регрессия|
|[Информационная безопасность](https://github.com/Nataly-nb/ds-projects/tree/main/Info%20Security)|Разработать модель, которая будет классифицировать трафик на нормальный и злонамеренный, включая следующие типы атак: DDoS, SQL-инъекции, брутфорс, вредоносные программы и т.д. Дополнительная задача - собрать REST API сервис.|Компания онлайн-сервис с высоким уровнем входящего трафика имеет специализированный отдел безопасности, который занимается фильтрацией и анализом трафика. Сотрудники этого отдела обратились за помощью в автоматизации выявления аномального и злонамеренного трафика.|Pandas, Numpy, REST API|Найдена модель с максимальной метрикой Accuracy = 0.9966 - RandomForestClassifier|
|Сервис Докт24 телемедицина:  [Осложнения у беременных](https://github.com/Nataly-nb/ds-projects/blob/main/Colab/Test_task_preg_risk_ipynb.ipynb)|Прогнозирование осложнений при беременности | Согласно описанию датасета, данные были собраны из различных больниц, общественных клиник и служб охраны материнского здоровья в сельских районах Бангладеш. https://archive.ics.uci.edu/dataset/863/maternal+health+risk |pandas, numpy, matplotlib, seaborn, sklearn, catboost|Наилучшую точность показала модель CatBoostClassifier - 83%. Наибольшее влияние на риск оказывает уровень глюкозы, наименьшее - температура. |
|Определение диабета у пациента|Определить наличие диабета у пациента (под nda)|Датасет состоит из 482 записей (параметров пациентов), в каждой 107 признаков, в числе которых данные из ОАК и биохимии крови, рассчитанные по формулам значения, данные о принимаемых/назначенных препаратах, поставленных диагнозах. |pandas, numpy, matplotlib, seaborn, phik, sklearn, catboost, lightgbm, xgboost|Обучены модели DecisionTreeClassifier, RandomForestClassifier, CatBoostClassifier, LGBMClassifier, XGBClassifier. Был создан пайплайн по скалированию, заполнению пропусков и кросс-валидации. Лучшую метрику F1 Macro на тестовой выборке показал CatBoost: 0.6923, RandomForest: 0.7429. 5 самых важных признаков для CatBoost: Глюкоза, Лимфоциты%, Гемоглобин, ЛПВП, АЛТ. Для RandomForest: Глюкоза, ИМТ, Лейкоциты, Мочевина, АЛТ.|
|[Компьютерное зрение](https://github.com/Nataly-nb/ds-projects/tree/main/%D0%9A%D0%BE%D0%BC%D0%BF%D1%8C%D1%8E%D1%82%D0%B5%D1%80%D0%BD%D0%BE%D0%B5%20%D0%B7%D1%80%D0%B5%D0%BD%D0%B8%D0%B5) |Определение приблизительного возраст человека по фотографии|Фотофиксация в прикассовой зоне поможет: Анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы; Контролировать добросовестность кассиров при продаже алкоголя.|CV,Машинное обучение, Keras|Получена модель с MAE = 7.11, что недостаточно точно для продажи алкоголя, но вполне достаточно для предложения товаров по возрастным группам.|
|[Прогнозирование заказов такси](https://github.com/Nataly-nb/ds-projects/blob/main/%D0%9F%D1%80%D0%BE%D0%B3%D0%BD%D0%BE%D0%B7%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5_%D0%B7%D0%B0%D0%BA%D0%B0%D0%B7%D0%BE%D0%B2_%D1%82%D0%B0%D0%BA%D1%81%D0%B8/15_%D0%9F%D1%80%D0%BE%D0%B3%D0%BD%D0%BE%D0%B7%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5_%D0%B7%D0%B0%D0%BA%D0%B0%D0%B7%D0%BE%D0%B2_%D1%82%D0%B0%D0%BA%D1%81%D0%B8.ipynb)|Разработка системы предсказания объема заказа.|Компания такси собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Строится модель для такого предсказания.|временные ряды, регрессия, предсказания|Получена RMSE на тестовой выборке у CatBoostRegressor 40.22, значит можно использовать эту модель для прогнозирования количества заказов такси на следующий час.|
|[Определение ориентации мед. справки](https://github.com/Nataly-nb/ds-projects/tree/main/donorSearch_detect_orientation/app)|Создать docker-сервис определения угла поворота справки и поворот справки|Заказчик DonorSearch - занимается развитием донорства в стране. Разработать модель определения ориентации справки и автоматического поворота ее в нормальное положение перед запуском сервиса OCR. Нормальное положение - текст на справке расположен горизонтально.|sklearn, catboost, PyTorch, FastAI, FastAPI, docker|Используя нейросетевую предобученную модель ResNet50 на 100 эпохах удалось добиться следующих метрик: accuracy=0.92, precision_score=0.93, recall_score=0.92, f1_score=0.92.|
