# Ad Hoc в такси агрегаторе

### Описание проекта
Проект по 4 задачам продуктовой аналитики в агрегатои такси SkyTaxi.


### Использованные библиотеки

```
pandas
numpy
seaborn
matplotlib.pyplot
math
```


### Задание 1
Изучите утренние и вечерние часы пик. 

1. Постройте график с количеством заказов по суточным часам (на оси Х - часы от 0 до 23).
2. На сколько за один час в среднем делается больше заказов в часы пик, чем в обычное время? (по всем городам вместе)
3. Рассмотрите города по отдельности: для каждого города выведите разницу в количестве заказов (среднечасовом) между пиковыми и не-пиковыми часами.
4. В каком городе наблюдается наибольшее отклонение конверсии *Order2Ride* в пиковые часы по сравнению с не-пиковыми часами?

### Задание 2

Изучите заказы в Хабаровске и Тюмени. Эти города интересуют менеджеров, так как в них наша компания начала работать относительно недавно. 

1. На сколько процентных пунктов *Order2Ride* в среднем в них ниже, чем в других городах? 
2. За счет какого звена воронки достигается эта разница? Сделайте выводы по Хабаровску и по Тюмени по отдельности.
3. Какие рекомендации вы можете дать локальным менеджерам?

Для их решения рассмотрите основную конверсию из заказа в поездку *Order2Ride*, а также промежуточные три звена конверсии, из которых состоит *Order2Ride* (*Order2Assign*, *Assign2Arrive*, *Arrive2Ride*).

### Задание 3

К вам обратились коллеги из отдела антифрода (отдела, предотвращающего мошенничество). У них есть подозрение, что некоторые водители “мимикрируют координаты”, то есть на самом деле не приезжают в точку А своего заказа, но в приложение посылают сигнал, что они в эту точку А приехали. Таким образом они вынуждают клиента отменить заказ после “прибытия ими в точку А”.

Постарайтесь локализовать данную проблему и выделить города, в которых такое происходит чаще всего.

### Задание 4

Тариф “Доставка” был запущен недавно на всей России. Изучите конверсии в рамках данного тарифа по городам, локализуйте просадку конверсии *Order2Ride* в рамках данного тарифа **и дайте рекомендации отделу операционистов, которые занимаются этим тарифом.

### Данные

Конверсия из заказа в поездку Order2Ride, а также промежуточные три звена конверсии, из которых состоит Order2Ride (Order2Assign, Assign2Arrive, Arrive2Ride).
