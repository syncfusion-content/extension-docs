---
layout: post
title: Template Studio in .NET MAUI - Syncfusion
description: Learn here about how to create the .NET MAUI application using Syncusion .NET MAUI Components with the help of template studio.
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Syncfusion<sup style="font-size:70%">&reg;</sup>  .NET MAUI Template Studio

The .NET MAUI Template Studio is provided by Syncfusion<sup style="font-size:70%">&reg;</sup>  and is used to build the Syncfusion<sup style="font-size:70%">&reg;</sup>  .NET MAUI applications using Syncfusion<sup style="font-size:70%">&reg;</sup>  components. The required Syncfusion<sup style="font-size:70%">&reg;</sup>  components, NuGet references, namespace, and component render code are all used to develop the Syncfusion<sup style="font-size:70%">&reg;</sup>  .NET MAUI applications. The Syncfusion<sup style="font-size:70%">&reg;</sup>  .NET MAUI Template Studio providing a project wizard to simplify the process for you to create an application using Syncfusion<sup style="font-size:70%">&reg;</sup>  components.

The following steps below will assist you to create your **Syncfusion .NET MAUI Application** through **Visual Studio 2022**:

N> Before use the Syncfusion<sup style="font-size:70%">&reg;</sup>  .NET MAUI Project Template, check whether the Syncfusion<sup style="font-size:70%">&reg;</sup>  .NET MAUI Template Studio Extension installed or not in Visual Studio Extension Manager by clicking on the Extensions -> Manage Extensions -> Installed. If this extension not installed, install the extension by follow the steps from the [download and installation](download-and-installation) help topic.

1. Open the Visual Studio 2022.

2. To develop the Syncfusion<sup style="font-size:70%">&reg;</sup>  .NET MAUI application, select one of the following options:

     **Option 1**

     Choose **Extension -> Syncfusion<sup style="font-size:70%">&reg;</sup>  -> Essential Studio<sup style="font-size:70%">&reg;</sup>  for .NET MAUI -> Create New Syncfusion<sup style="font-size:70%">&reg;</sup>  Project...** from the **Visual Studio menu**.

     ![CreateMenu](images/MenuProject.png)

     **Option 2**

     Choose **File -> New -> Project** from the menu. This launches a new dialogue for creating a new application. Filtering the application type by **Syncfusion** or typing **Syncfusion** as a keyword in the search option can help you to find the Syncfusion<sup style="font-size:70%">&reg;</sup>  templates for .NET MAUI.

     ![CreateNewWindow](images/ProjectTemplates.png)

3. Select the **Syncfusion .NET MAUI Template Studio** and click **Next**.

     ![CreateNewWizard](images/SyncfusionTemplate.png)

4. After launching the Syncfusion<sup style="font-size:70%">&reg;</sup>  .NET MAUI Template Studio, the wizard for configuring the Syncfusion<sup style="font-size:70%">&reg;</sup>  .NET MAUI application will appear. You can add the following Syncfusion<sup style="font-size:70%">&reg;</sup>  .NET MAUI components to the application. Choose the required Syncfusion<sup style="font-size:70%">&reg;</sup>  .NET MAUI components 

    ![Controls Section](images/ControlsTab.png)

    Choose the required control(s) by clicking the corresponding control box.

    To unselect the added control(s), use either one of the following options:

    **Option 1:** Click the corresponding selected control box.

    **Option 2:** Click ‘x’ button for the corresponding control in the control list from **Project Details**. 

    N> **Note:** Choose at least one control to enable the Features and Configuration tab.

5. The features for the selected controls are listed when you click on the **Next** or the **Features tab**. You can choose the required features for the selected controls.

    ![Choose required Project Configuration](images/FeaturesTab.png)    

    By unchecking the features checkboxes, you can unselect the features from the selected controls.

6. The Configuration section will load if you choose to click the **Next** button or the **Configuration tab**. You can select the required .NET Core Version (.NET 7.0 or .NET 8.0)

     ![Choose required Project Configuration](images/ConfigurationsTab.png)

     **Project details section**

     Under the Project Details section, you can modify the configurations and remove a control or controls from the selected controls.

     ![Choose required Project Details](images/ProjectDetails.png)

7. Click the **Create** button to create the Syncfusion<sup style="font-size:70%">&reg;</sup>  .NET MAUI application The created Syncfusion<sup style="font-size:70%">&reg;</sup>  .NET MAUI application has the Syncfusion<sup style="font-size:70%">&reg;</sup>  NuGet packages,and the rendering code for the selected Syncfusion<sup style="font-size:70%">&reg;</sup>  components.

     ![Readme](images/MauiApplication.png)

8. The Syncfusion<sup style="font-size:70%">&reg;</sup>  .NET MAUI application configures with most recent Syncfusion<sup style="font-size:70%">&reg;</sup>  .NET MAUI NuGet packages version, namespaces , and component render code for Syncfusion<sup style="font-size:70%">&reg;</sup>  components.

9. If you installed the trial setup or NuGet packages from nuget.org you must register the Syncfusion<sup style="font-size:70%">&reg;</sup>  license key to your application since Syncfusion<sup style="font-size:70%">&reg;</sup>  introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio<sup style="font-size:70%">&reg;</sup>  release. Navigate to the [help topic](https://help.syncfusion.com/common/essential-studio/licensing/license-key#how-to-generate-syncfusion-license-key) to generate and register the Syncfusion<sup style="font-size:70%">&reg;</sup>  license key to your application. Refer to this [blog](https://blog.syncfusion.com/post/Whats-New-in-2018-Volume-2-Licensing-Changes-in-the-1620x-Version-of-Essential-Studio.aspx?_ga=2.11237684.1233358434.1587355730-230058891.1567654773) post for understanding the licensing changes introduced in Essential Studio.
