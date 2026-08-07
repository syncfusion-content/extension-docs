---
layout: post
title: Add References| Wpf | Syncfusion
description: Syncfusion Reference Manger extension is add-in to add the Syncfusion references into the WinForms application
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Add Reference for WPF

Syncfusion<sup style="font-size:70%">&reg;</sup> Reference Manager is a Visual Studio add-in for the WPF platform. It adds the Syncfusion<sup style="font-size:70%">&reg;</sup> assembly reference to the project from the GAC location, the Essential Studio<sup style="font-size:70%">&reg;</sup> installed location, or NuGet packages. It can also migrate projects that contain older Syncfusion<sup style="font-size:70%">&reg;</sup> assembly references to a newer or specific version. It supports Microsoft Visual Studio 2013 or higher. This Visual Studio extension is included from the Essential Studio<sup style="font-size:70%">&reg;</sup> 2013 Volume 3 release.

N> This Reference Manager can be applied to a project for Syncfusion<sup style="font-size:70%">&reg;</sup> assembly versions 10.4.0.71 and later.

To add the Syncfusion<sup style="font-size:70%">&reg;</sup> assembly references in Visual Studio, follow the steps below:

> Check whether the **WPF Extensions - Syncfusion<sup style="font-size:70%">&reg;</sup>** are installed in the Visual Studio Extension Manager. In Visual Studio 2017 or lower, go to **Tools -> Extensions and Updates -> Installed**. In Visual Studio 2019 and later, go to **Extensions -> Manage Extensions -> Installed**. If this extension is not installed, follow the steps from the [download and installation](download-and-installation) help topic to install it.

1. Open a new or existing **WPF** application.

2. To open Syncfusion<sup style="font-size:70%">&reg;</sup> Reference Manager Wizard, follow either one of the options below:

   **Option 1:** From the **Syncfusion<sup style="font-size:70%">&reg;</sup> Menu**, choose **Essential Studio<sup style="font-size:70%">&reg;</sup> for WPF > Add References…**.

   ![Syncfusion Reference Manager via Syncfusion Menu](Syncfusion-Reference-Manger_images/Syncfusion_Menu_AddReference.png)

   N> From Visual Studio 2019, the Syncfusion<sup style="font-size:70%">&reg;</sup> menu is available under **Extensions** in the Visual Studio menu.

   ![Syncfusion Reference Manager via Syncfusion Menu](Syncfusion-Reference-Manger_images/Syncfusion_Menu_AddReference_2019.png)

   **Option 2:** Right-click the project in **Solution Explorer** and select **Syncfusion<sup style="font-size:70%">&reg;</sup> Reference Manager…** from the context menu. The following screenshot shows this option in Visual Studio.

   ![Syncfusion Reference Manager add-in](Syncfusion-Reference-Manger_images/Syncfusion-Reference-Manger-img1.png)

3. The Syncfusion<sup style="font-size:70%">&reg;</sup> Reference Manager Wizard displays a list of loaded Syncfusion<sup style="font-size:70%">&reg;</sup> WPF controls.

   ![Syncfusion Reference Manger Wizard](Syncfusion-Reference-Manger_images/Syncfusion-Reference-Manger-img2.png)

   **Platform Selection:** The Platform Selection option appears when the Syncfusion<sup style="font-size:70%">&reg;</sup> Reference Manager is opened from a Console or Class Library project. Select the appropriate platform.

   ![Platform selection option in Syncfusion Reference Manger](Syncfusion-Reference-Manger_images/Syncfusion-Reference-Manger-img3.png)

   N> The Platform Selection option appears only if Essential Studio<sup style="font-size:70%">&reg;</sup> for Enterprise Edition with the platforms WPF and Windows Forms has been installed, or if both Essential Studio<sup style="font-size:70%">&reg;</sup> for WPF and WinForms have been installed.

   **Assembly From:** Choose the assembly location: NuGet packages, installed location, or GAC location.

   N> The **Installed location** and **GAC** options are available only when the Syncfusion<sup style="font-size:70%">&reg;</sup> Essential Studio<sup style="font-size:70%">&reg;</sup> WPF setup has been installed.

   ![Assembly location option in Syncfusion Reference Manger](Syncfusion-Reference-Manger_images/Syncfusion-Reference-Manger-img4.png)


   N> The **GAC** option is not available when you select a WPF (.NET 10.0, .NET 9.0, .NET 8.0, .NET 7.0, and .NET 6.0) application in Visual Studio 2022 and later.

   **Version:** To add the corresponding version assemblies to the project, select the build version.

   ![Assembly location option in Syncfusion Reference Manger](Syncfusion-Reference-Manger_images/Syncfusion-Reference-Manger1-img4.png)


   **Themes Option:** Choose the necessary themes based on your requirements. To learn more about built-in themes and their available assemblies, click the link below.

   [https://help.Syncfusion.com/wpf/themes/](https://help.Syncfusion.com/wpf/themes/)

   ![Themes selection option in Syncfusion Reference Manger](Syncfusion-Reference-Manger_images/Syncfusion-Reference-Manger-img5.png)

   N> The **Themes** option is enabled only if you select theme-supported controls.

   ![Themes selection option notification in Syncfusion Reference Manger](Syncfusion-Reference-Manger_images/Syncfusion-Reference-Manger-img6.png)


4. Select the required controls to add to your project, then click **Done** to add the required assemblies for the specified controls. The list of required assemblies for the selected controls to be added is shown in the screenshot below.

   ![Syncfusion Reference Manager new assemblies add information dialog](Syncfusion-Reference-Manger_images/Syncfusion-Reference-Manger-img7.png)

5. Click **OK**. The listed Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies are added to the project. A status bar message in Visual Studio confirms: "Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies have been added successfully".

   ![Syncfusion Reference Manager success status in Visual Studio status bar](Syncfusion-Reference-Manger_images/Syncfusion-Reference-Manger-img8.png)

6. If you installed the trial setup or NuGet packages, the Syncfusion<sup style="font-size:70%">&reg;</sup> license registration message box is displayed, since Syncfusion<sup style="font-size:70%">&reg;</sup> introduced the licensing system in 2018 Volume 2 (v16.2.0.41) of the Essential Studio<sup style="font-size:70%">&reg;</sup> release. Navigate to the [help topic](https://help.Syncfusion.com/common/essential-studio/licensing/license-key#how-to-generate-Syncfusion-license-key) shown in the licensing message box to generate and register the Syncfusion<sup style="font-size:70%">&reg;</sup> license key for your project. Refer to this [blog](https://blog.Syncfusion.com/post/Whats-New-in-2018-Volume-2-Licensing-Changes-in-the-1620x-Version-of-Essential-Studio.aspx) post to understand the licensing changes introduced in Essential Studio<sup style="font-size:70%">&reg;</sup>.

   ![Syncfusion license registration required information dialog in Syncfusion Reference Manager](Syncfusion-Reference-Manger_images/Syncfusion-Reference-Manger-img9.png)

N> Reference Manager support is provided by Syncfusion<sup style="font-size:70%">&reg;</sup> for select versions of the .NET Framework that are included (as assemblies) in the Syncfusion<sup style="font-size:70%">&reg;</sup> Essential Studio<sup style="font-size:70%">&reg;</sup> installation. If you add Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies to a project and the project framework is not compatible with the specified Syncfusion<sup style="font-size:70%">&reg;</sup> version assemblies, a dialog box appears with the message: **Current build v{version} isn't compatible with this framework v{Framework} Version**.






