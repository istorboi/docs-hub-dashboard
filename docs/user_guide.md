# User's Guide

## Introduction
<div align="justify">

Although the PIXEL Platform has 5 components, users interact with it through the dashboard user interface.
The Pixel Dashboard and Notification component provides a web User Interface to interact with the platform. 
It is needed to have an account to access to the platform.

<p align="center">
<img src="https://github.com/pixel-ports/docs-hub-dashboard/raw/master/docs/img/user_guide/introduction.png" alt="Introduction" align="center" />
</p>

</div>
<br/><br/>

## Login
<div align="justify">

After entering the url of the PIXEL platform, a login form appears allowing you access the application.  You need to have an account to enter into the application. Depending on your permissions you will have different functionalities available.
<p align="center">
<img src="https://github.com/pixel-ports/docs-hub-dashboard/raw/master/docs/img/user_guide/Login_page.png" alt="Login" align="center" />
</p>

</div>
<br/><br/>

## Layout
<div align="justify">

The pixel platform has 3 main areas:
  - *Menu*. Provides access to different functionalities. (1)
  - *Header*. Provides navigation and configuration properties. (2)
  - *Content*. Provides the functionalities to interact with. (3)

<p align="center">
<img src="https://github.com/pixel-ports/docs-hub-dashboard/raw/master/docs/img/user_guide/layout.png" alt="Layout" align="center" />
</p>

**Menu**<br/>
The menu allows the user to access all the available functionalities of the platform.
By default, the menu appears in extended mode, but it can be extended through the compact / extend icon.

<p align="center">
<img src="https://github.com/pixel-ports/docs-hub-dashboard/raw/master/docs/img/user_guide/menu.png" alt="Menu" align="center" />
</p>

The functionalities available are:
  - *Overview*. List of information visualization to control port operations.
  - *Views*. Manage the visualizations to be shown in the overview functionality.
  - *Dashboard*. Manage the creation of reports.
  - *Permission*. Manage the roles and uses of the platform.
  - *PAS Information*. Manage the Port Activity Scenario information.
  - *Map*. Geographical information system with real-time sensors.
  - *Alerts*. Manage alerts definition and subscription.
  - *Operational Tools*. Manage Models and Algorithms.

**Header**<br/>
The header provides a ser of functionalities to navigates between different sections, search elements, language selection and profile information.
On the left-hand side, you will find the following functionalities:
 -	*Collapse / Expand menu*
 -	*Breadcrumbs*
 -	*Functionality button bar*

<p align="center">
<img src="https://github.com/pixel-ports/docs-hub-dashboard/raw/master/docs/img/user_guide/header.png" alt="Header" align="center" />
</p>

On the right hand-side, you will find the following functionalities:
  - *Search functionality* (1)
  - *Language selection* (2)
  - *Profile options* (3)
  - *Profile details* (4)
  - *LogOut* (5)

<p align="center">
<img src="https://github.com/pixel-ports/docs-hub-dashboard/raw/master/docs/img/user_guide/header_right-side.png" alt="Header right side" align="center" />
</p>

**Content**<br/>
The content area is the largest display area and shows the content of the functionality selected in the menu.
At the top, there is a tab bar that allow quick access to previously opened content.

<p align="center">
<img src="https://github.com/pixel-ports/docs-hub-dashboard/raw/master/docs/img/user_guide/content.png" alt="Content" align="center" />
</p>

</div>
<br/><br/>

## Permission
<div align="justify">

The permission functionality allows you to manage the roles and users of the platform. This functionality uses internally the security layer of PIXEL.

**Role permission**<br/>
The role permission functionality allows to manage the roles of the platform “the different types of users that will use the platform and what actions they can execute”.
This functionality will only be available to administrators
The list of roles shows the roles defined and provides the functionality to manage them  (Create, Edit, Delete).
<p align="center">
<img src="https://github.com/pixel-ports/docs-hub-dashboard/raw/master/docs/img/user_guide/RoleList.png" alt="List of Roles" align="center" />
</p>

If you want to create a new role, select the "New role" button. After selecting the button, a form appears that allows to define the characteristics of the new role.

<p align="center">
<img src="https://github.com/pixel-ports/docs-hub-dashboard/raw/master/docs/img/user_guide/NewRole.png" alt="New Role" align="center" />
</p>

**Users**<br/>
The user functionality allows to manage the users that can access to the platform. In the list of users functionality provides a list of users created.

<p align="center">
<img src="https://github.com/pixel-ports/docs-hub-dashboard/raw/master/docs/img/user_guide/UserList.png" alt="User's List" align="center" />
</p>

If you want to create a new user, select the "New user" button. After selecting the button, a form appears that allows to define the properties of a new user.

