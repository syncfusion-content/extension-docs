---
layout: post
title: Add References| Wpf | Syncfusion
description: Syncfusion Reference Manger extension is add-in to add the Syncfusion references into the WinForms application
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Add Reference for WPF

Syncfusion<sup style="font-size:70%">&reg;</sup> Reference Manager is the Visual Studio Add-In for WPF platform. It adds the Syncfusion<sup style="font-size:70%">&reg;</sup> assembly reference to the project, either from the GAC location or from Essential Studio<sup style="font-size:70%">&reg;</sup> installed location or from NuGet packages. It can also migrate the projects that contain the old versions of the Syncfusion<sup style="font-size:70%">&reg;</sup> assembly reference to newer or specific versions of the Syncfusion<sup style="font-size:70%">&reg;</sup> assembly reference. It supports Microsoft Visual Studio 2013 or higher. This Visual Studio extension is included from Essential Studio<sup style="font-size:70%">&reg;</sup> 2013 Volume 3 release.

N> This Reference Manager can be applied to a project for Syncfusion<sup style="font-size:70%">&reg;</sup> assembly versions 10.4.0.71 and later.

To add the Syncfusion<sup style="font-size:70%">&reg;</sup> assembly references in Visual Studio, follow the steps below:

> Check whether the **WPF Extensions - Syncfusion<sup style="font-size:70%">&reg;</sup>** are installed or not in Visual Studio Extension Manager by going to **Tools -> Extensions and Updates -> Installed** for Visual Studio 2017 or lower, and **Extensions -> Manage Extensions -> Installed** for Visual Studio 2019 by going to Extensions -> Manage Extensions -> Installed. If this extension not installed, please install the extension by follow the steps from the [download and installation](download-and-installation) help topic.

1. Open a new or existing **WPF** application.

2. To open Syncfusion<sup style="font-size:70%">&reg;</sup> Reference Manager Wizard, follow either one of the options below:

   **Option 1:**  
   Click **Syncfusion<sup style="font-size:70%">&reg;</sup> Menu** and choose **Essential Studio<sup style="font-size:70%">&reg;</sup> for WPF > Add References…** in **Visual Studio**.

   ![Syncfusion<sup style="font-size:70%">&reg;</sup> Reference Manager via Syncfusion<sup style="font-size:70%">&reg;</sup> Menu](Syncfusion-Reference-Manger_images/Syncfusion_Menu_AddReference.png)

   N> From Visual Studio 2019, Syncfusion<sup style="font-size:70%">&reg;</sup> menu is available under Extensions in Visual Studio menu.

   ![Syncfusion<sup style="font-size:70%">&reg;</sup> Reference Manager via Syncfusion<sup style="font-size:70%">&reg;</sup> Menu](Syncfusion-Reference-Manger_images/Syncfusion_Menu_AddReference_2019.png)

   **Option 2:**  

   Right-click the selected project file from Solution Explorer, then select **Syncfusion<sup style="font-size:70%">&reg;</sup> Reference Manager…** from **Context Menu**. The following screenshot shows this option in Visual Studio.   

   ![Syncfusion<sup style="font-size:70%">&reg;</sup> Reference Manager add-in](Syncfusion-Reference-Manger_images/Syncfusion-Reference-Manger-img1.png)

