# Training plans management

> Only users with completed coach profile can view, create and edit training plans.

In this article:

* [View training plans](#view)
* [Create a training plan](#createplan):
  * [Tab "General params"](#general)
  * [Tab "Store"](#store)
  * [Tab "Description"](#description)
  * [Tab "Samples"](#samples)
  * [Images in the plan](#images)
* [Plan activities, events, competitions within the plan](#buildplan)
* [Assign plan to athletes](#assignplan)
* [Cancel assignment](#deleteassignment)
* [Publish plan in the Store](#publish)
* [Publish plan updates in the Store](#publishupdates)
* [Unpublish plan](#unpublish)

### View training plans {#view}

In order to manage training plans you need to go to the section “Methodology” - “Training plans”

![Training plans for a coach](https://content.staminity.com/assets/images/_new/methodology/training-plan-management.png)

In this window you can view previously created plans, filter plans, create new and manage existing ones.

Structure of the window:

* 1 -  "Training plans" tab in Methodology. Using the other tabs you can manage [periodization schemes](/methodology/periodisation-schemes.md), [categories](/basics/categories.md) and[activity templates](/basics/templates.md). Information about how to work with these sections you can find in relevant articles. 
* 2 - plans filter. Enables to select only the needed training plans. 
* 3 -  training plans list. Plans are grouped by publication in the Store.
* 4 - plan’s context menu providing access to functions: "Create plan items", "Assignments", "Training plan publication", "Preview in Store" и "Unpublish plan".

![Training plans for a coach](https://content.staminity.com/assets/images/_new/methodology/tp-menu-items-2.png)

* 5 - dynamic plan attribute. Detailed information about plan types you can find in this [article](/basics/training-plan.md);

* 6 - training plan publication in the Store;

* 7 - attribute of changes available in the published plan. It is displayed when the current version of the plan differs from the one published in the Store.

* 8 - button to create a plan.

### Create a training plan {#createplan}

In order to create a training plan you need to go to the section “Methodology” - “Training plans” and click on the “Add” button \[8\].

There are several tabs in the new plan creation window.

* tab **"General params"** is available always, 
* tabs **"Store"**, **"Description"** и **"Samples"** are available only for plans meant for publication.

#### Tab "General params" {#general}

![Main params of the plan](https://content.staminity.com/assets/images/_new/methodology/tp-create-general.png)

On this tab you can set:

* **Plan name**
* **Sport** for which the training plan is designed;
* **Distance type**, for which the athlete is being prepared;
* **Plan for publication**. Enable this attribute for plans, that you want to publish in the Store;
* **Fixed dates**. Enable this attribute to create [plan with fixed dates](/basics/training-plan.md#fixed) and disable for [plans with non-fixed dates](/basics/training-plan.md#notfixed). If the attribute isn't set, then the plan will be created for unspecified dates \(Week 1, Day 1; Week 1, Day 2 and etc.\) Such universal plan can be used in any dates.
* **Start date**. You need to set the start date for plans with fixed dates.
* **Dynamic plan** \(only for plans with fixed dates\). Enable this attribute if you want to create a [dynamic plan](/basics/training-plan.md#dynamic) and transfer plan changes to assigned athletes. 
* **Tags**. Select attributes suitable for your plan. They will help you to filter plans and as for plans put up for sale, they will help customers to select the required plan.
* **Keywords**. In addition to the tags, you can set keywords. They are also meant to help customers in their plan selection.

#### Tab "Store" {#store}

> is available only for plans with enabled "For publish in Store" attribute

![Tab Store for a plan](https://content.staminity.com/assets/images/_new/methodology/tp-create-storeInfo.png)

On this tab you can set:

* Attribute **"Paid plan"**. Enable for plans that are put up for sale. If the attribute is enabled, set currency and price. As for now, only "Rubles" currency is available and the price should be within 300 - 10 000 RUB.

* **Язык плана** - язык, на котором автор приводит описание тренировок в плане. По-умолчанию русский.

* **Целевая аудитория** \(обязательное поле\) - опишите в свободной форме, для кого предназначен данный план.

* **Типовая неделя** \(обязательное поле\) - опишите в свободной форме нагрузки для типовой тренировочной недели в плане. Staminity также рассчитает и выведет на странице плана среднее, максимальное и минимальное значение по количеству тренировок, времени и расстоянию тренировок в плане, но ваше описание дополнит эту информацию.

* **График тренировочных объемов в плане** - система Staminity автоматически рассчитывает и выводит на странице плана график тренировочных объемов. Этот график может быть выведен по времени или по расстоянию. В зависимости от вашего подхода к планированию тренировок выберите нужное значение. По-умолчанию установлено значение "По времени".

* Признак **"Включены консультации"**. Если в стоимость плана включены консультации с вами, включите данный признак и опишите как часто, и каким образом покупатель может задать вам вопрос.

* Признак **"Очные тренировки"**. Если в стоимость плана включены очные тренировки с вами, включите данный признак и опишите частоту, время и место проведения очных тренировок.

* Признак **"Тренировочные задания разбиты по сегментам"**. Если при подготовке плана вы используете структурированные тренировки, включите данный признак и опишите для покупателей, для каких тренировок вы применяете разбивку по сегментам и какой показатель интенсивности используете. Это важно сделать, чтобы покупатели планов смогли настроить значение ПАНО по данному показателю интенсивности для корректного расчета плановой нагрузки.

#### Вкладка "Описание" {#description}

> доступна только для планов с признаком "Для публикации в магазине"

![Вкладка Описание для плана](https://content.staminity.com/assets/images/_new/methodology/tp-create-description-2.png)

В свободной форме укажите описание плана. Для планов на продажу описание выводится на странице плана в Магазине и будет одним из основных факторов при выборе плана.  
Сделайте описание запоминающимся, используйте форматированный текст, изображения, ссылки на видео.

#### Вкладка "Примеры" {#samples}

> доступна только для планов с признаком "Для публикации в магазине"

![Вкладка Примеры для плана](https://content.staminity.com/assets/images/_new/methodology/tp-create-samples.png)

На данной вкладке выводятся примеры тренировок. Чтобы выбрать тренировку или событие из плана в качестве примера, войдите в конструктор плана и отметьте признак "Сделать примером".

Примеры тренировок в плане помогут оценить потенциальным покупателям ваш подход к планированию и детальность описания.

#### Изображения плана {#images}

Изображения можно указать только для сохраненного плана.  
Для загрузки изображений перейдите на вкладку "Магазин" и выберите:

* "Изменить" для загрузки аватара \(кнопка доступна при наведении мышкой на изображение\);
* "Изменить фон" для загрузки основного изображения плана.

![Изображения плана](https://content.staminity.com/assets/images/_new/methodology/tp-create-images.png)

Загруженные изображения используются в магазине тренировочных планов, а также при просмотре страницы плана.  
Выбирайте качественные изображения, на которые у вас есть права для использования.

### Запланировать тренировки, события, соревнования в плане {#buildplan}

Для наполнения плана перейдите в конструктор плана. Для этого в контекстном меню плана выберите "Запланировать тренировки".

![Конструктор плана](https://content.staminity.com/assets/images/_new/methodology/tp-builder-navigation.png)

В окне конструктора тренировочного плана доступно:

* **1 - панель шаблонов**, как в календаре. Панель шаблонов доступна только пользователям с подключенными тарифами "Премиум" и "Тренер".
* **2 - название плана и селектор планов**. По нажатию на название плана откроется карточка плана для редактирования его параметров, а при нажатии на иконку выпадающего списка можно быстро перейти в конструктор нужного плана, а также вернуться в список планов.
* **3 - присвоения** для доступа к диалогу [присвоений](#assignplan) плана.
* 4 - **операции над тренировками**: копирование, вставка и удаление тренировок.
* 5 - выбор **режима отображения записей в плане**: подробно / кратко;
* 6 - **тренировочная неделя** плана.

Создание [тренировок](/basics/create-plan-activity.md), [событий](/basics/create-record.md) и [соревнований](/basics/competition.md) в тренировочном плане полностью повторяет эти действия в календаре ученика.

Тренировки в плане можно создавать:

* вручную;
* из шаблонов, выбирая шаблон при вводе тренировки;
* из шаблонов, перетаскивая шаблон с левой панели шаблонов;
* копированием из другой тренировки плана.

![Тренировки в плане Staminity](https://content.staminity.com/assets/images/methodology/training-plan-copy-paste.gif)

> **Обратите внимание!**  
> В заданиях тренировочного плана интенсивность всегда указывается в % от ПАНО. Это позволяет один план использовать для нескольких спортсменов с разным уровнем подготовки и уровнем ПАНО.

### Присвоения плана {#assignplan}

Тренировочный план можно присвоить своим спортсменам и все записи плана попадут в их тренировочный календарь.

Есть несколько способов присвоения плана.

В контекстном меню для строчки плана выберите "Присвоения":  
![Присвоения плана](https://content.staminity.com/assets/images/_new/methodology/tp-menu-items-2.png)

ИЛИ в конструкторе планов нажмите на иконку "Присвоить" \[3\].

В окне присвоения плана укажите:  
![Основные параметры плана](https://content.staminity.com/assets/images/_new/methodology/tp-assignment-window.png)

* **1 - Спортсмена или спортсменов**, в чьих календарях вы хотите видеть записи плана,
* **2 - Режим присвоения**, который определяет способ расчета дат присвоения. Можно выбрать присвоение в даты плана или присвоение в даты записей \(событий, тренировок, соревнований\). Расчетный блок дат \[5\] в карточке присвоения поможет выбрать нужный вам режим.
* **3 - Дату начала или дату окончания присвоения. **Выбор даты позволит применить план или начиная с определенной даты или по определенную дату. 
* **4 - Укажите дату**:

| Дата | Описание |
| :--- | :--- |
| Дата начала плана | Первый день недели, начиная с которой в календаре спортсмена будут показаны записи плана |
| Дата первой записи | Дата первой записи из плана в календаре спортсмена. Отличается от даты начала плана, если первая тренировка в плане запланирована не в первый день недели |
| Дата последней записи | Дата последней записи из плана в календаре спортсмена. Отличается от даты окончания плана, если последняя тренировка в плане запланирована не в последний день недели |
| Дата окончания плана | Последний день недели в календаре спортсмена, когда закончится тренировочный план |

* **5 - расчетный блок дат**, для помощи в правильности выбора параметров присвоения

* Для обновляемого плана также можно указать **признак трансляции изменений **- нужно ли для спортсменов транслировать изменения плана после присвоения.

**Важные особенности присвоения плана:**

1. **Тренировки в прошлом не создаются. **Если вы выберите даты так, что все или часть тренировок из плана окажутся в прошлом, то они не будут созданы в календаре спортсмена.
2. **Обновляемый план с трансляцией изменений можно присвоить только в даты плана. **Если выбрать другие даты присвоения, обновления плана транслироваться спортсменам не будут. 
3. **Изменения тренировок в прошлом в обновляемом плане не передаются спортсменам.** Если в обновляемом плане, присвоенном с трансляцией изменений, изменить тренировку за вчера, такие изменения не будут переданы спортсменам.

### Удалить присвоение плана {#deleteassignment}

В окне присвоений вы всегда можете видеть, кому и когда был присвоен данный план:

![Присвоения плана](https://content.staminity.com/assets/images/_new/methodology/tp-assignments.png)

Для удаления присвоения войдите в контекстное меню присвоения и выберите функцию "Удалить".

После удаления присвоения из календаря спортсмена будут удалены все невыполненные тренировки по данному плану.

### Опубликовать план {#publish}

Для публикации плана в Магазине:

1 - Проверьте, как увидят ваш план потенциальные покупатели. Для этого в контекстном меню плана выберите **"Предпросмотр \(текущая версия\)**:

![Основные параметры плана](https://content.staminity.com/assets/images/_new/methodology/tp-menu-items-2.png)

Тщательно проверьте корректность информации и при необходимости внесите изменения в [характеристики плана](#createplan), указанные при создании.

2 - Перейдите в диалог публикации плана. Для этого в контекстном меню выберите пункт **"Публикация"**.

3 - Убедитесь, что в окне публикации плана пройдены все проверки.  
![Основные параметры плана](https://content.staminity.com/assets/images/_new/methodology/tp-publication.png)

Если часть проверок не пройдена, публикация будет невозможна. Устраните замечания, изменив значения характеристик плана или в настройках \(если не заполнен [профиль Автора планов](/basics/plan-author-profile.md)\).

4 - Нажмите "Опубликовать" и подтвердите публикацию.

### Опубликовать изменения плана {#publishupdates}

Любые изменения, которые произошли в плане после публикации в магазине, автоматически НЕ ОТРАЖАЮТСЯ в магазине планов.

Чтобы в магазине планов появилась последняя актуальная версия плана, изменения необходимо опубликовать.

Красная иконка магазина планов в списке опубликованных планов покажет, что у плана есть неопубликованные изменения.

![Неопубликованы изменения](https://content.staminity.com/assets/images/_new/methodology/tp-red-icon.png)

Для публикации изменений нажмите на иконку или перейдите в окно публикации из контекстного меню плана. Убедитесь, что в окне публикации пройдены все проверки и нажмите "Опубликовать".

### Снять план с публикации {#unpublish}

В любой момент план можно снять с публикации и удалить из магазина.

Для снятия плана с публикации откройте окно публикации и нажмите на кнопку "Снять с публикации".

Кнопка доступна для любых опубликованных планов.

