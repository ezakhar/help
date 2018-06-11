# Templates

* [What are templates](#templates)
* [Differences between template and activity](#template-and-activity)
* [View and manage templates](#managetemplates)
* [Create a template from activity](#templatefromactivity)
* [Create a template manually](#createtemplate)
* [Create an activity using template](#createsingleactivity)
* [Create an activity for several athletes using one template](#createmultipleactivity)


### What are templates{#templates}

**Template** - saved set of activity parameters which can be used when creating new activities. 

By saving activities that you often complete by yourself or plan for your athletes as templates, you'll be able to create new activities in more simple and fast way. 

### Differences between template and activity{#template-and-activity}

Template differs from activity by: 

![Templates and activities](http://264710.selcdn.ru/assets/images/_new/methodology/templates-view.png)

* **1 - Name**. The name will help to differ templates from one another and select the required template when planning activities.

* **2 - Attribute “Favorite”.** Templates with this attribute will be highlighted in the list so that you could find them faster. 

* **3 - Intensity only in %LT.** The same template can be used to create activities for athletes with different fitness, that's why in a template you can set intensity only in % of LT ([lactate threshold](/basics/lactate-threshold.md)). 

Depending on the athletes’ LT, activities with different intensity level will be created for different athletes when using the same template:  

![Templates and activities](http://264710.selcdn.ru/assets/images/_new/methodology/template-and-activity.png)

### View and manage templates{#managetemplates}
The list of templates is located in the “Methodology” view on the “Activity templates” tab. Templates are displayed for the selected sport and category.

![Templates and activities](http://264710.selcdn.ru/assets/images/_new/methodology/templates-navigation.png)

* 1 - **"Activity templates" tab in the Methodology view**. On the other tabs you will find ["Training plans"](/basics/training-plan.md), ["Periodization schemes"](/methodology/periodisation-schemes.md) and ["Activity categories"](/basics/categories.md), information about how to manage them is given in relevant articles.

* 2 - Select **sport**. 
* 3 - **Categories** for the selected sport. An icon with a number located next to the category shows how many templates are available for the selected category. 
* 4 - **Templates panel**. Here are displayed templates for the selected sport [2] and categories [3].
* 5 - Button "**Add template**".

All templates are grouped by type:
* **My templates** - user's templates. 
* **Coach templates** - templates which have been used by the coach when planning your activities.  
* **Club templates** - templates which have been created by the club management to be used by the coaches when planning activities for the athletes.

You can edit only "My templates" but you can change order of templates in all groups. 
In order for the most commonly used templates to be displayed at the beginning of the list, drag and drop template to the required place.


### Create a template from activity{#templatefromactivity}

You can create a template from any activity which has planned values: both yours and your athlete's; both planned and completed. 

In order to create a template:  
1) in the activity window click on the "Save as template" button  
2) check and edit parameters of the template in the emerged window  
3) save the template
4) if needed, check that template has appeared in the list of available templates.

<iframe width="720" height="405" src="https://www.youtube.com/embed/eUqBAQs1LKA?rel=0" frameborder="0" allowfullscreen></iframe>


### Create a template manually {#createtemplate}

In order to create a template you need to: 
1\) Open menu item "Methodology" and proceed to the "Activity templates" tab,
2\) Select sport and category,  
3\) Click on the "Create template" button,  
4\) Fill in parameters of the template and save it.

The process of template creation is similar to the process of  [simple activity](/basics/create-plan-activity.md#planactivity) or [structured activity](/basics/create-plan-activity.md#structuredactivity) creation. 

### Create an activity using template {#createsingleactivity}

Templates greatly speed up the process of activity creation. If you often complete activities of the same type, create a template and save your time when planning.

The most convenient way to create an activity using a template is to drag and drop the activity from the templates panel located to the left to the required date in the calendar:

![Create activity using template from the templates panel](https://264710.selcdn.ru/assets/images/_new/activity/activity-create-from-template-ezgif.gif)


Also, you can select a template when creating an activity after having set sport and category. 

![Create activity using template](https://264710.selcdn.ru/assets/images/_new/activity/activity-create-from-template-2-ezgif.gif)

### Create an activity for several athletes using one template {#createmultipleactivity}

When using a template you can create an activity for several athletes at once. It will come in handy if you have a group of athletes who train according to the same plan or if you hold general group activities. 

In order to create several activities at once using one template:
1. Start creating an activity, set sport and category, select template.
2. In the activity menu select the "Add athletes" item
3. Select athletes and set the attribute indicating whether you want the intensity level to be recalculated based on LT for these athletes.
4. Save the activity. It will appear in calendars of all selected athletes. 

![Create activity using template](https://264710.selcdn.ru/assets/images/_new/methodology/activity-for-2-athletes.gif)


> We would like to illustrate effect of the "Recalculate based on LT" attribute. Let's assume that a coach has a template of an activity with the intensity set at the level of 80% of the LTHR. Using this template, the coach creates an activity for an athlete 1 with LT 170. When filling in task, he adds another two athletes "Athlete 2" and "Athlete 3" who have different LT levels.  
>
> The table shows intensity of the athletes' 1,2, and 3 activities depending on the value of the "Recalculate based on LT" attribute.

|  | Recalculate based on LT = "YES" | Recalculate based on LT  = "NO" |
| :--- | :--- | :--- |
| Athlete 1. LT 170 bpm| Planned HR value  = 136 bpm | Planned HR value = 136 bpm |
| Athlete 2. LT 180 bpm | Planned HR value = 144 bpm| Planned HR value = 136 bpm|
| Athlete 3. LT 185 bpm | Planned HR value = 148 bpm| Planned HR value = 136 bpm|