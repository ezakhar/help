# How to analyze a completed activity

## Analysis tools

The following information is available in a completed activity, uploaded from sports watch or from smartphone:

* [Comparing planned and actual values - “Overview” tab"](#planfact);
* [Indicators chart](#measurementchart);
* [Calculated indicators - “Details” tab](#metrics);
* [Peaks by distance and by time - “Details” tab](#peaks);
* [Laps panel](#laps);
* [Time in zones](#timeinzone);
* [Planned and completed values by segments, segments chart, segments panel - for structured activities](#segmentpanel).

## Calculated indicators

Staminity **calculates a set of indicators** for each completed activity, each round, segment or part of activity randomly selected on a chart. The calculations are made based on the initial data recorded by sports watches or be an application on the smartphone.

The information is displayed **on the “Details” tab** in activity which is available for users with “Premium” and “Coach” tariffs enabled and includes the following indicators:

* [Distance](#distance)
* [Duration](#duration)
* [Cadence](#cadence)
* [Elevation gain](#elevation)
* [Grade](#grade)
* [Average HR](#heartrate)
* [Calories](#calories)
* [Intensity level](#intensitylevel)
* [Training load](#trainingload)
* [VAM ](#vam)
* [Relative power ](#relativepower)
* [Adjusted power](#adjustedpower)
* [Adjusted pace](#adjustedpace)
* [Variability index](#variabilityindex)
* [Decoupling and efficiency factor](#decoupling)
  * [Efficiency factor \(EF\)](#efficiencyfactor)
  * [Decoupling \(pace\)](#speeddecoupling)
  * [Decoupling \(power](#powerdecoupling)

---

## Tools for analysis of completed activity

The following information is available in a completed activity, uploaded from sports watch or from smartphone.

### Comparing planned and actual values - “Overview” tab {#planfact}

Total planned and actual values are compared on the “Overview” tab.  
![](http://content.staminity.com/assets/images/ActivityPlanFact.png)

Percent of the planned activities’ completion is calculated based on the results of the planned and actual values of duration/distance and intensity indicators comparison.

If duration/distance and intensity values are set in the planned activity, than calculation is performed according to the following formula  
:

> % of completion = \(% of completion by duration/distance\) \* \(% of completion by intensity\)

If only duration/distance is set in the planned activity, then only the actual duration/distance for the given indicator is taken into account when calculating % of completion.

Percent of completion for structured activities is calculated based on the percent of completion for each segment of the activity.

### Indicators chart {#measurementchart}

There is an indicators chart for each completed activity.

![Управление графиком показателей в тренировке](https://content.staminity.com/assets/images/_new/activity/measures-chart-actions.gif)

The chart is composed by time or by distance and displays the following indicators \(the set depends on the list of indicators recorded by the device\):

* heart rate;
* power;
* pace/speed;
* elevation;
* cadence.

Elements of the chart management:  
![Управление графиком показателей в тренировке](https://content.staminity.com/assets/images/_new/activity/measures-chart.png)

* 1 - Choose a chart: **indicators chart/segments chart**. Is available for structured activities. The indicators chart is always displayed in all the remaining activities.
* 2 - Turn on/turn off the **auto scaling** attribute. If the attribute is turned on, then when you select a part of the chart, it changes its scale and the selected part is displayed at full width of the screen. 
* 3 -  **Set up **chart **smoothing**. By changing the position of the cursor you can set the degree of the indicators’ smoothing on the chart.
* 4 - Buttons allowing to **manage scale **of the chart. They appear if the auto scaling mode is turned off \(2\) 
* 5 - Choose **layout **of the chart: by duration or by distance; 
* 6 - Manage **set of indicators** to be displayed;

### Calculated indicators - “Details” tab {#metrics}

Staminity calculates a set of indicators as for the whole activity, as for a lap, segment or any part of the activity.

The calculated indicators are described below in the section  
 ["Calculated indicators"](#measures)

The indicators are located on the “Details” tab which is available for users with “Premium” and “Coach” tariffs enabled.

The indicators are available  
:

* for a whole activity;
* for a selected lap or several laps from the list of laps; 
* for a selected segment or several segments from the list of segments; 
* for any part of the activity, selected on the chart
  .

![Показатели в тренировке](http://content.staminity.com/assets/images/_new/activity/activity-details-measures.png)

### Peaks by distance and by time - “Details” tab {#peaks}

**Peak **- the maximum value of the moving average values for the selected interval by time or by distance.

_For example, a 10-seconds heart rate peak of the activity is the maximum moving average value of heart rate among all 10-seconds parts of the activity._

Peaks are calculated by time and by distance for the following indicators:

* heart rate
* pace
* power

![Пики](http://content.staminity.com/assets/images/_new/activity/activity-details-peaks.png)

As well as indicators, peaks are available:

* for a whole activity;
* for a selected lap or several laps from the list of laps; 
* for a selected segment or several segments from the list of segments; 
* for any part of the activity, selected on the chart

### Laps panel {#laps}

In the laps table you will find information about the main duration/distance and intensity indicators for each lap.  
![Управление графиком показателей в тренировке](https://content.staminity.com/assets/images/_new/activity/activity-laps.png)

The selected lap is displayed on the chart and on the map, and information about its calculated indicators and peaks is provided on the “Details” tab.

### Time in zones {#timeinzone}

The "Zones" tab displays the activity duration in each zone, for each intensity indicator.  
![Время в зонах](http://content.staminity.com/assets/images/settings/Staminity-time-in-zones-480.gif)

You can set up the training zones limits in the section ["Settings” - “Zones”](/basics/getting-started.md#trainingzones)

### Analysis of a structured activity completion, by segments {#segmentpanel}

For a structured activity, planned by segments, there are the following additional analysis options available:

![Анализ структурированной тренировки](https://content.staminity.com/assets/images/_new/activity/activity-structured-analysis.png)

* **1 - panel of the total values by segments**. 

It allows to choose a display mode “Planned” / “Completed” / “Groups”:

* Planned - planned values by segments;
* Completed - actual values by segments.
* Groups - allows to manage the mode of data display: per each segment or per group of segments
  .

![Анализ структурированной тренировки](https://content.staminity.com/assets/images/_new/activity/activity-segment-panel.gif)

* **2 - chart of planned/actual values by segments**. 

The x-axis is the total duration/distance of the activity, the y-axis - % LT for the intensity indicator set in plan \(heart rate, pace, power\).  
The color of the line shows the percent of completion of the segment:

* green - deviation from the plan does not exceed 10%;
  yellow - deviation from the plan from 10 to 20%;
  red - deviation from the plan is more than 20%.

3 - **table of planned/actual values by segments. **

When you select any segment in the table, then on the “Details” tab located to the left you will find indicators and peaks for the given segment.

---

# Indicators in the completed activity calculated by Staminity {#measures}

Staminity calculates a set of indicators as for the whole activity, as for a lap, segment or any part of the activity selected on the chart, based on the initial data registered by sports watch or by a program on the smartphone.

The information is displayed **on the “Details” tab** in activity and includes the following indicators  
:

* [Distance](#distance)
* [Duration](#duration)
* [Cadence](#cadence)
* [Elevation gain](#elevation)
* [Grade](#grade)
* [Average HR](#heartrate)
* [Calories](#calories)
* [Intensity level](#intensitylevel)
* [Training load](#trainingload)
* [VAM ](#vam)
* [Relative power ](#relativepower)
* [Adjusted power](#adjustedpower)
* [Adjusted pace ](#adjustedpace)
* [Variability index](#variabilityindex)
* [Decoupling and efficiency factor ](#decoupling)
  * [Efficiency factor \(EF\)](#efficiencyfactor)
  * [Decoupling \(pace\) ](#speeddecoupling)
  * [Decoupling \(power\)](#powerdecoupling)

### Distance {#distance}

Length of an activity, lap, segment or any interval:

* in kilometers or miles for running, cycling, skiing;
* in meters or yards - for swimmin  g.

### Duration {#duration}

Staminity calculates three indicators of activity duration:

* **Elapsed duration** - time spent on activity from the moment it started till the end. For example, if you started your activity at 9 a.m., then paused recording, by clicking on “Pause” for 10 minutes from 10 a.m. till 10:10 and finished activity at 10:30 then the “Elapsed time” will be 90 minutes.
* **Duration **- time spent on activity minus pauses. For the above-mentioned example it will be 80 minutes. 
* **Moving duration** - the number of seconds when the athlete moved during the activity. For the above-mentioned example, if during these 80 minutes an athlete twice stopped at the traffic light for 1 minute, without pausing his watch, then the moving duration will be 78 minutes.

### Cadence {#cadence}

Cadence - step frequency in running, pedaling speed in cycling, stroke frequency in swimming, etc. Is measured by the number of steps/turns/strokes per minute.

### Elevation gain {#elevation}

An altitude above sea level is registered for each activity, recorded by a device, with the help of a built-in barometer \(more accurately\) or data received from GPS/Glonass satellites \(less accurately\). Based on this information, the following indicators are calculated in Staminity:

* **Elevation **- sum of the elevation gain and loss;
* **Elevation gain** - sum of positive elevation differences of adjacent points;
* **Elevation loss** - sum of negative elevation differences of adjacent points

We are constantly upgrading the calculation algorithm in order to avoid incorrect registration of altitude by the device at separate points.

### Grade {#grade}

Slope grade of the selected part of activity. It is calculated in the following way:

> Grade = elevation / duration.

### Calories {#calories}

When calculating the amount of energy spent during activity, the duration and intensity of the activity, as well as gender, age, weight of an athlete stated in the application settings, are taken into account.

> For men: kcal= \[Duration\] x \[\(-55.0969 + 0.6309 x HR + 0.1988 x weight + 0.2017 x age\) / 4.184\]  
> For women: kcal= \[Duration\] x \[\(-20.4022 + 0.4472 x HR - 0.1263 x weight + 0.074 x age\) / 4.184\], where:
>
> * Duration - activity duration in minutes,
> * HR - average heart rate,
> * weight - weight in kilograms,
> * age - athlete’s age.
>
>
> If an athlete hasn’t set gender, height, and weight in settings, then the calculation is performed for a 30 years old man who weighs 70 kg.

Sources:

* Braydenwm.com: Calories and Power as a Function of Heart Rate \([http://www.braydenwm.com/calburn.htm](http://www.braydenwm.com/calburn.htm)\)
* Journal of Sports Sciences: Prediction of Energy Expenditure \([http://www.braydenwm.com/cal\_vs\_hr\_ref\_paper.pdf](http://www.braydenwm.com/cal_vs_hr_ref_paper.pdf)\)

### Уровень интенсивности {#intensitylevel}

Уровень интенсивности тренировки измеряется в процентах от значений ПАНО спортсмена по мощности, темпу или пульсу.

Если тренировка выполнена с измерителем мощности \(мощемером\), то

> Уровень интенсивности = Скорректированная мощность / [ПАНО](/basics/lactate-threshold.md) по мощности.

Если в тренировке мощность не фиксировалась, то расчет производится по темпу:

> Уровень интенсивности = Скорректированный темп / [ПАНО](/basics/lactate-threshold.md) по темпу

Если в тренировке отсутствует мощность и скорость \(например, при занятиях на тренажерах\), то расчет производится по пульсу:

> Уровень интенсивности = Средний пульс / [ПАНО](/basics/lactate-threshold.md) по пульсу.

### TL - Training load или Балл нагрузки {#trainingload}

Балл нагрузки рассчитывается с учетом интенсивности тренировки и ее продолжительности.  Нагрузка 100 баллов соответствует тренировке продолжительностью 1 час, выполняемой на уровне ПАНО по мощности \(для вела\), по темпу \(для бега и плавания\) или по пульсу \(для всех видов спорта\).

> Балл нагрузки = Уровень интенсивности \* Продолжительность тренировки в часах \* 100

### VAM или Вертикальная скорость {#vam}

VAM - это аббревиатура с итальянского **velocità ascensionale media**, что переводится как "средняя скорость подъема". Термин предложен итальянским физиологом и тренером по велоспорту Микеле Феррари \(Michele Ferrari\).  Показатель рассчитывается для любого выделенного отрезка дистанции и показывает скорость в метрах в час.

VAM широко используется в велоспорте для сравнения подготовленности спортсменов между собой и расчета [относительной мощности](#relativepower).

> VAM или Вертикальная скорость = Набор высоты / Продолжительность в часах.

Источник: [https://en.wikipedia.org/wiki/VAM\_\(bicycling\)](https://en.wikipedia.org/wiki/VAM_%28bicycling%29)

### Relative power или Относительная мощность {#relativepower}

Относительная мощность - расчетная величина, показывающая мощность в ваттах на килограмм. Это один из самых важных показателей для велосипедистов.

Относительная мощность рассчитывается на основании [VAM \(Вертикальной скорости\)](#vam) по формуле:

**Относительная мощность \(Вт/кг\) = VAM \(м/час\) / \(Фактор градиента x 100\)**,  
где Фактор градиента = 2 + \(Градиент в процентах / 10\).

Например, для градиента 6% фактор градиента = 2,6, а для градиента 11% Фактор градиента = 3,1.

Источник: [https://en.wikipedia.org/wiki/VAM\_\(bicycling\)](https://en.wikipedia.org/wiki/VAM_%28bicycling%29)

### Средняя мощность и Скорректированная мощность {#adjustedpower}

По тренировке, выполненной с измерителем мощности \(мощемером\), рассчитывается средняя мощность и скорректированная мощность.

**Средняя мощность** - среднее арифметическое от значений мощности, зарегистрированных в каждой точке тренировки или отрезка.

**Скорректированная мощность** определяет эквивалент средней мощности для тренировки/отрезка такой же продолжительности, при условии равномерного приложения усилий спортсменом.

> Зачем нужна скорректированная мощность.  
> Две тренировки с одинаковой продолжительностью и одной и той же средней мощностью могут потребовать разных усилий от спортсмена: тренировка на развитие аэробной выносливости на одном уровне интенсивности потребует меньше усилий, чем тренировка на развитие скорости, с несколькими быстрыми ускорениями через восстановительные отрезки.

В расчете скорректированной мощности используется сглаживание зарегистрированных мощемером показателей мощности в каждой точке тренировки.

При разработке алгоритма расчета скорректированной мощности в Стаминити были использованы книга Аллена и Коггана "Training and racing with a power meter" и работы Ф.Скибы по количественной оценке интенсивности тренировок велосипедистов, бегунов и триатлетов.

### Средний темп и скорректированный темп {#adjustedpace}

**Средний темп** рассчитывается для тренировки и любого выбранного отрезка как расстояние отрезка, деленное на его продолжительность.

Однако на темп тренировки сильно влияет профиль трассы: занятие, выполненное на треке, невозможно сравнить с тренировкой, выполненной на холмистой местности.  
Для того, чтобы можно было сравнить тренировки, выполненные на трассах с разным рельефом, был введен показатель скорректированного темпа.

**Скорректированный темп** - это расчетный темп с которым бы пробежал спортсмен тренировку аналогичной продолжительности по ровной трассе, затратив те же усилия, как в исходной тренировке/отрезке.

При разработке алгоритма расчета скорректированного темпа в Стаминити были использованы работы C.T.M Davies \(1973 год\), работы Alberto Minetti \(2003 год\), статья R.Lovett в Runnersworld \(2007 год\).

Мы постоянно работаем над уточнением алгоритма расчета скорректированного темпа.

### Индекс изменений {#variabilityindex}

Индекс изменений рассчитывается для тренировок с мощностью и показывает, насколько равномерно вы прилагали усилие на протяжении всего заезда.

> Индекс изменений = Скорректированная мощность / Средняя мощность

### Кардиокомпенсация и фактор эффективности {#decoupling}

Кардиокомпенсация представляет собой способность ЧСС повышаться со временем тренировки даже при стабильных уровнях мощности или темпа. У подготовленного с аэробной точки зрения спортсмена этот рост будет минимальным.

Величину кардиокомпенсации показывает изменение величины показателя «скорость к ЧСС» или "мощность к ЧСС" для 1 и 2 половины тренировки, в процентах. При этом сам показатель "Скорость к ЧСС" или "Мощность к ЧСС" называется **Фактором эффективности**.

Джо Фрил в "Библии триатлета" приводит следующий критерий оценки величины кардиокомпенсации:  
_"Если изменение величины показателя «скорость к ЧСС» \(или "мощность к ЧСС"\) составляет менее 5%, то упражнение считается «коррелированным». В этом случае физическую подготовку с точки зрения аэробного порога для гонки данной продолжительности ... можно считать полностью завершенной"_

В Стаминити расчет фактора эффективности, а также кардиокомпенсации производится как по всей тренировке, так и по выделенному отрезку.

##### Фактор эффективности {#efficiencyfactor}

> Фактор эффективности \(ФЭ\) = Средняя скорость / Средняя ЧСС,

а для тренировок с мощемером:

> Фактор эффективности \(ФЭ\) = Средняя мощность / Средняя ЧСС.

##### Темп:ЧСС  - кардиокомпенсация по темпу {#speeddecoupling}

Кардиокомпенсация по темпу показывает изменение величины Фактора эффективности, рассчитанного по скорости для первой и второй половины тренировки:

> **ФЭ1** = Средняя скорость / средняя ЧСС для 1 половины тренировки  
> **ФЭ2** = Средняя скорость / средняя ЧСС для 2 половины тренировки  
> **Темп:ЧСС** = \(ФЭ1 - ФЭ2\) / ФЭ1

##### Мощность:ЧСС  - кардиокомпенсация по мощности {#powerdecoupling}

Кардиокомпенсация по мощности показывает изменение Фактора эффективности, рассчитанного по мощности, для первой и второй половины тренировки:

> **ФЭ1** = Средняя мощность / средняя ЧСС для 1 половины тренировки  
> **ФЭ2** = Средняя мощность / средняя ЧСС для 2 половины тренировки  
> **Мощность:ЧСС** = \(ФЭ1 - ФЭ2\) / ФЭ1



