---
layout: post
title: Add a Syncfusion References| WinForms | Syncfusion
description: Syncfusion Reference Manager extension is an add-in to add the Syncfusion references into the WinForms application
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Add Reference for WinForms

Syncfusion<sup style="font-size:70%">&reg;</sup> Reference Manager is the Visual Studio Add-In for the WinForms platform. It adds the Syncfusion<sup style="font-size:70%">&reg;</sup> assembly reference to the project, either from the GAC location or the Essential Studio<sup style="font-size:70%">&reg;</sup> WinForms installed location. It can also migrate the projects that contain the old versions of the Syncfusion<sup style="font-size:70%">&reg;</sup> assembly reference to newer or specific versions of the Syncfusion<sup style="font-size:70%">&reg;</sup> assembly reference. It supports Microsoft Visual Studio 2013 or higher. This Visual Studio extension is included from the Essential Studio<sup style="font-size:70%">&reg;</sup> 2013 Volume 3 release.

N> This Reference Manager can be applied to a project for Syncfusion<sup style="font-size:70%">&reg;</sup> assembly versions 10.4.0.71 and later.

Follow the given steps to add the Syncfusion<sup style="font-size:70%">&reg;</sup> references in Visual Studio:

> Before using the Syncfusion<sup style="font-size:70%">&reg;</sup> WinForms Reference Manager, check whether the **WinForms Extensions - Syncfusion<sup style="font-size:70%">&reg;</sup>** is installed or not in the Visual Studio Extension Manager by clicking on Tools -> Extensions and Updates -> Installed for Visual Studio 2017 or lower, and for Visual Studio 2019 or higher by clicking on Extensions -> Manage Extensions -> Installed. If this extension is not installed, please install the extension by following the steps from the [download and installation](https://help.Syncfusion.com/windowsforms/visual-studio-integration/vs2019-extensions/download-and-installation/) help topic.

1. Open a new or existing **WinForms** application.

2. To open the Syncfusion<sup style="font-size:70%">&reg;</sup> Reference Manager Wizard, follow either one of the options below:

   **Option 1:**  
   Click **Syncfusion<sup style="font-size:70%">&reg;</sup> Menu** and choose **Essential Studio<sup style="font-size:70%">&reg;</sup> for WinForms > Add References…** or any other Form in **Visual Studio**.

   ![Syncfusion Reference Manager via Syncfusion Menu](Syncfusion-Reference-Manger_images/Syncfusion_Menu_AddReference.png)

   N> From Visual Studio 2019, Syncfusion<sup style="font-size:70%">&reg;</sup> menu is available under Extensions in Visual Studio menu.

   **Option 2:**  
   Right-click the selected project file from Solution Explorer, then select **Syncfusion<sup style="font-size:70%">&reg;</sup> Reference Manager…** from **Context Menu**. The following screenshot shows this option in Visual Studio.   

   ![Syncfusion Reference Manager add-in](Syncfusion-Reference-Manger_images/Syncfusion-Reference-Manger-img1.png)

3. The Syncfusion<sup style="font-size:70%">&reg;</sup> Reference Manager Wizard contains the list of Syncfusion<sup style="font-size:70%">&reg;</sup> WinForms controls that are loaded.

   ![Syncfusion Reference Manger Wizard](Syncfusion-Reference-Manger_images/Syncfusion-Reference-Manger-img2.png)

   **Platform Selection:** If you launch the Syncfusion<sup style="font-size:70%">&reg;</sup> Reference Manager from a Console/Class Library project, the Platform selection option will appear as an option in the Syncfusion<sup style="font-size:70%">&reg;</sup> Reference Manager. Choose the required platform. 

   ![Platform selection option in Syncfusion Reference Manger](Syncfusion-Reference-Manger_images/Syncfusion-Reference-Manger-img3.png)

   **Assembly From:** Choose the assembly location, either from NuGet packages, the build installed location, or by using the GAC location.

   N> The installed location and GAC option will be available only when the Syncfusion<sup style="font-size:70%">&reg;</sup> Essential Studio<sup style="font-size:70%">&reg;</sup> WinForms setup has been installed.

   ![Assembly location option in Syncfusion Reference Manger](Syncfusion-Reference-Manger_images/Syncfusion-Reference-Manger-img4.png)

   N> The GAC option will not be available if you have selected a WinForms (.NET 10.0, .NET 9.0, .NET 8.0, .NET 7.0, and .NET 6.0) application in Visual Studio.

   **Version:** Choose the build version to add the corresponding version assemblies to the project.

   ![Assembly location option in Syncfusion Reference Manger](Syncfusion-Reference-Manger_images/Syncfusion-Reference-Manger1-img4.png)

   
  

4. Choose the required controls that you want to include in the project. Then, click **Done** to add the required assemblies for the selected controls into the project. The following screenshot shows the list of required assemblies for the selected controls to be added.

   ![Syncfusion Reference Manager new assemblies add information dialog](Syncfusion-Reference-Manger_images/Syncfusion-Reference-Manger-img5.png)

5. Click **OK**. The listed Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies are added to the project. Then, it notifies “Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies have been added successfully” in the Visual Studio status bar.

   ![Syncfusion Reference Manager success status in Visual Studio status bar](Syncfusion-Reference-Manger_images/Syncfusion-Reference-Manger-img6.png)

6. Then, the Syncfusion<sup style="font-size:70%">&reg;</sup> licensing registration required message box will be shown if you installed the trial setup or NuGet packages, since Syncfusion<sup style="font-size:70%">&reg;</sup> introduced the licensing system from the 2018 Volume 2 (v16.2.0.41) Essential Studio<sup style="font-size:70%">&reg;</sup> release. Navigate to the  [help topic](https://help.Syncfusion.com/common/essential-studio/licensing/license-key#how-to-generate-Syncfusion-license-key), which is shown in the licensing message box, to generate and register the Syncfusion<sup style="font-size:70%">&reg;</sup> license key in your project. Refer to this [blog](https://blog.Syncfusion.com/post/Whats-New-in-2018-Volume-2-Licensing-Changes-in-the-1620x-Version-of-Essential-Studio.aspx) post to understand the licensing changes introduced in Essential Studio<sup style="font-size:70%">&reg;</sup>.

   ![Syncfusion license registration required information dialog in Syncfusion Reference Manager](Syncfusion-Reference-Manger_images/Syncfusion-Reference-Manger-img7.png)

N>  Syncfusion<sup style="font-size:70%">&reg;</sup> provides Reference Manager support for specific .NET Frameworks, which are shipped (assemblies) in the Syncfusion<sup style="font-size:70%">&reg;</sup> Essential Studio<sup style="font-size:70%">&reg;</sup> setup. So, if you try to add Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies to the project and the project framework is not supported with the selected Syncfusion<sup style="font-size:70%">&reg;</sup> version assemblies, the dialog appears along with the **“Current build v{version} is not supported this framework v{Framework Version}”** message.






