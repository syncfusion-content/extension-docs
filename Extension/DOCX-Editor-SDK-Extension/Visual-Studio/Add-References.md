---
layout: post
title: Add a Syncfusion® DOCX Editor SDK References| WPF | Syncfusion
description: Syncfusion® DOCX Editor SDK Reference Manger is add-in to add the Syncfusion references into WPF application
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Add Syncfusion® DOCX Editor SDK Reference for WPF Application

Syncfusion® DOCX Editor SDK Reference Manager is an Add-In for WPF application. It adds the Syncfusion<sup style="font-size:70%">&reg;</sup> assembly reference to the project, either from the GAC location or Essential Studio<sup style="font-size:70%">&reg;</sup> installed location. It can also migrate the projects that contain the old versions of the Syncfusion<sup style="font-size:70%">&reg;</sup> assembly reference to newer or specific versions of the Syncfusion<sup style="font-size:70%">&reg;</sup> assembly reference.

N> This Syncfusion® DOCX Editor SDK Reference Manager can be applied to a project for Syncfusion<sup style="font-size:70%">&reg;</sup> assembly versions 10.4.0.71 and later.

Follow the given steps to add the Syncfusion® DOCX Editor SDK Reference Manager in Visual Studio:

> Before use the Syncfusion® DOCX Editor SDK Reference Manager, check whether the **Syncfusion® DOCX Editor SDK Extensions - Syncfusion<sup style="font-size:70%">&reg;</sup>** installed or not in Visual Studio Extension Manager by clicking on the Tools -> Extensions and Updates -> Installed for Visual Studio 2017 or lower and for Visual Studio 2019 by clicking on the Extensions -> Manage Extensions -> Installed.If this extension not installed, please install the extension by follow the steps from the [download and installation](https://help.Syncfusion.com/windowsforms/visual-studio-integration/vs2019-extensions/download-and-installation/) help topic.

1. Open a new or existing **WPF** application.

2. To open Syncfusion® DOCX Editor SDK Reference Manager Wizard, follow either one of the options below:

   **Option 1:**  
   Click **Syncfusion<sup style="font-size:70%">&reg;</sup> Menu** and choose **Essential Studio<sup style="font-size:70%">&reg;</sup> for Syncfusion® DOCX Editor SDK > Add Syncfusion® DOCX Editor SDK Reference Manager…**.

   ![Syncfusion® DOCX Editor SDK Reference Manager via Syncfusion Menu](images/Syncfusion_Menu_AddReference.png)

   N> From Visual Studio 2019, Syncfusion<sup style="font-size:70%">&reg;</sup> menu is available under Extensions in Visual Studio menu.

   **Option 2:**  
   Right-click the selected WPF project file from Solution Explorer, then select **Syncfusion® DOCX Editor SDK Reference Manager…** from **Context Menu**. The following screenshot shows this option in Visual Studio.   

   ![Syncfusion® DOCX Editor SDK Reference Manager add-in](images/Syncfusion-Reference-Manger-img1.png)

3. The Syncfusion® DOCX Editor SDK Reference Manager Wizard will be loaded.

   ![DOCX Editor SDK Reference Manger Wizard](images/Syncfusion-Reference-Manger-img2.png)

   **Choose Theme:** Choose the required Theme options which is enabled only for WPF application from the dropdown.

   ![Theme option in Syncfusion DOCX Editor SDK Reference Manger](images/Syncfusion-Reference-Manger-img3.png)

   **Assembly From:** Choose the assembly location, either from NuGet packages, the build installed location, or by using the GAC location.

   N> The installed location and GAC option will be available only when the Syncfusion<sup style="font-size:70%">&reg;</sup> WindowsForm or WPF build has been installed.

   ![Assembly location option in Syncfusion DOCX Editor SDK Reference Manger](images/Syncfusion-Reference-Manger-img4.png)

   N> The GAC option will not be available if you have selected WPF (.NET 8.0, .NET 7.0, and .NET 6.0) application in Visual Studio 2022.

   **Version:** Choose the build version to add the corresponding version assemblies to the project.

   ![Assembly location option in Syncfusion DOCX Editor SDK Reference Manger](images/Syncfusion-Reference-Manger1-img4.png)


4. click Done to add the required assemblies for the selected controls into the project. The following screenshot shows the list of required assemblies for the selected controls to be added.

   ![Syncfusion® DOCX Editor SDK Reference Manager new assemblies add information dialog](images/Syncfusion-Reference-Manger-img6.png)

5. Click **OK**. The listed Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies are added to project. Then it notifies “Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies have been added successfully” in Visual Studio status bar.

6. Then, Syncfusion<sup style="font-size:70%">&reg;</sup> licensing registration required message box will be shown, if you installed the trial setup or NuGet packages since Syncfusion<sup style="font-size:70%">&reg;</sup> introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio<sup style="font-size:70%">&reg;</sup> release. Navigate to the  [help topic](https://help.syncfusion.com/common/essential-studio/licensing/overview#how-to-generate-syncfusion-license-key), which is shown in the licensing message box to generate and register the Syncfusion<sup style="font-size:70%">&reg;</sup> license key to your project. Refer to this [blog](https://blog.Syncfusion.com/post/Whats-New-in-2018-Volume-2-Licensing-Changes-in-the-1620x-Version-of-Essential-Studio.aspx) post for understanding the licensing changes introduced in Essential Studio<sup style="font-size:70%">&reg;</sup>.

   ![Syncfusion license registration required information dialog in Syncfusion® DOCX Editor SDK Reference Manager](images/Syncfusion-Reference-Manger-img7.png)

N>  Syncfusion<sup style="font-size:70%">&reg;</sup> provides Syncfusion® DOCX Editor SDK Reference Manager support for specific .NET Framework, which is shipped (assemblies) in Syncfusion<sup style="font-size:70%">&reg;</sup> Essential Studio<sup style="font-size:70%">&reg;</sup> setup. So, if you try to add Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies in the project and project framework is not supported with selected Syncfusion<sup style="font-size:70%">&reg;</sup> version assemblies, the dialog appears along with **“Current build v{version} is not supported this framework v{Framework Version}”** message.






