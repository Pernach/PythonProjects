# SteelTemperature

Для уменьшения потребления предприятием электроэнергии подготовить модель машинного обучения, осуществляющую прогнозирование температуры стали.

Задача: значение MAE на тестовой выборке не должно превышать 6.3

Была проведена предварительная обработка данных, включающая: удаление пропусков, заполнение пропусков, проверка на мультиколлинеарность, добавление новых признаков, поиск выбросов.
Задача была решена с применением алгоритма градиентного бустинга, параметры которого найдены методом перебора по сетке.

Использованы библиотеки:
pandas, IPython, datetime, numpy, collections, matplotlib, seaborn, sklearn, lightgbm
