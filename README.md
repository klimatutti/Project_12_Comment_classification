# Проект_12_Классификация_комментариев

Интернет-магазин «Викишоп» запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.

Обучите модель классифицировать комментарии на позитивные и негативные. В вашем распоряжении набор данных с разметкой о токсичности правок.

Для начала загрузим и изучим данные: рассмотрим дубликаты, пропуски, разберемся с регистром и лишними знаками в тектах и избавимся от стоп-слов. Далее приступим к разделу обучения: разделим данные на выборки, проведем TF-IDF векторизацию, обучим модели, подбирая различные параметры и вычисляя метрику F1.

# Project_12_Comment_classification

Online store "Wikishop" launches a new service. Now users can edit and supplement product descriptions, just like in wiki communities. That is, clients propose their edits and comment on the changes of others. The store needs a tool that will look for toxic comments and submit them for moderation.

Train the model to classify comments into positive and negative. At your disposal is a dataset with markup on the toxicity of edits.

To begin with, let's load and study the data: consider duplicates, gaps, deal with case and extra characters in texts and get rid of stop words. Next, let's proceed to the training section: we divide the data into samples, carry out TF-IDF vectorization, train the models by selecting various parameters and calculating the F1 metric.