<p align="center">
<img src="https://github.com/pixel-ports/docs-hub-dashboard/raw/master/docs/img/user_guide/NewUser.png" alt="New User" align="center" />
</p>

</div>
<br/><br/>

## Overview and Views
<div align="justify">

These functionalities allow to define and show the most suitable visualizations to monitor the port activity depending on the specific needs of each port.

Note: Most of the visualizations that a user can create are related with model executions. Before creating these visualizations, the user has to add a model an run it form the operational tools functionality.

**Views**<br/>
From the *list of views* , the user can manage the mots appropriate visualizations to control the port activity. The list of views provides a search mechanism (1) to filter by name, source or type the views showed in the table. The Add (2) button allows to create a new visualization. For each visualization (4), the user can change the visualization status.   Only the enabled visualization will appear in the overview.

<p align="center">
<img src="https://github.com/pixel-ports/docs-hub-dashboard/raw/master/docs/img/user_guide/ListViews.png" alt="Views' List" align="center" />
</p>

The add visualization functionality has three steps.
  -	1st Step: the user chooses the model for which he wants to create a new visualization. Currently the  platform provides visualization for the PAS model and for the Predictive ETD algorithm. Moreover, the user can create a custom visualization.
<p align="center">
<img src="https://github.com/pixel-ports/docs-hub-dashboard/raw/master/docs/img/user_guide/FirstStep.png" alt="First step" align="center" />
</p>

  -	2nd Step: In the second step, the user chooses the visualization most appropriated for the analysis he wants to perform.
<p align="center">
<img src="https://github.com/pixel-ports/docs-hub-dashboard/raw/master/docs/img/user_guide/SecondStep.png" alt="Second step" align="center" />
</p>

  -	3rd Step: In the third step, the user define the name of the visualization and select the proper model execution to be shown.
<p align="center">
<img src="https://github.com/pixel-ports/docs-hub-dashboard/raw/master/docs/img/user_guide/ThirdStep.png" alt="Third step" align="center" />
</p>

**Process of creating and visualizing a new view**<br/>
To show a new visualization on the overview you need to follow these steps:
  - In the list view, click the add button (1)
  - Complete the three steps for creating a new  visualization (2)
  -	Look for the visualization created (3)
  -	Change the status from disabled to enabled (4)
<p align="center">
<img src="https://github.com/pixel-ports/docs-hub-dashboard/raw/master/docs/img/user_guide/CreateNewView.png" alt="Create new view" align="center" />
</p>

If a user wants to create a custom visualization, independent from any model, in the process of creating a new visualization, the user has to select the custom option in the step 1. In the next figure, you  can see how a user can create a custom visualization to show in an iframe the content of other web.

<p align="center">
<img src="https://github.com/pixel-ports/docs-hub-dashboard/raw/master/docs/img/user_guide/CustomView.png" alt="Custom view" align="center" />
</p>

**Overviews**<br/>
The overview is the main control panel to monitor and analyse the port activities.  The overview will show all the enabled views in a table of two cols. Next figure depicts the layout of the visualizations showed in the overview.

<p align="center">
<img src="https://github.com/pixel-ports/docs-hub-dashboard/raw/master/docs/img/user_guide/CustomView.png" alt="Custom view" align="center" />
</p>

Next picture illustrates an example of the overviews with three visualizations.

<p align="center">
<img src="https://github.com/pixel-ports/docs-hub-dashboard/raw/master/docs/img/user_guide/Layout_overview.png" alt="Layout Overview" align="center" />
</p>

</div>
<br/><br/>

## Dashboard - Reporting
<div align="justify">

This functionality allows the users to create flexible dashboards and reports thanks to a mechanism that lets the user insert different types of information in any place/size of the report. During the creation of the dashboard the user can drag and drop and resize any visual component to make the most adequate report for each case.

<p align="center">
<img src="https://github.com/pixel-ports/docs-hub-dashboard/raw/master/docs/img/user_guide/dashboard_management.png" alt="Dashboard Management" align="center" />
</p>

**Dashboard creation / edition**<br/>
If a user wants to create a new dashboard (click Add button) or edit an existing one (click Edit button)

<p align="center">
<img src="https://github.com/pixel-ports/docs-hub-dashboard/raw/master/docs/img/user_guide/dashboard_creation.png" alt="Dashboard Creation" align="center" />
</p>

**Dashboard visualization and print**<br/>
If a user wants to create a new dashboard (click Add button) or edit an existing one (click Edit button)

<p align="center">
<img src="https://github.com/pixel-ports/docs-hub-dashboard/raw/master/docs/img/user_guide/dashboard_visualization.png" alt="Dashboard Visualization" align="center" />
</p>

</div>
<br/><br/>

## PAS Information
<div align="justify">

The PAS Information allows to define the information needed to use the Port Activity Scenario model (PAS Model).

