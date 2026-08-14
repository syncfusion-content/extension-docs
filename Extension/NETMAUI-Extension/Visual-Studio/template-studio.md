---
layout: post
title: Template Studio in .NET MAUI - Syncfusion®
description: Learn here about how to create the .NET MAUI application using Syncfusion .NET MAUI Components with the help of template studio.
platform: extension
component: Syncfusion<sup>®</sup> Extensions
documentation: ug
---

# Syncfusion<sup>®</sup> .NET MAUI Template Studio

The .NET MAUI Template Studio, provided by Syncfusion<sup>®</sup>, helps you build .NET MAUI applications using Syncfusion<sup>®</sup> components. It includes the necessary components, NuGet references, namespaces, and rendering code to streamline development. The Template Studio also offers a project wizard that simplifies the process of creating applications with Syncfusion<sup>®</sup> components.

The following steps will assist you in creating your **Syncfusion<sup>®</sup> .NET MAUI Application** through **Visual Studio 2022 or 2026**:

N> Before using the Syncfusion<sup>®</sup> .NET MAUI Project Template, verify whether the Syncfusion<sup>®</sup> .NET MAUI Template Studio extension is installed in the Visual Studio Extension Manager by clicking on **Extensions > Manage Extensions > Installed**. If the extension is not installed, install it by following the steps in the [download and installation](download-and-installation) help topic.

1. Open Visual Studio.

2. To develop the Syncfusion<sup>®</sup> .NET MAUI application, select one of the following options:

     **Option 1**

     Choose **Extensions > Syncfusion<sup>®</sup> > Essential Studio<sup>®</sup> for .NET MAUI > Create New Syncfusion<sup>®</sup> Project...** from the Visual Studio menu.

     ![CreateMenu](images/MenuProject.png)

     **Option 2**

     Choose **File > New > Project** from the menu. This launches a new dialog for creating a new application. Filtering the application type by **Syncfusion** or typing **Syncfusion** as a keyword in the search option can help you find the Syncfusion<sup>®</sup> templates for .NET MAUI.

     ![CreateNewWindow](images/ProjectTemplates.png)

3. Select the **Syncfusion<sup>®</sup> .NET MAUI Template Studio** template and click **Next**.

     ![CreateNewWizard](images/SyncfusionTemplate.png)

4. After launching the Syncfusion<sup>®</sup> .NET MAUI Template Studio, a configuration wizard will appear to help you set up your application. You can then choose from the available Syncfusion<sup>®</sup> .NET MAUI components which are listed based on category wise such as UI Component Suite, Grid SDK, Scheduler SDK, Gantt SDK, Chart SDK and Rich Text Editor SDK.

    ![Controls Section](images/ControlsTab.png)

    Choose the required control(s) by clicking the corresponding control box.

    To unselect the added control(s), use either one of the following options:

    **Option 1:** Click the corresponding selected control box.

    **Option 2:** Click the **'x'** button for the corresponding control in the control list under **Project Details**.

    N> **Note:** Choose at least one control to enable the **Features** and **Configuration** tabs.

5. The features for the selected controls are listed when you click on **Next** or the **Features** tab. You can choose the required features for the selected controls.

    ![Choose required Project Configuration](images/FeaturesTab.png)

    By unchecking the feature checkboxes, you can unselect features from the selected controls.

6. The Configuration section will load when you click **Next** or the **Configuration** tab. You can select the required .NET version (.NET 9.0 or .NET 10.0).

     ![Choose required Project Configuration](images/ConfigurationsTab.png)

     **Project details section**

     Under the Project Details section, you can modify the configurations and remove one or more controls from the selected controls.

     ![Choose required Project Details](images/ProjectDetails.png)

7. Click the **Create** button to create the Syncfusion<sup>®</sup> .NET MAUI application. The created Syncfusion<sup>®</sup> .NET MAUI application has the Syncfusion<sup>®</sup> NuGet packages and the rendering code for the selected Syncfusion<sup>®</sup> components.

     ![Readme](images/MauiApplication.png)

8. The Syncfusion<sup>®</sup> .NET MAUI application is configured with the latest Syncfusion<sup>®</sup> .NET MAUI NuGet package versions, namespaces, and component rendering code.

9. If you installed the trial setup or NuGet packages from nuget.org, you must register the Syncfusion<sup>®</sup> license key to your application, since Syncfusion<sup>®</sup> introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio<sup>®</sup> release. Navigate to the [help topic](https://help.syncfusion.com/common/essential-studio/licensing/overview#how-to-generate-syncfusion-license-key) to generate and register the Syncfusion<sup>®</sup> license key to your application. Refer to this [blog](https://www.syncfusion.com/blogs/post/whats-new-in-2018-volume-2.aspx) post for understanding the licensing changes introduced in Essential Studio<sup>®</sup>.
