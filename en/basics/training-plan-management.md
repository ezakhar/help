# Training plans management

> Only users with completed coach profile canview, create and edit training plans

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
* [Publish plan in the Store](#publishupdates)
* [Unpublish plan](#unpublish)

### View training plans {#view}

In order to manage training plans you need to go to the section “Methodology” - “Training plans”

![Тренировочные планы для тренера](https://264710.selcdn.ru/assets/images/_new/methodology/training-plan-management.png)

In this window you can view previously created plans, filter plans, create new and manage existing ones.

Structure of the window:

* 1 - "Training plans" tab in Methodology. Using the other tabs you can manage [periodization schemes](/methodology/periodisation-schemes.md), [categories](/basics/categories.md) and [activity templates](/basics/templates.md). Information about how to work with these sections you can find in relevant articles; 
* 2 - plans filter. Enables to select only the needed training plans; 
* 3 - training plans list. Plans are grouped by publication in the Store;
* 4 - plan’s context menu providing access to functions: "Create plan items", "Assignments", "Training plan publication", "Preview in Store" и "Unpublish plan";

![Тренировочные планы для тренера](https://264710.selcdn.ru/assets/images/_new/methodology/tp-menu-items-2.png)

* 5 -  dynamic plan attribute. Detailed information about plan types you can find in this [article](/basics/training-plan.md);

* 6 - training plan publication in the Store;

* attribute of changes available in thepublished plan. It is displayed when the currentversion of the plan differs from the onepublished in the Store; 
* 8 - button to create a plan.

### Create a training plan {#createplan}

In order to create a training plan you need to go to the section “Methodology” - “Training plans” and click on the “Add” button \[8\].

There are several tabs in the new plan creation window

* tab "**General params**" is available always, 
* tabs "**Store**", "**Description**" и "**Samples**" are available only for plans meant for publication.

#### Tab "General params" {#general}

![General params of the plan](https://264710.selcdn.ru/assets/images/_new/methodology/tp-create-general.png)

On this tab you can set:

* **Plan name**
* **Sport **for which the training plan is designed;
* **Distance type**, for which the athlete is being prepared;
* **Plan for publication**. Enable this attribute for plans, that you want to publish in the Store;
* **Fixed dates**. Enable this attribute to create [plan with fixed dates](/basics/training-plan.md#fixed) and disable for [plans with non-fixed dates](/basics/training-plan.md#notfixed).  If the attribute isn't set, then the plan will be created for unspecified dates \(Week 1, Day 1; Week 1, Day 2 and etc.\) Such universal plan can be used in any dates.
* **Start date**. You need to set the start date for plans with fixed dates.
* **Dynamic plan** \(only for plans with fixed dates\). Enable this attribute if you want to create a [dynamic plan](/basics/training-plan.md#dynamic) and transfer plan changes to assigned athletes. 
* **Tags**. Select attributes suitable for your plan. They will help you to filter plans and as for plans put up for sale, they will help customers to select the required plan.
* **Keywords**. In addition to the tags, you can set keywords. They are also meant to help customers in their plan selection.

#### Tab "Store" {#store}

> is available only for plans with enabled "For publish in Store" attribute

![Tab &quot;Store&quot;](https://264710.selcdn.ru/assets/images/_new/methodology/tp-create-storeInfo.png)

On this tab you can set:

* Attribute "**Paid plan**". Enable for plans that are put up for sale. If the attribute is enabled, set currency and price. As for now, only "Rubles" currency is available and the price should be within 300 - 10 000 RUB.

* **Plan language** is a language used by the author to describe activities within the plan. By default it's Russian.

* **Target audience** \(obligatory field\) - describe for whom this plan has been designed.

* **Typical week** \(obligatory field\) - describe training load for typical training week within the plan. Staminity will calculate and display on the plan page the average, maximum and minimum values based on the number of activities, duration and distance of activities within the plan, but your description will make the information complete.

* **Chart of training volumes within the plan** -  Staminity system will automatically calculate the training volumes chart and display it on the plan page. This chart can be calculated based on duration or distance. You can select the required value depending on your planning approach. By default “By duration” value is set.

* Attribute **“Consultations included”**. If the plan’s cost include possibility of consulting with you, then you need to enable this attribute and describe how often the buyer can contact you and how exactly..

* Attribute**"Offline activities included"**. If the plan's cost includes offline activities with you, then you need to enable this attribute and describe frequency, time and place of these activities.

* Attribute  **"Structured activities included"**. In case if you use structured activities within the plan, then you need to enable this attribute and describe which activities you have divided to segments and which intensity indicator  you have used. It is important and must be done to enable athletes to set up the LT value based on this intensity indicator in order to calculate the training load in a correct way.

#### Tab "Description" {#description}

> Is available only for plans with “For publish in Store” attribute enabled

![Вкладка Описание для плана](https://264710.selcdn.ru/assets/images/_new/methodology/tp-create-description-2.png)

Describe the plan as you want to. For plans intended for sale, description is displayed on the plan page in the Store and greatly affect the plan selection.  
Make it impressive and memorable, use text formattin, insert images and links to videos.

#### Tab “Samples” {#samples}

> Is available only for plans with “For publish in Store” attribute enabled.

![Tab Samples](https://264710.selcdn.ru/assets/images/_new/methodology/tp-create-samples.png)

On this tab you will find activity samples. In order to set an activity or event from the plan as a sample, go to the plan constructor and enable the “Set as sample” attribute.

Activity samples provided in the plan will help potential clients to study your planning approach and accuracy of description.

#### Plan images {#images}

Images can be set only for a saved plan.  
In order to download images you need to go to the “Store” tab and select:

* "Edit" to download new plan image \(this button becomes available when you hover over the image\);
* "Edit background" to download the main image of the plan.

![Plan images](https://264710.selcdn.ru/assets/images/_new/methodology/tp-create-images.png)

Downloaded images are used in the Store and when viewing the plan page.  
Select high-quality images which you have the right to use.

### Plan activities, events, competitions within the plan {#buildplan}

In order to fill the plan, you need to go to the plan constructor. To do it, you should select “Create plan items” in the context menu of the plan.

![Plan constructor](https://264710.selcdn.ru/assets/images/_new/methodology/tp-builder-navigation.png)

In the plan constructor window you will find:

* **1 - templates panel** just like in the calendar.  Templates panel is available only for users with “Coach” and “Premium” tariffs enabled.
* **2 - plan name** and plan selector. When clicking on the plan name, the plan card will open where you can edit its parameters, and when clicking on the drop-down list icon, you can quickly go to the constructor of the required plan, and also return to the plans list.
* **3 - assignments.** You need to click here to access the dialog box enabling to [assign](#assignplan) the plan.
* **4 - operations with activities**: copy, paste and delete activities
* **5 **- select the **mode of displaying records in the plan**: in detail/briefly;
* **6 - training week** of the plan.

The process of [activities](/basics/create-plan-activity.md), [events](/basics/create-record.md) and [competitions](/basics/competition.md) creation within the plan is similar to the process of their creation in the athlete’s calendar.  

Activities within the plan can be  created:

* manually;
* from templates, by selecting template when filling in information in activity;
* from templates, by dragging and dropping template from the templates panel located to the left;
* By copying from another activity within the plan.

![Activities within the plan in Staminity](https://264710.selcdn.ru/assets/images/methodology/training-plan-copy-paste.gif)

> **Please note!**  
> In the training plan activities, intensity is always set in % of LT. It enables to use the same plan for several athletes with different fitness and LT level.

### Assign plan to athletes {#assignplan}

Training plan can be assigned to your athletes and all plan items will appear in their training calendars.

There are several ways to assign a plan.

In the context menu for the plan line select "Assignments":  
![Plan assignments](https://264710.selcdn.ru/assets/images/_new/methodology/tp-menu-items-2.png)

OR in the plan constructor click on the "Assign" icon \[3\].

In the plan assignment window you need to set:  
![General params of the plan](https://264710.selcdn.ru/assets/images/_new/methodology/tp-assignment-window.png)

* **1 - An athlete or athletes**, in whose calendars plan items should appear,
* **2 - Assinment mode**, which determines the method of assignment dates calculation. Ypu can select assinment in the plan dates or in the item \(events, activities, competitions\) dates. The calculated block of dates \[5\] in the assignments card will help you to choose the mode you need.
* **3 - Start date and end date of assignment. **Date selection will help you to apply plan either starting from a specific date or till a specific date. 
* **4 - Set a date**:

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

![Присвоения плана](https://264710.selcdn.ru/assets/images/_new/methodology/tp-assignments.png)

Для удаления присвоения войдите в контекстное меню присвоения и выберите функцию "Удалить".

После удаления присвоения из календаря спортсмена будут удалены все невыполненные тренировки по данному плану.

### Опубликовать план {#publish}

Для публикации плана в Магазине:

1 - Проверьте, как увидят ваш план потенциальные покупатели. Для этого в контекстном меню плана выберите **"Предпросмотр \(текущая версия\)**:

![Основные параметры плана](https://264710.selcdn.ru/assets/images/_new/methodology/tp-menu-items-2.png)

Тщательно проверьте корректность информации и при необходимости внесите изменения в [характеристики плана](#createplan), указанные при создании.

2 - Перейдите в диалог публикации плана. Для этого в контекстном меню выберите пункт **"Публикация"**.

3 - Убедитесь, что в окне публикации плана пройдены все проверки.   
![Основные параметры плана](https://264710.selcdn.ru/assets/images/_new/methodology/tp-publication.png)

Если часть проверок не пройдена, публикация будет невозможна. Устраните замечания, изменив значения характеристик плана или в настройках \(если не заполнен [профиль Автора планов](/basics/plan-author-profile.md)\).

4 - Нажмите "Опубликовать" и подтвердите публикацию.

### Опубликовать изменения плана {#publishupdates}

Любые изменения, которые произошли в плане после публикации в магазине, автоматически НЕ ОТРАЖАЮТСЯ в магазине планов.

Чтобы в магазине планов появилась последняя актуальная версия плана, изменения необходимо опубликовать.

Красная иконка магазина планов в списке опубликованных планов покажет, что у плана есть неопубликованные изменения.

![Неопубликованы изменения](https://264710.selcdn.ru/assets/images/_new/methodology/tp-red-icon.png)

Для публикации изменений нажмите на иконку или перейдите в окно публикации из контекстного меню плана. Убедитесь, что в окне публикации пройдены все проверки и нажмите "Опубликовать".

### Снять план с публикации {#unpublish}

В любой момент план можно снять с публикации и удалить из магазина.

Для снятия плана с публикации откройте окно публикации и нажмите на кнопку "Снять с публикации".

Кнопка доступна для любых опубликованных планов.