The information has been divided in 3 sections:
  -	*Rules*. Cargo Categories, Shift works and priorities information.
  -	*Resources*. Machines and Areas information.
  -	*Supplier Chain*. Suppier chain information.

<p align="center">
<img src="https://github.com/pixel-ports/docs-hub-dashboard/raw/master/docs/img/user_guide/pas_information.png" alt="PAS Information" align="center" />
</p>

**Rules**<br/>
The rules functionality allows to create the information related with cargo types, shift works and priorities. It is possible to create several rules. After finalising the definition of the rules, it is possible to publish the information (export to Information Hub) to be used by the PAS Model.
After creating a new rule (Add Rule button), the user can complete the content of the rule through the Edit button that opens a new page. From this page, it is possible to define cargo categories, shift works and priorities.

<p align="center">
<img src="https://github.com/pixel-ports/docs-hub-dashboard/raw/master/docs/img/user_guide/rulesList.png" alt="Rules List" align="center" />
</p>

*Cargoes category*<br/>
The form for the creation of charge categories is divided into 3 steps. In the Step 1 general property information is filled in. In the step 2 preference properties are filled in. In the step 3 range property information is filled in.

<p align="center">
<img src="https://github.com/pixel-ports/docs-hub-dashboard/raw/master/docs/img/user_guide/createCargoCategory.png" alt="Create Cargo Category" align="center" />
</p>

*ShiftWork*<br/>
The form for the creation of ShiftWorks allows you to create different work schedules for a port that will later be assigned to different activities.

<p align="center">
<img src="https://github.com/pixel-ports/docs-hub-dashboard/raw/master/docs/img/user_guide/createShiftWork.png" alt="Create ShiftWork" align="center" />
</p>

*Priorities*<br/>
The priorities form allows you to define the priorities for attending to the different cargo categories.

<p align="center">
<img src="https://github.com/pixel-ports/docs-hub-dashboard/raw/master/docs/img/user_guide/addPriorities.png" alt="Add Priorities" align="center" />
</p>

**Resources**<br/>
The resources functionality allows to create the information related with areas and machines. It is possible to create several resources. After finalising the definition of the resources, it is possible to publish the information (export to Information Hub) to be used by the PAS Model.

After creating a new resource (Add Resource button), the user can complete the content of the resource through the Edit button that opens a new page. From this page, it is possible to define areas and machines.

<p align="center">
<img src="https://github.com/pixel-ports/docs-hub-dashboard/raw/master/docs/img/user_guide/resourceList.png" alt="Resources' List" align="center" />
</p>

*Area*<br/>
The area form allows you to define a new port Area where a where port activities take place.

<p align="center">
<img src="https://github.com/pixel-ports/docs-hub-dashboard/raw/master/docs/img/user_guide/createArea.png" alt="Create Area" align="center" />
</p>

*Machine*<br/>
The Add Machine form allows you to create a new machine and it is divided into 3 steps. In the Step 1 general property information is filled in. In the step 2 throughput properties are filled in. In the step 3 range consumption information is filled in.

<p align="center">
<img src="https://github.com/pixel-ports/docs-hub-dashboard/raw/master/docs/img/user_guide/createMachine.png" alt="Create Machine" align="center" />
</p>

**Supplier Chain**<br/>
The supplier chain functionality allows to create the information related with a supply chain and its steps. It is possible to create several supply chains. After finalising the definition of the supply chains, it is possible to publish the information (export to Information Hub) to be used by the PAS Model.
After creating a new supply chain (Add Supplier Chain), the user can complete the content of the supply chain through the Edit button that opens a new page. From this page, it is possible to define the details, steps, and compatibilities of a supply chain.

<p align="center">
<img src="https://github.com/pixel-ports/docs-hub-dashboard/raw/master/docs/img/user_guide/supplierChainList.png" alt="Supplier Chain's List" align="center" />
</p>

*Detail*<br/>
The detail form allows you to define the detail properties of the supply chain.

<p align="center">
<img src="https://github.com/pixel-ports/docs-hub-dashboard/raw/master/docs/img/user_guide/createSupplierChain.png" alt="Create Detail" align="center" />
</p>

*Steps*<br/>
The Add Steps form allows you to create the different steps of the supply chain and it is divided into 3 steps. In the Step 1 general property information is filled in. In the step 2 scheduling properties are filled in. In the step 3 work information is filled in.

<p align="center">
<img src="https://github.com/pixel-ports/docs-hub-dashboard/raw/master/docs/img/user_guide/createSteps.png" alt="Create Steps" align="center" />
</p>

*Compatibility*<br/>
The compatibility form allows you to define the elements (cargo categories, direction, areas and shift works )  compatible with the supply chain.

