# Проекты Я. Практикума

## Проект №1 Базовый Python

**Dataset:** *'/datasets/yandex_music_project.csv'*

Требуемые знания:
* Базовый Pandas;
* Проверка гипотез;


### Описание:
На данных Яндекс.Музыки сравнить поведение пользователей двух столиц.

**Цель исследования** — проверить три гипотезы:
1. Активность пользователей зависит от дня недели. Причём в Москве и Петербурге это проявляется по-разному.
2. В понедельник утром в Москве преобладают одни жанры, а в Петербурге — другие. Так же и вечером пятницы преобладают разные жанры — в зависимости от города. 
3. Москва и Петербург предпочитают разные жанры музыки. В Москве чаще слушают поп-музыку, в Петербурге — русский рэп.

---

## Проект №2 Предобработка данных

**Dataset:** *'/datasets/data.csv'*

Требуемые знания:
* Работа с пропусками;
* Изменение типов данных;
* Поиск дубликатов;
* Категоризация данных;


### Описание:
Заказчик — кредитный отдел банка. Нужно разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. Входные данные от банка — статистика о платёжеспособности клиентов.
Результаты исследования будут учтены при построении модели кредитного скоринга — специальной системы, которая оценивает способность потенциального заёмщика вернуть кредит банку.

---

## Проект №3 Исследовательский анализ данных

**Dataset:** *'/datasets/real_estate_data.csv'*

Требуемые знания:
* Построение графиков и сводные таблицы;
  * сводные таблицы;
  * гистрограмма;
  * распределения;
  * диаграмма размаха
* Срезы данных:
  * pivot_table;
  * .query();
* Взаимосвязь данных;
  * Диаграмма рессеяния;
  * Корреляция;
  * Совместное распределение множества величин;
* Валидация результатов;


### Описание:
На вход предоставляются данные сервиса Яндекс.Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет. Нужно научиться определять рыночную стоимость объектов недвижимости. **Задача — установить параметры**. Это позволит построить автоматизированную систему: она отследит аномалии и мошенническую деятельность. По каждой квартире на продажу доступны два вида данных. Первые вписаны пользователем, вторые — получены автоматически на основе картографических данных.

---

## Проект №4 Статистический анализ данных
Превью: Изучение объектов и их взаимосвязей методами статистики. Выборки и статистическая значимость. Выявление и обработка аномалий. Проект. Проанализировать тарифы федерального оператора сотовой связи.

**Data set:** 
1. *'/datasets/calls.csv'*
2. *'/datasets/internet.csv'*
3. *'/datasets/messages.csv'*
4. *'/datasets/tariffs.csv'*
5. *'/datasets/users.csv'*

Требуемые знания:
* Описательная статистика;
* Теория вероятности;
* Проверка гипотез;

### Описание:

Имеются данные федерального оператора сотовой связи. Клиентам предлагают два тарифных плана: А = «Смарт» и Б = «Ультра». Чтобы скорректировать рекламный бюджет, коммерческий департамент хочет понять, какой тариф приносит больше денег.Необходимо сделать предварительный анализ тарифов на небольшой выборке клиентов. Имеются данные 500 пользователей компании: кто они, откуда, каким тарифом пользуются, сколько звонков и сообщений каждый отправил за 2018 год. Нужно проанализировать поведение клиентов и сделать вывод — какой тариф лучше.

---

## Проект №5 Сборный проект - 1
Превью: Подготовка данных для анализа. Предварительное исследование датасета. Формулирование и проверка гипотез.

**Data set:** 
1. *'/datasets/mkrf_movies.csv'*
2. *'/datasets/mkrf_shows.csv'*

Требуемые знания:
* Предобработка данных;
* EDA;
* Статистика.

### Описание:

Заказчик этого исследования — Министерство культуры Российской Федерации.
Вам нужно изучить рынок российского кинопроката и выявить текущие тренды. Уделите внимание фильмам, которые получили государственную поддержку. Попробуйте ответить на вопрос, насколько такие фильмы интересны зрителю.
Вы будете работать с данными, опубликованными на портале открытых данных Министерства культуры. Набор данных содержит информацию о прокатных удостоверениях, сборах и государственной поддержке фильмов, а также информацию с сайта КиноПоиск.

---

## Проект №6 Введение в ML
Превью: 

**Data set:** 
1. *'datasets/users_behavior.csv'*

### Библиотеки:

### Требуемые знания:
* Обучение с учителем;
* Метрики качества;
* Улучшение модели;
* Регрессия.

