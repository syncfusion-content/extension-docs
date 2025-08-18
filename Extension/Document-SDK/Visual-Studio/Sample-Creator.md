---
layout: post
title: Sample Creator | Document SDK | Syncfusion
description: Sample Creator is the utility that allows you to create Syncfusion Document SDK Projects along with the samples based on Controls and Features selection
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Sample Creator

Sample Creator is the utility that allows you to create Syncfusion<sup style="font-size:70%">&reg;</sup> Document SDK Projects along with the samples based on platform and Features selection.

I> The Syncfusion<sup style="font-size:70%">&reg;</sup> Document SDK Sample Creator utility is available from v30.1.37

## Create Syncfusion<sup style="font-size:70%">&reg;</sup> Document SDK Web Application from Sample Creator

The following steps help you to create the Syncfusion<sup style="font-size:70%">&reg;</sup> Document SDK Web Application via the Sample Creator utility.

1. To launch Document SDK Sample Creator application, follow either one of the options below: 

   **Option 1:**   
   Click **Syncfusion<sup style="font-size:70%">&reg;</sup> Menu** and choose **Essential Studio<sup style="font-size:70%">&reg;</sup> for Document SDK > Launch Sample Creator…** in **Visual Studio**.
   
   ![launch the Sample Creator via Syncfusion<sup style="font-size:70%">&reg;</sup> menu](images/Syncfusion_Menu_SampleCreator.png)

   N> In Visual Studio 2019, Syncfusion<sup style="font-size:70%">&reg;</sup> menu available under Extension in Visual Studio menu.

   **Option 2:**  
   Launch the Syncfusion<sup style="font-size:70%">&reg;</sup> Document SDK Control Panel. Select the Sample Creator button to launch the Document SDK Sample Creator application. Refer to the following screenshot for more information.

   ![Syncfusion<sup style="font-size:70%">&reg;</sup> Document SDK control panel to launch the Sample Creator](images/SampleCreator-img1.png)

2. Syncfusion<sup style="font-size:70%">&reg;</sup> Sample Creator Wizard displaying the **Controls and its Feature Selection** section

   ![Syncfusion<sup style="font-size:70%">&reg;</sup> Document SDK Sample Creator wizard](images/SampleCreator-img2.png)


### Controls Selection

Listed here are the Syncfusion<sup style="font-size:70%">&reg;</sup> Document SDK controls so you can choose the required controls.

   ![Syncfusion<sup style="font-size:70%">&reg;</sup> Document Sdk Sample Creator Controls selection](images/SampleCreator-img3.png)

### Project Configuration

1. You can configure the following project details in the Sample Creator.

   * Platform Type – Select the type of platform either ASP.NET Core or MVC.

      - ASP.NET Core:
         - Select the VS Version - Version 2022
         - .NET Framework – Choose the .NET Framework version either .NET 9.0 or .NET 8.0

         ![Syncfusion<sup style="font-size:70%">&reg;</sup> Document SDK Sample Creator project configuration section](images/SampleCreator-core.png)

      - ASP .NET MVC:
         - Select the VS Version - Choose the Visual Studio Version
         - .NET Framework – Choose the .NET Framework version

         ![Syncfusion<sup style="font-size:70%">&reg;</sup> Document SDK Sample Creator project configuration section](images/SampleCreator-mvc.png)
   
   
   * Assets From – Load the Syncfusion<sup style="font-size:70%">&reg;</sup> assets to ASP.NET Core Project, either Bower, CDN or Installed Location.

   * Name – Name your Syncfusion<sup style="font-size:70%">&reg;</sup> Document SDK Application.

   * Location – Choose the target location of your project.

   * Theme Selection – Choose the required theme.The Theme Preview section shows the controls preview before create the Syncfusion<sup style="font-size:70%">&reg;</sup> project.


2. Click **Create** button. After creating the project, open the project by clicking **Yes**. If you click **No**, the corresponding location of the project will be opened. Refer to the following screenshot for more information.

    ![create](images/sample-creator-create.png)

3. The new Syncfusion<sup style="font-size:70%">&reg;</sup> Document SDK project is created with the resources.

    * Added the required Controllers and View files in the project.

      - ASP.NET Core:

        ![required controllers](images/required-controllers.png)

      - ASP.NET MVC:

        ![required controllers](images/required-controllers1.png)

    * Included the required Syncfusion<sup style="font-size:70%">&reg;</sup> scripts and theme files.

      - ASP.NET Core:

        ![script-theme references](images/scripts-theme.png)

      - ASP.NET MVC:

        ![script-theme references](images/scripts-theme1.png)


    * The required Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies are added for selected controls under Project Reference.

      - ASP.NET Core:

        ![syncfusion<sup style="font-size:70%">&reg;</sup> assemblies](images/syncfusion-assemblies.png)

      - ASP .NET MVC:

         ![syncfusion<sup style="font-size:70%">&reg;</sup> assemblies](images/syncfusion-assemblies1.png)
