# Spam
Дан тренировочный датасет с разметкой спам/не спам. Нужно определить является ли содержимое в тестовом наборе спамом/не спамом.

На данном датасете применены разные модели (Логистическая регрессия, Случайный лес, Наивный Байесовский классификатор, XGBoost).

В качестве метрики использовалась ROC-AUC. Выявлена модель, которая лучше всего справилась с валидационной выборкой. Данной моделью оказался Случайный лес.

Проведен скоринг лучшей модели тестовых данных.