### Описание:

Оператор мобильной связи, например «Мегалайн», выяснил: многие клиенты пользуются архивными тарифами. Они хотят построить систему, способную проанализировать поведение клиентов и предложить пользователям новый тариф: «Смарт» или «Ультра».
В вашем распоряжении данные о поведении клиентов, которые уже перешли на эти тарифы *(продолжение проекта №4)*. Нужно построить модель для задачи классификации, которая выберет подходящий тариф. Постройте модель с максимально большим значением accuracy. Accuracy не менее 0.75.

---

## Проект №7 Обучение с учителем

**Data set:** 
1. *'/datasets/Churn.csv'*

### Библиотеки:

### Требуемые знания:
* Подготовка признаков к обучению;
* Метрики классификации;
* Несбалансированная классификация;
* Метрики регрессии.

### Описание:

***Данные бизнеса:***
Из банка, например «Бета-Банка», стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.
***Задача***
Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Имеются исторические данные о поведении клиентов и расторжении договоров с банком.
Постройте модель с предельно большим значением F1-меры. *(не менее 0.59)*. Дополнительно измеряйте AUC-ROC.
Источник данных: https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling

---

## Проект №8 ML в бизнесе

**Data set:** 
1. *'/datasets/geo_data_0.csv'*
2. *'/datasets/geo_data_1.csv'*
3. *'/datasets/geo_data_2.csv'*

### Требуемые знания:
* Метрики в бизнесе;
* Инструменты для запуска нового функционала:
 * А/В тестирование;
 * Bootstrap;
* Сбор данных:
 * Декомпозиция;
 * Утечка целевого признака;
 * Голосование по большинству;
 * Кросс-валидация.

### Описание:

Допустим, вы работаете в добывающей компании «ГлавРосГосНефть». Нужно решить, где бурить новую скважину.
Шаги для выбора локации:
* В избранном регионе собирают характеристики для скважин: качество нефти и объём её запасов;
* Строят модель для предсказания объёма запасов в новых скважинах;
* Выбирают скважины с самыми высокими оценками значений;
* Определяют регион с максимальной суммарной прибылью отобранных скважин.
Вам предоставлены пробы нефти в трёх регионах. Характеристики для каждой скважины в регионе уже известны. Постройте модель для определения региона, где добыча принесёт наибольшую прибыль. Проанализируйте возможную прибыль и риски техникой Bootstrap.

---

## Проект №9 Сборный проект - 2

**Data set:** 
1. *'/datasets/hotel_train.csv'*
2. *'/datasets/hotel_test.csv'*

### Требуемые знания:
* Обучение с учителем;
* ML в бизнесе.

### Описание:

Заказчик этого исследования — сеть отелей «Как в гостях».
Чтобы привлечь клиентов, эта сеть отелей добавила на свой сайт возможность забронировать номер без предоплаты. Однако если клиент отменял бронирование, то компания терпела убытки. Сотрудники отеля могли, например, закупить продукты к приезду гостя или просто не успеть найти другого клиента.
Чтобы решить эту проблему, вам нужно разработать систему, которая предсказывает отказ от брони. Если модель покажет, что бронь будет отменена, то клиенту предлагается внести депозит. Размер депозита — 80% от стоимости номера за одни сутки и затрат на разовую уборку. Деньги будут списаны со счёта клиента, если он всё же отменит бронь.

---

## Проект №10 Системы обработки больших данных

**Data set:** 
1. *'/datasets/housing.csv'*

### Требуемые знания:
* PySpark;
* PySpark.ML;
* PySpark.SQL;

### Описание:

Вам нужно защитить данные клиентов страховой компании «Хоть потоп». Разработайте такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию. Обоснуйте корректность его работы.
Нужно защитить данные, чтобы при преобразовании качество моделей машинного обучения не ухудшилось. Подбирать наилучшую модель не требуется.

---

## Проект №11 Линейная алгебра

**Data set:** 
1. *'/datasets/insurance.csv'*

### Требуемые знания:
* Векторы и векторные операции;
* Растояние между векторами;
* Матрицы и матричные операции;
* Линейная регрессия в векторизованом представлении.


### Описание:

В проекте вам нужно обучить модель линейной регрессии на данных о жилье в Калифорнии в 1990 году. На основе данных нужно предсказать медианную стоимость дома в жилом массиве. Обучите модель и сделайте предсказания на тестовой выборке. Для оценки качества модели используйте метрики RMSE, MAE и R2.

---