3. The Syncfusion<sup style="font-size:70%">&reg;</sup> Reference Manager Wizard displays a list of loaded Syncfusion<sup style="font-size:70%">&reg;</sup> WPF controls.

   ![Syncfusion<sup style="font-size:70%">&reg;</sup> Reference Manger Wizard](Syncfusion-Reference-Manger_images/Syncfusion-Reference-Manger-img2.png)

   **Platform Selection:** Platform selection option will appear as an option in Syncfusion<sup style="font-size:70%">&reg;</sup> Reference Manager if opened from a Console/Class Library project. Select the appropriate platform. 

   ![Platform selection option in Syncfusion<sup style="font-size:70%">&reg;</sup> Reference Manger](Syncfusion-Reference-Manger_images/Syncfusion-Reference-Manger-img3.png)

   N> The platform selection option will appear only if Essential Studio<sup style="font-size:70%">&reg;</sup> for Enterprise Edition with the platforms WPF and Windows Forms has been installed, or if both Essential Studio<sup style="font-size:70%">&reg;</sup> for WPF and WinForms has been installed.

   **Assembly From:** Choose the assembly location, either from NuGet packages, the build installed location, or by using the GAC location.

   N> The installed location and GAC option will be available only when the Syncfusion<sup style="font-size:70%">&reg;</sup> Essential Studio<sup style="font-size:70%">&reg;</sup> WPF setup has been installed.

   ![Assembly location option in Syncfusion<sup style="font-size:70%">&reg;</sup> Reference Manger](Syncfusion-Reference-Manger_images/Syncfusion-Reference-Manger-img4.png)


   N> The GAC option will not be available when you select the WPF (.NET 8.0, .NET 7.0, and.NET 6.0) application in Visual Studio 2022.

   **Version:** To add the corresponding version assemblies to the project, select the build version.

   ![Assembly location option in Syncfusion<sup style="font-size:70%">&reg;</sup> Reference Manger](Syncfusion-Reference-Manger_images/Syncfusion-Reference-Manger1-img4.png)


   **Themes Option:** Choose the necessary themes based on your requirements. To learn more about built-in themes and their available assembly, click the link below.

   [https://help.Syncfusion.com/wpf/themes/](https://help.Syncfusion.com/wpf/themes/)

   ![Themes selection option in Syncfusion<sup style="font-size:70%">&reg;</sup> Reference Manger](Syncfusion-Reference-Manger_images/Syncfusion-Reference-Manger-img5.png)

   N> Themes option will be enabled only if we selected theme supported controls.

   ![Themes selection option notification in Syncfusion<sup style="font-size:70%">&reg;</sup> Reference Manger](Syncfusion-Reference-Manger_images/Syncfusion-Reference-Manger-img6.png)


4. Select the required controls you want to add in your project. Then click ****Done** to add the project's required assemblies for the specified controls. The list of required assemblies for the selected controls to be added is shown in the screenshot below.

   ![Syncfusion<sup style="font-size:70%">&reg;</sup> Reference Manager new assemblies add information dialog](Syncfusion-Reference-Manger_images/Syncfusion-Reference-Manger-img7.png)

5. Click **OK**. The listed Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies are added to project. Then it notifies “Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies have been added successfully” in Visual Studio status bar.

   ![Syncfusion<sup style="font-size:70%">&reg;</sup> Reference Manager success status in Visual Studio status bar](Syncfusion-Reference-Manger_images/Syncfusion-Reference-Manger-img8.png)

6. Then, Syncfusion<sup style="font-size:70%">&reg;</sup> licensing registration required message box will be shown if you installed the trial setup or NuGet packages since Syncfusion<sup style="font-size:70%">&reg;</sup> introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio<sup style="font-size:70%">&reg;</sup> release. Navigate to the [help topic](https://help.Syncfusion.com/common/essential-studio/licensing/license-key#how-to-generate-Syncfusion-license-key), which is shown in the licensing message box to generate and register the Syncfusion<sup style="font-size:70%">&reg;</sup> license key to your project. Refer to this [blog](https://blog.Syncfusion.com/post/Whats-New-in-2018-Volume-2-Licensing-Changes-in-the-1620x-Version-of-Essential-Studio.aspx) post for understanding the licensing changes introduced in Essential Studio<sup style="font-size:70%">&reg;</sup>.

   ![Syncfusion<sup style="font-size:70%">&reg;</sup> license registration required information dialog in Syncfusion<sup style="font-size:70%">&reg;</sup> Reference Manager](Syncfusion-Reference-Manger_images/Syncfusion-Reference-Manger-img9.png)

N>  Reference Manager support is provided by Syncfusion<sup style="font-size:70%">&reg;</sup> for select versions of the.NET Framework that are included (as assemblies) in the Syncfusion<sup style="font-size:70%">&reg;</sup> Essential Studio<sup style="font-size:70%">&reg;</sup> installation. If you try to add Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies to a project and the project framework isn't compatible with the specified Syncfusion<sup style="font-size:70%">&reg;</sup> version assemblies, a dialogue box shows with the message "**Current build v{version} isn't compatible with this framework v{Framework} Version**".






