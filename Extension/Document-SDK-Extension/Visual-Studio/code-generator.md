---
layout: post
title: Code Generator in Document SDK | Syncfusion
description: Learn here about adding the Document SDK Component using Code Generator of Syncfusion Document SDK Extension for Visual Studio.
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Add Blazor Document SDK component code

Syncfusion® provides a Code Generator component for the Blazor platform, allowing you to quickly insert Syncfusion® Document SDK component code into the desired location within a Razor file. The Syncfusion® extension automatically adds the necessary Syncfusion® Document SDK components along with the required namespaces, styles, and NuGet references. The Code Generator is a simple wizard that interacts with data models and integrates Syncfusion® Document SDK components with the required features into your application. 

The steps below will assist you to add the Syncfusion® Document SDK components code in your Blazor application through **Visual Studio 2022**:

N> Before using the Syncfusion® Blazor Document SDK Code Generator, check whether the Syncfusion® Blazor Document SDK Extension is installed or not in Visual Studio Extension Manager by clicking on the Extensions -> Manage Extensions -> Installed. If this extension not installed, install the extension by follow the steps from the [download and installation](download-and-installation) help topic.

1. Open your existing Blazor application or create a new Blazor application in the Visual Studio 2022 or Visual Studio 2022.

2. To open the Syncfusion® Blazor Document SDK Code Generator Wizard, select one of the options below in the Razor file, and then add Syncfusion® Document SDK components:

    **Option 1:**

    To generate a specific component code, right-click on the editor of the Razor file at the required line and Select the **Syncfusion® Blazor Document SDK Code Generator...**

    ![CodeGeneratorCommand](images/Code-Generator-Command.PNG)

    **Option 2:**

    Open the .razor file and place the cursor at the required line then choose **Extension -> Syncfusion® -> Essential Studio® for Document SDK -> Syncfusion® Blazor Document SDK Code Generator…** from the Visual Studio menu.

    ![CodeGeneratorMenu](images/Code-Generator-Menu.PNG)

3. The wizard for the Syncfusion® Blazor Document SDK Code Generator will appear. Choose a required control.

    ![CodeGeneratorWizard](images/Code-Generator-MainWizard.png)

    **Feature:** Selected Syncfusion® Document SDK component features are listed. You can select the required features.

    **Control requirements:** Contains the required user input fields for the selected component. You can provide the required value for those fields to add the component code.

    Click **Insert**. It generates the selected Syncfusion® Document SDK component render code and inserts it wherever the cursor is positioned.

    ![ComponentRenderCode](images/Code-Generator-ComponentRenderCode.PNG)

4. In the Output window, select the **Syncfusion® Blazor Document SDK Code Generator** from the **“Show output from”** drop-down to see the changes made to your application.

    ![OutputWindow](images/Code-Generator-OutputWindow.PNG)

5. The selected Syncfusion® Blazor Document SDK component code is inserted into the active Razor file, and the application is configured with the latest NuGet package, styles, and namespaces required for the selected component.

6. If you have installed the trial setup or NuGet packages from nuget.org, you must register the Syncfusion® license key to your application as Syncfusion® has introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio® release. Navigate to the [help topic](https://help.syncfusion.com/common/essential-studio/licensing/overview#how-to-generate-syncfusion-license-key) to generate and register the Syncfusion® license key to your application. Refer to this [blog](https://www.syncfusion.com/blogs/post/whats-new-in-2018-volume-2) post to know more about the licensing changes introduced in Essential Studio®.
