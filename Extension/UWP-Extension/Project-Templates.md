---
layout: post
title: Syncfusion UWP Project Templates | Extension | Syncfusion
description: Syncfusion provides the Visual Studio Project Templates for the Syncfusion UWP platform to create Syncfusion UWP Applications
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Syncfusion<sup style="font-size:70%">&reg;</sup> Project Templates

Syncfusion<sup style="font-size:70%">&reg;</sup> provides the **Visual** **Studio** **Project** **Templates** for the Syncfusion<sup style="font-size:70%">&reg;</sup> UWP platform to create Syncfusion<sup style="font-size:70%">&reg;</sup> UWP Applications.  

I> The Syncfusion<sup style="font-size:70%">&reg;</sup> UWP project templates are available from v15.3.0.26.  

## Create Syncfusion<sup style="font-size:70%">&reg;</sup> UWP Application

The following steps help you to create the **Syncfusion<sup style="font-size:70%">&reg;</sup>** **UWP** **Application** through the **Visual** **Studio** **Project** **Template**.

> Before use the Syncfusion<sup style="font-size:70%">&reg;</sup> UWP Project Template, check whether the **UWP Extensions - Syncfusion<sup style="font-size:70%">&reg;</sup>** installed or not in Visual Studio Extension Manager by clicking on the Tools -> Extensions and Updates -> Installed for Visual Studio 2017 or lower and for Visual Studio 2019 by clicking on the Extensions -> Manage Extensions -> Installed.

1. To create a Syncfusion<sup style="font-size:70%">&reg;</sup> UWP project, follow either one of the options below:

   **Option 1:**   
   Click **Syncfusion<sup style="font-size:70%">&reg;</sup> Menu** and choose **Essential Studio<sup style="font-size:70%">&reg;</sup> for UWP > Create New Syncfusion<sup style="font-size:70%">&reg;</sup> Project…** in **Visual Studio**.
   
   ![Choose Syncfusion<sup style="font-size:70%">&reg;</sup> Universal Windows Application from Visual Studio new project dialog via Syncfusion menu](Syncfusion-Project-Templates_images/Syncfusion_Menu_ProjectTemplate.png)

   N> In Visual Studio 2019, Syncfusion<sup style="font-size:70%">&reg;</sup> menu under Extension in Visual Studio menu.

   **Option 2:**  
   Choose **File > New > Project** and navigate to **Syncfusion<sup style="font-size:70%">&reg;</sup> > Windows Universal> Syncfusion<sup style="font-size:70%">&reg;</sup> Universal Windows Application** in **Visual Studio**.

   ![Choose Syncfusion<sup style="font-size:70%">&reg;</sup> Universal Windows Application from Visual Studio new project dialog](Syncfusion-Project-Templates_images/Syncfusion-Project-Templates-img1.jpeg)

2. Name the **Project** and choose the destination location if required, then click **OK**. 

3. Then Project Configuration Wizard appears. Choose the options to configure the Syncfusion<sup style="font-size:70%">&reg;</sup> Universal Windows Platform application by using the following Project Configuration dialog.

   ### Project configurations:

   **Language:** Select the language, either Visual C# or Visual Basic.

   **Reference Type:** Select the reference type of UWP Project, either Assemblies or SDK.

   **Target Version:** Choose the Target Version of the UWP platform that your project is targeting. This sets the **TargetPlatformVersion** setting in your project file.

   **Minimum Version:** Choose the Minimum Version of the UWP platform that your project can work with. This sets the **TargetPlatformMinVersion** setting in your project file.

   **Template Type:** Select the template type of UWP Project, either Blank or Hamburger Menu or Hamburger Menu (MVVM).

   **Components:** Choose the required Syncfusion<sup style="font-size:70%">&reg;</sup> components to configure.
   
   ![Syncfusion<sup style="font-size:70%">&reg;</sup> UWP Project configuration wizard](Syncfusion-Project-Templates_images/Syncfusion-Project-Templates-img4.jpeg)
   
   N> If SDK is chosen as the reference type, then all the Syncfusion<sup style="font-size:70%">&reg;</sup> UWP controls will be added. So, you no need to select any components.
   
4. Once you click Create button, the Syncfusion<sup style="font-size:70%">&reg;</sup> UWP Application is created.

5. Once the Project Configuration Wizard is done, the Syncfusion<sup style="font-size:70%">&reg;</sup> UWP Application is created with required SDK/references and pages.

   ![Syncfusion<sup style="font-size:70%">&reg;</sup> UWP Project created with SDK reference](Syncfusion-Project-Templates_images/Syncfusion-Project-Templates-img5.jpeg)

   ![Syncfusion<sup style="font-size:70%">&reg;</sup> UWP Project created with readme](Syncfusion-Project-Templates_images/Syncfusion-Project-Templates-img7.PNG)

6. Then, Syncfusion<sup style="font-size:70%">&reg;</sup> licensing registration required message box will be shown as follow, if you are installed the trial setup or NuGet packages since Syncfusion<sup style="font-size:70%">&reg;</sup> introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio<sup style="font-size:70%">&reg;</sup> release. Please navigate to the [help topic](https://help.syncfusion.com/common/essential-studio/licensing/license-key#how-to-generate-syncfusion-license-key) which is shown in the licensing message box to generate and register the Syncfusion<sup style="font-size:70%">&reg;</sup> license key to your project. Refer to this [blog](https://blog.syncfusion.com/post/Whats-New-in-2018-Volume-2-Licensing-Changes-in-the-1620x-Version-of-Essential-Studio.aspx) post for understanding the licensing changes introduced in Essential Studio<sup style="font-size:70%">&reg;</sup>.

   ![Syncfusion<sup style="font-size:70%">&reg;</sup> license registration required information dialog in Syncfusion<sup style="font-size:70%">&reg;</sup> UWP Project](Syncfusion-Project-Templates_images/Syncfusion-Project-Templates-img6.jpeg)   


