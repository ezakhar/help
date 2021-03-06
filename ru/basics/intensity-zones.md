# Определение тренировочных зон

Тренировочные зоны – это уровни интенсивности, в которых необходимо выполнять те или иные тренировки для достижения лучшего тренировочного эффекта.  
Существует несколько известных методов определения границ своих тренировочных зон, отличающихся количеством зон, базой для их расчета и границами зон.  
В Staminity мы реализовали расчет границ зон интенсивности по следующим методам:

* **Зоны частоты сердечных сокращений \(зоны по пульсу\):**

  * [Метод Джо Фрила \(Joe Friel\), 7 зон по пульсу от ПАНО](#frielhr)
  * [Метод Янсена \(Peter Janssen\), 6 зон от ЧССмакс](#janssenhr)
  * [Метод Карвонена \(Martti Karvonen\), 5 зон от резерва ЧСС](#karvonenhr)

* **Зоны по темпу/скорости**

  * [Метод Джо Фрила \(Joe Friel\), 7 зон по темпу/скорости от ПАНО](#frielspeed)

* **Зоны по мощности**

  * [Метод Коггана \(Andy Coggan\), 7 зон по мощности от ПАНО](#cogganpower)

## Зоны по пульсу

#### Метод Джо Фрила \(Joe Friel\), 7 зон по пульсу от ПАНО {#frielhr}

Джо Фрил в "Библии триатлета" определяет семь тренировочных зон, границы которых рассчитываются в процентах от значения ПАНО спортсмена по пульсу, отдельно для бега и велоспорта:

| Зоны | Границы зон для бега | Границы зон для велосипеда |
| :--- | :--- | :--- |
| Зона 1. Recovery | До 85% от ПАНО | До 81% от ПАНО |
| Зона 2. Aerobic | 85-89% от ПАНО | 81-89% от ПАНО |
| Зона 3. Tempo | 90-94% от ПАНО | 90-93% от ПАНО |
| Зона 4. SubThreshold | 95-99% от ПАНО | 94-99% от ПАНО |
| Зона 5.a. SuperThreshold | 100-102% от ПАНО | 100-102% от ПАНО |
| Зона 5.b. Aerobic capacity | 103-106% от ПАНО | 103-106% от ПАНО |
| Зона 5.c. Anaerobic capacity | Выше 106% от ПАНО | Выше 106% от ПАНО |

> Источник данных для таблицы: [http://www.trainingbible.com/joesblog/2009/11/quick-guide-to-setting-zones.html](http://www.trainingbible.com/joesblog/2009/11/quick-guide-to-setting-zones.html)

Чтобы рассчитать границы пульсовых зон по Фрилу, введите значение ПАНО, выберите в настройках зон соответствующий метод расчета и сохраните изменения:
![](http://264710.selcdn.ru/assets/images/settings/FrielHRZones.png)

**Восстановление \(зона 1\)**. Тренировки в границах зоны 1 включают в себя самые простые упражнения, которые помогают опытным спортсменам восстановиться после тяжелых упражнений или периода сложных тренировок.

**Экстенсивная выносливость \(зона 2\)**. Для данного типа интенсивности нормой являются продолжительные тренировки по развитию выносливости. При проведении упражнений на таком уровне усилий происходит формирование, а затем и поддержание аэробной выносливости. Лактат в организме вырабатывается в сравнительно небольших количествах, это позволяет проводить продолжительные, но в то же время комфортные тренировочные сессии на пределе аэробной выносливости спортсмена \(или чуть выше его\).

**Интенсивная выносливость \(зона 3\)**. При незначительном повышении интенсивности производство лактата начинает повышаться по сравнению с предыдущими уровнями, так как помимо медленно сокращающихся мышечных волокон в дело вступают быстро сокращающиеся.

**Порог интенсивности \(зоны 4 и 5a\)**. Возможно, самая важная тренировочная зона для многоборцев. Уровень усилий здесь чуть ниже или чуть выше ПАНО. При такой работе максимально задействуются аэробные механизмы, основное напряжение приходится на медленно сокращающиеся мышечные волокна и системы организма, вырабатывающие энергию. Значительная ее часть начинает производиться за счет  
анаэробных механизмов; в организме возникают улучшения, связанные с невосприимчивостью к действию лактата и ускорением утилизации продуктов его распада. Кроме того, быстро сокращающиеся мышечные волокна начинают проявлять характеристики медленно сокращающихся. Для того чтобы отделить друг от друга усилия, прилагаемые выше и ниже ПАНО, порог интенсивности разбит на две зоны.

**Анаэробная выносливость \(зона 5b\).** На этом этапе интенсивность оказывается на уровне выше ПАНО. Типичными для него являются интервальные тренировки. Данный этап способствует росту и развитию быстро сокращающихся мышечных волокон, развивается способность организма противостоять действию лактата и утилизировать его. Высокий объем тренировок анаэробной выносливости является самой распространенной причиной перетренированности у серьезных спортсменов, поэтому к подобным тренировкам следует относиться с осторожностью, и за ними обязательно должен следовать продолжительный период восстановления.

**Мощность \(зона 5c\)**. Тренировка мощности не является особенно важной для спортсменов, занимающихся многоборьем. Исключение составляют случаи, когда спортсмену сложно нарастить мышечную массу или когда для набора скорости ему необходимо задействовать быстро сокращающиеся мышечные волокна. Упражнения на развитие мощности должны состоять из коротких, взрывных интервалов, разделяемых длительными периодами восстановления.

> Источник данных для описания зон: Джо Фрил, "Библия триатлета". Издательство "Манн, Иванов, Фербер", Москва, 2011 год

####  {#janssenhr}

#### Метод Янсена \(Peter Janssen\), 6 зон от ЧССмакс {#janssenhr}

Питер Янсен в книге "ЧСС, лактат и тренировки на выносливость" определяет 6 зон интенсивности, рассчитывая их границы в процентах от ЧССмакс.

**ЧССмакс** - это максимальная частота сердечных сокращений, наблюдавшаяся у спортсмена при тестировании в лаборатории или во время соревнований.

| Зоны | Границы зон по пульсу |
| :--- | :--- |
| Зона R. Восстановительная | 60-70% от ЧССмакс |
| Зона A1. Аэробная 1 | 70-80% от ЧССмакс |
| Зона A2. Аэробная 2 | 80-85% от ЧССмакс |
| Зона E1. Развивающая 1 | 85-90% от ЧССмакс |
| Зона E2. Развивающая 2 | 90-95% от ЧССмакс |
| Зона An1. Анаэробная 1 | 95-100% от ЧССмакс |

Чтобы рассчитать границы пульсовых зон по Янсену, ведите значение ЧССмакс, выберите в настройках зон соответствующий метод расчета и сохраните изменения:
![](http://264710.selcdn.ru/assets/images/settings/JanssenHRZones.png)

Обозначения зон:

1. **R - recovery** - восстановительная. Очень низкая интенсивность.
2. **A - aerobic **- аэробная зона. Разделяется на две подзоны, с низкой \(А1\) и средней \(А2\) интенсивностью. В аэробной зоне энергия поставляется исключительно за счет аэробных процессов.
3. **E - endurance** - развивающая зона \(от англ. endurance – выносливость\). Развивающая зона расположена чуть ниже и чуть выше анаэробного порога, поэтому энергия поставляется частично аэробным путем и частично анаэробным. Также выделяются две подзоны: E1 - транзитная зона, E2 - высокоинтенсивная выносливость. 
4. **An - anaerobic** - анаэробная зона. Основана на анаэробном гликолизе, реакции образования энергии протекают в условиях недостаточного поступления кислорода,что ведет к образованию и накоплению молочной кислоты.

#### Метод Карвонена \(Martti Karvonen\), 5 зон от резерва ЧСС {#karvonenhr}

Финский физиолог Мартти Карвонен предложил рассчитывать интенсивность тренировки от **ЧСС резерва**, который определяется как **ЧССмакс - ЧССпокоя**.

С учетом этого 5 зон интенсивности определяются по следующим правилам: 

| Зоны | Границы зон по пульсу  |
| :--- | :--- |
| Зона 1 | ЧССпокоя + ЧССрезерв \* \(50 - 60%\) |
| Зона 2 | ЧССпокоя + ЧССрезерв \* \(60 - 70%\) |
| Зона 3 | ЧССпокоя + ЧССрезерв \* \(70 - 80%\) |
| Зона 4 | ЧССпокоя + ЧССрезерв \* \(80 - 90%\) |
| Зона 5 | ЧССпокоя + ЧССрезерв \* \(90 - 100%\) |

Чтобы рассчитать границы пульсовых зон по Карвонену, введите значение ЧССпокоя и ЧССмакс, выберите в настройках зон соответствующий метод расчета и сохраните изменения:
![](http://264710.selcdn.ru/assets/images/settings/KarvonenHRZones.png)


## Зоны по темпу

#### Метод Джо Фрила \(Joe Friel\), 7 зон по темпу/скорости от ПАНО {#frielspeed}

| Зоны | Границы зон по темпу |
| :--- | :--- |
| Зона 1. Recovery | Медленнее, чем 129% от ПАНО по темпу |
| Зона 2. Aerobic | 114-129% от ПАНО по темпу |
| Зона 3. Tempo | 106-113% от ПАНО по темпу |
| Зона 4. SubThreshold | 101-105% от ПАНО по темпу |
| Зона 5.a. SuperThreshold | 97-100% от ПАНО по темпу |
| Зона 5.b. Aerobic capacity | 90-96% от ПАНО по темпу |
| Зона 5.c. Anaerobic capacity | Быстрее 90% от ПАНО по темпу |

> Источник данных для таблицы: [http://www.trainingbible.com/joesblog/2009/11/quick-guide-to-setting-zones.html](http://www.trainingbible.com/joesblog/2009/11/quick-guide-to-setting-zones.html)

Чтобы рассчитать границы темповых зон по Фрилу, введите значение ПАНО по темпу, выберите в настройках зон соответствующий метод расчета и сохраните изменения:
![](http://264710.selcdn.ru/assets/images/settings/FrielPaceZones.png)

Описания зон см. в разделе [Метод Джо Фрила \(Joe Friel\), 7 зон по пульсу от ПАНО](#frielhr)

## Зоны по мощности

#### Метод Коггана \(Andy Coggan\), 7 зон по мощности от ПАНО {#cogganpower}

| Зоны | Границы зон мощности для велосипеда |
| :--- | :--- |
| Зона 1. Active recovery | Меньше 55% от ПАНО по мощности |
| Зона 2. Endurance | 55-74% от ПАНО |
| Зона 3. Tempo | 75-89% от ПАНО |
| Зона 4. Lactate threshold | 90-104% от ПАНО |
| Зона 5. VO2 max | 105-120% от ПАНО |
| Зона 6. Anaerobic capacity | 121-150% от ПАНО |
| Зона 7. Neuromuscular power | Более 150% от ПАНО |

> Источник данных для таблицы: [http://m-ivanov.com/2016/08/kak-exat-bystree-sammari-na-knigu-trenirovki-po-moshhnosti-xanter-allen-i-endryu-koggan/](http://m-ivanov.com/2016/08/kak-exat-bystree-sammari-na-knigu-trenirovki-po-moshhnosti-xanter-allen-i-endryu-koggan/)

Чтобы рассчитать границы зон мощности по Коггану, введите значение ПАНО по мощности, выберите в настройках зон соответствующий метод расчета и сохраните изменения:
![](http://264710.selcdn.ru/assets/images/settings/CogganPowerZones.png)