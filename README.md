# yandex.projects


|Название проекта|Описание|Стек|
|-|--------|---|
| [Финальный проект телеком компании](https://github.com/AfanasiyFoma/yandex.projects/blob/main/%D0%BE%D1%82%D1%82%D0%BE%D0%BA%20%D0%BA%D0%BB%D0%B8%D0%B5%D0%BD%D1%82%D0%BE%D0%B2.ipynb)|Оператор связи «Ниединогоразрыва.ком» хочет научиться прогнозировать отток клиентов. Если выяснится, что пользователь планирует уйти, ему будут предложены промокоды и специальные условия. Команда оператора собрала персональные данные о некоторых клиентах, информацию об их тарифах и договорах. Задача: разработать модель для предсказания оттока клиентов.  Метрика на тестовой выборке AUC-ROC=>0.85|python, pandas, numpy, seaborn, matplotlib, sklearn, lightgbm, catboost, phik|
|[Прогнозирование заказов такси](https://github.com/AfanasiyFoma/yandex.projects/blob/main/%D0%BF%D1%80%D0%BE%D0%B3%D0%BD%D0%BE%D0%B7%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%B7%D0%B0%D0%BA%D0%B0%D0%B7%D0%BE%D0%B2%20%D1%82%D0%B0%D0%BA%D1%81%D0%B8%20%D0%BF%D0%BE%20%D0%B2%D1%80%D0%B5%D0%BC%D0%B5%D0%BD%D0%B8.ipynb)|Компания «Чётенькое такси» собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Постройте модель для такого предсказания. Значение метрики RMSE на тестовой выборке должно быть не больше 48.|python, pandas, numpy, seaborn, matplotlib, sklearn, lightgbm, catboost, time|
|[Определение токсичности комментариев](https://github.com/AfanasiyFoma/yandex.projects/blob/main/%D0%9E%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D1%82%D0%BE%D0%BA%D1%81%D0%B8%D1%87%D0%BD%D0%BE%D1%81%D1%82%D0%B8%20%D0%BA%D0%BE%D0%BC%D0%BC%D0%B5%D0%BD%D1%82%D0%B0%D1%80%D0%B8%D0%B5%D0%B2/%D0%9E%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D1%82%D0%BE%D0%BA%D1%81%D0%B8%D1%87%D0%BD%D0%BE%D1%81%D1%82%D0%B8%20%D0%BA%D0%BE%D0%BC%D0%BC%D0%B5%D0%BD%D1%82%D0%B0%D1%80%D0%B8%D0%B5%D0%B2.ipynb)|Интернет-магазин «Викишоп» запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию. Обучите модель классифицировать комментарии на позитивные и негативные. В вашем распоряжении набор данных с разметкой о токсичности правок. Постройте модель со значением метрики качества F1 не меньше 0.75.|python, pandas, numpy, seaborn, matplotlib, sklearn, lightgbm, catboost, nltk, spacy|
