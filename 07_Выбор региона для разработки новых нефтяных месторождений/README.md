# Выбор локации для скважины

### Использованные инструменты:
* Pandas
* sklearn
* math
* numpy
* Seaborn
* Matplotlib
* SciPy
* Bootstrap
* машинное обучение

### Задача:
Решить в каком регионе добывать нефть. Построить модель машинного обучения, которая поможет определить регион, где добыча принесет наибольшую прибыль с наименьшим риском убытков.
Шаги для выбора локации:

- В избранном регионе ищут месторождения, для каждого определяют значения признаков;
- Строят модель и оценивают объём запасов;
- Выбирают месторождения с самым высокими оценками значений. Количество месторождений зависит от бюджета компании и стоимости разработки одной скважины;
- Прибыль равна суммарной прибыли отобранных месторождений.

### Данные:
* `id` — уникальный идентификатор месторождения;
* `f0, f1, f2` — три признака точек (неважно, что они означают, но сами признаки значимы);
* `product` — объём запасов в месторождении (тыс. баррелей).


### Описание проекта
* Собраны характеристики пробы нефти для скважин: качество нефти и объём её запасов по трем регионам. Характеристики для каждой скважины в регионе уже известны. 
* Построена модель для предсказания объёма запасов в новых скважинах.
* Выбраны скважины с самыми высокими оценками значений.
* Определены регионы с максимальной суммарной прибылью отобранных скважин.
* Построена модель для определения региона, где добыча принесёт наибольшую прибыль. Проанализирована возможная прибыль и риски техникой Bootstrap.

### Краткий вывод:
По результатам применения методики Bootsrap мы можем сказать, что наиболее перспективным для разработки является регион №2. Только для него мы получили вероятность потерь ниже двух с половиной процентов.