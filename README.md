# Мои проекты

## Project 1 - Музыка больших городов $~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~$Статус: Завершен
### Описание проекта
Сравнение Москвы и Петербурга окружено мифами:<br>
 - Москва — мегаполис, подчинённый жёсткому ритму рабочей недели;<br>
 - Петербург — город своеобразной культуры, непохожий на Москву.<br>

Некоторые мифы отражают действительность. Другие — пустые стереотипы. Бизнес должен отличать первые от вторых, чтобы принимать рациональные решения. На реальных данных музыкального сервиса проверим гипотезы и сравним поведение пользователей двух столиц.


## Project 2 - Исследование надёжности заёмщиков $~~~~~~~~~~~$Статус: Завершен
### Описание проекта
Заказчик — кредитный отдел банка. Нужно разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. Входные данные от банка — статистика о платёжеспособности клиентов. Результаты исследования будут учтены при построении модели кредитного скоринга — специальной системы, которая оценивает способность потенциального заёмщика вернуть кредит банку.


## Project 3 - Исследовательский анализ данных $~~~~~~~~~~~~~~~~$Статус: Завершен
### Описание проекта
В нашем распоряжении данные сервиса недвижимости — архив объявлений за несколько лет о продаже квартир в Санкт-Петербурге и соседних населённых пунктах. Задача — выполнить предобработку данных и изучить их, чтобы найти интересные особенности и зависимости, которые существуют на рынке недвижимости. О каждой квартире в базе содержится два типа данных: добавленные пользователем и картографические. Например, к первому типу относятся площадь квартиры, её этаж и количество балконов, ко второму — расстояния до центра города, аэропорта и ближайшего парка.


## Project 4 - Статистический анализ данных $~~~~~~~~~~~~~~~~~~~~~$Статус: Завершен
### Описание проекта
Компания — федеральный оператор сотовой связи. Клиентам предлагают два тарифных плана: «Смарт» и «Ультра». Чтобы скорректировать рекламный бюджет, коммерческий департамент хочет понять, какой тариф приносит больше денег. Нужно сделать предварительный анализ тарифов на небольшой выборке клиентов. В нашем распоряжении данные 500 пользователей: кто они, откуда, каким тарифом пользуются, сколько звонков и сообщений каждый отправил за 2018-й год. Нужно проанализировать поведение клиентов и сделать вывод — какой тариф лучше. Также нужно проверить гипотезу, что средняя выручка с пользователей тарифов «Ультра» и «Смарт» различается. И проверить гипотезу, что средняя выручка с пользователей из Москвы отличается от выручки с пользователей других регионов.


## Project 5 - Исследование для интернет-магазина $~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~$Статус: Завершен
### Описание проекта
Интернет-магазин продаёт по всему миру компьютерные игры. Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation). Нужно выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.

В наборе данных попадается аббревиатура ESRB (Entertainment Software Rating Board) — это ассоциация, определяющая возрастной рейтинг компьютерных игр. ESRB оценивает игровой контент и присваивает ему подходящую возрастную категорию, например, «Для взрослых», «Для детей младшего возраста» или «Для подростков».


## Project 6 - Рекомендация тарифов $~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~$Статус: Завершен
### Описание проекта
Оператор мобильной связи выяснил: многие клиенты пользуются архивными тарифами. Они хотят построить систему, способную проанализировать поведение клиентов и предложить пользователям новый тариф: «Смарт» или «Ультра». В нашем распоряжении данные о поведении клиентов, которые уже перешли на эти тарифы. Нужно построить модель для задачи классификации, которая выберет подходящий тариф. Нужно построить модель с максимально большим значением accuracy. Чтобы сдать проект успешно, нужно довести долю правильных ответов по крайней мере до 0.75. Проверить accuracy на тестовой выборке.


## Project 7 - Отток клиентов $~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~$Статус: Завершен
### Описание проекта
Из «Бета-Банка» стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых. Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Предоставлены исторические данные о поведении клиентов и расторжении договоров с банком. Нужно построить модель с предельно большим значением F1-меры. Нужно довести метрику до 0.59. Проверить F1-меру на тестовой выборке. Дополнительно измерить AUC-ROC, сравнивая её значение с F1-мерой.


## Project 8 - Выбор локации для скважины $~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~$Статус: Завершен
### Описание проекта
Добывающей компании нужно решить, где бурить новую скважину. Шаги для выбора локации обычно такие:

 - В избранном регионе собирают характеристики для скважин: качество нефти и объём её запасов;
 - Строят модель для предсказания объёма запасов в новых скважинах;
 - Выбирают скважины с самыми высокими оценками значений;
 - Определяют регион с максимальной суммарной прибылью отобранных скважин.


Нам предоставлены пробы нефти в трёх регионах. Характеристики для каждой скважины в регионе уже известны. Нужно построить модель для определения региона, где добыча принесёт наибольшую прибыль. Проанализировать возможную прибыль и риски техникой Bootstrap.


## Project 9 - Восстановление золота из руды $~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~$Статус: Завершен
### Описание проекта
Компания разрабатывает решения для эффективной работы промышленных предприятий. Нужно построить модель способную предсказать коэффициент восстановления золота из золотосодержащей руды. В нашем распоряжении данные с параметрами добычи и очистки. Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.


## Project 10 - Защита персональных данных клиентов $~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~$Статус: Завершен
### Описание проекта
Нам нужно защитить данные клиентов страховой компании. Разработать такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию. Обосновать корректность его работы. Нужно защитить данные, чтобы при преобразовании качество моделей машинного обучения не ухудшилось. Подбирать наилучшую модель не требуется.


## Project 11 - Определение стоимости автомобилей $~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~$Статус: Завершен
### Описание проекта
Сервис по продаже автомобилей с пробегом разрабатывает приложение, чтобы привлечь новых клиентов. В нём можно будет узнать рыночную стоимость своего автомобиля. Нужно построить модель, которая умеет её определять. В нашем распоряжении данные о технических характеристиках, комплектации и ценах других автомобилей.


## Project 12 - Прогнозирование заказов такси $~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~$Статус: Завершен
### Описание проекта
Компания собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Построить модель для такого предсказания. Значение метрики RMSE на тестовой выборке должно быть не больше 48.


## Project 13 - Проект: Обучение для текстов $~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~$Статус: Завершен
### Описание проекта
Интернет-магазин запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию. Обучим модель классифицировать комментарии на позитивные и негативные. В нашем распоряжении набор данных с разметкой о токсичности правок.<br>
Нужно построить модель со значением метрики качества F1 не меньше 0.70.


## Project 14 - Определение возраста покупателей $~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~$Статус: Завершен
### Описание проекта
Сетевой супермаркет внедряет систему компьютерного зрения для обработки фотографий покупателей. Фотофиксация в прикассовой зоне поможет определять возраст клиентов, чтобы:
 - Анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы;
 - Контролировать добросовестность кассиров при продаже алкоголя.

Нужно построить модель, которая по фотографии определит приблизительный возраст человека. В нашем распоряжении набор фотографий людей с указанием возраста.


## Project 15 - Промышленность $~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~$Статус: Завершен
### Описание проекта
Чтобы оптимизировать производственные расходы, металлургический комбинат решил уменьшить потребление электроэнергии на этапе обработки стали. Нам предстоит построить модель, которая предскажет температуру стали.