<p align="center">
<img src="https://github.com/pixel-ports/docs-hub-dashboard/raw/master/docs/img/user_guide/createCompatibility.png" alt="Create Compatibility" align="center" />
</p>

**Publish - Export to Information Hub**<br/>
After defining rules, resources, and supply chains, you should publish this information to be available for the PAS Model. To publish the information created you only need to press the “Export to IH” button available in in list of rules, resources, and supply chains.  After executing the action, you will see  the execution result with the name of the index created.  You will need to specify the name of the index when you run a new instance of the model.

<p align="center">
<img src="https://github.com/pixel-ports/docs-hub-dashboard/raw/master/docs/img/user_guide/exportToIH.png" alt="Export to IH" align="center" />
</p>

Every time that a user updates any information related with the Port Activity scenario it is needed to use export the information (Export to IH) to have the new data available for the PAS model.

</div>
<br/><br/>

## Map
<div align="justify">
   
The maps functionality allows the user to see the location of several devices or sensors. It is possible to filter by a specific type of device. In the figure, you can see the location in the map of the tide sensors that measure the tide level. If you select (click on the icon) a sensor, a new panel appears showing details of the sensor and the captured values.

<p align="center">
<img src="https://github.com/pixel-ports/docs-hub-dashboard/raw/master/docs/img/user_guide/Map.png" alt="Map" align="center" />
</p>

</div>
<br/><br/>

## Operational Tools
<div align="justify">
PIXEL is a flexible analytical platform; through the operational tools (OP Tools) you can install new analytical functionalities and perform as many analyses as you need. 
In PIXEL the analytical functions have been grouped in 2 types. The functionalities based on models(1) and the functionalities based on predictive algorithms (2). Both can be executed on demand (3) or can be programmed to be executed periodically (4) . After the executions (5), graphs (6) or KPIs (7) can be created to show the results of the model/algorithm executions

<p align="center">
<img src="https://github.com/pixel-ports/docs-hub-dashboard/raw/master/docs/img/user_guide/otools_diagram.png" alt="OTools' Diagram" align="center" />
</p>

**Models**<br/>
The models functionality is part of the OP Tools and  allows you to manage the models added/installed in the platform . The Add model button allow us to create/ add a new model into the PIXEL platform, the information needed is the label or name of the model and the docker name.  All the models are encapsulated into docker components.

<p align="center">
<img src="https://github.com/pixel-ports/docs-hub-dashboard/raw/master/docs/img/user_guide/modelsManagement.png" alt="Models Management" align="center" />
</p>

*Schedule*<br/>
The schedule functionality allows you to manage the scheduled executions of a model. To Add  a new schedule (1) you have to provide the name of the schedule, the parameters of the model and the schedule information. Each model has different Parameters  (2), in the example we have chosen the “vessels-SEI” property.

<p align="center">
<img src="https://github.com/pixel-ports/docs-hub-dashboard/raw/master/docs/img/user_guide/scheduleModel.png" alt="Schedule a Model" align="center" />
</p>

After the model is executed, it is possible to verify the execution results from the view button (1). At any moment, the user can pause / run (play)  (2) the scheduled executions of a model.

<p align="center">
<img src="https://github.com/pixel-ports/docs-hub-dashboard/raw/master/docs/img/user_guide/executionResult.png" alt="Result of the execution" align="center" />
</p>

*Run Model*<br/>
The Run functionality allows you to manage the on demand executions of a model. To Add  a new Run(1) you have to provide the name of the run and the parameters of the model. Each model has different Parameters. As soon as you confirm the run, the model is executed. The status property of the table will show the “Finished” value when the execution ends. From the view (2) button, it is possible to view the result of the execution.

<p align="center">
<img src="https://github.com/pixel-ports/docs-hub-dashboard/raw/master/docs/img/user_guide/runModel.png" alt="Run a Model" align="center" />
</p>

**Predictive Algorithms**<br/>
The Predictive Algorithms functionality is part of the OP Tools and  allows you to manage the algorithms added/installed in the platform. The functionality is equivalent to the model functionality, but in this case instead of running Artificial Intelligent Models, it runs predictive algorithms.

<p align="center">
<img src="https://github.com/pixel-ports/docs-hub-dashboard/raw/master/docs/img/user_guide/predictiveManagement.png" alt="Predictive Algorithms" align="center" />
</p>

**KPIs**<br/>
The KPI functionality allows you to create different KPI related with model execution. There are two types of KPIs, environmental KPIs and Operational KPI. You can define as many KPIs (1) as you need and show the trends of them (2).

<p align="center">
<img src="https://github.com/pixel-ports/docs-hub-dashboard/raw/master/docs/img/user_guide/kpiManagement.png" alt="KPIs" align="center" />
</p>

</div>
