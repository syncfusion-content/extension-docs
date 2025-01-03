---
layout: post
title: Add Reference Manger | Extension | Syncfusion
description: Learn here all about how to add a syncfusion Essential  references via reference manger in Extenion, it's elements and more.
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Add a Syncfusion<sup style="font-size:70%">&reg;</sup> References via Syncfusion<sup style="font-size:70%">&reg;</sup> Reference Manger

The Add-In launches a pop-up window that contains the list of Syncfusion<sup style="font-size:70%">&reg;</sup> controls that are loaded, based on the platform of the project. If it is a WPF project, all the Syncfusion<sup style="font-size:70%">&reg;</sup> WPF controls are loaded.

To add the assemblies:

1. Select the Syncfusion<sup style="font-size:70%">&reg;</sup> Reference Manager either in the WPF, Windows Forms/Console/Class Library or Silverlight Project.
2. The Syncfusion<sup style="font-size:70%">&reg;</sup> Reference Manager dialog is displayed as shown in the following screenshot.

   ![Syncfusion Reference Manger Wizard](Add-a-Syncfusion-References-via-Syncfusion-Reference-Manger_images/Add-a-Syncfusion-References-via-Syncfusion-Reference-Manger-img1.png)

3. If launched the Syncfusion<sup style="font-size:70%">&reg;</sup> Reference Manager from Console/Class Library project, Platform selection option will be appeared as option in Syncfusion<sup style="font-size:70%">&reg;</sup> Reference Manager. Choose the required platform based on your need. 

    ![Platform selection option in Syncfusion Reference Manger](Add-a-Syncfusion-References-via-Syncfusion-Reference-Manger_images/Add-a-Syncfusion-References-via-Syncfusion-Reference-Manger-img6.png)

    N> Platform selection option will be appeared only if Essential Studio<sup style="font-size:70%">&reg;</sup> for Enterprise Edition with the platforms WPF and Windows Forms has been installed or both Essential Studio<sup style="font-size:70%">&reg;</sup> for WPF and Essential Studio<sup style="font-size:70%">&reg;</sup> for Windows Forms has been installed.

4. If launched the Syncfusion<sup style="font-size:70%">&reg;</sup> Reference Manager from WPF project or select the WPF platform from platform selection option, **Themes** option will be appeared as option in Syncfusion<sup style="font-size:70%">&reg;</sup> Reference Manger. Choose the required themes based on your need. Refer the below link to know more about built in themes and its available assemblies.

    [https://help.syncfusion.com/wpf/themes/skin-manager](https://help.syncfusion.com/wpf/themes/skin-manager)

    ![Themes selection option in Syncfusion Reference Manger](Add-a-Syncfusion-References-via-Syncfusion-Reference-Manger_images/Add-a-Syncfusion-References-via-Syncfusion-Reference-Manger-img4.png)

    N> Themes option will be enabled only if selected SfSkinManager supported controls.

    ![Tooltip information for Syncfusion Reference Manager themes option](Add-a-Syncfusion-References-via-Syncfusion-Reference-Manger_images/Add-a-Syncfusion-References-via-Syncfusion-Reference-Manger-img5.png)

5. Reference assemblies
   * You can add Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies from NuGet packages, the build installed location, or by using the GAC location. This option determines the location of the assemblies that are referenced in the project.

   N> The installed location and GAC option will be available only when the Syncfusion<sup style="font-size:70%">&reg;</sup> Essential Studio<sup style="font-size:70%">&reg;</sup> setup has been installed.

   ![Options for assembly location in Syncfusion Reference Manager](Add-a-Syncfusion-References-via-Syncfusion-Reference-Manger_images/Add-a-Syncfusion-References-via-Syncfusion-Reference-Manger-img8.png)

    N> The GAC option will not be available if you have selected a .NET 7.0 or .NET 6.0 application in Visual Studio 2022.

   * Select the Syncfusion<sup style="font-size:70%">&reg;</sup> Essential Studio<sup style="font-size:70%">&reg;</sup> versions that were previously installed on your machine.This option determines the assembly version that is referenced in the project.

   ![Versions for assemblies in Syncfusion Reference Manager](Add-a-Syncfusion-References-via-Syncfusion-Reference-Manger_images/Add-a-Syncfusion-References-via-Syncfusion-Reference-Manger-img9.png)

   * Choose the required controls that you want include in project
6. Click Done to add the required assemblies for the selected controls into the project. The   following screenshot shows the list of required assemblies for 
   the selected controls to be added.

   ![Syncfusion Reference Manager new assemblies add information dialog](Add-a-Syncfusion-References-via-Syncfusion-Reference-Manger_images/Add-a-Syncfusion-References-via-Syncfusion-Reference-Manger-img2.png)

7. Click OK. The listed Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies are added to project. Then it notifies “Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies have been added successfully” in Visual Studio status bar.

   ![Syncfusion Reference Manager success status in Visual Studio status bar](Add-a-Syncfusion-References-via-Syncfusion-Reference-Manger_images/Add-a-Syncfusion-References-via-Syncfusion-Reference-Manger-img3.png)

8. Then, Syncfusion<sup style="font-size:70%">&reg;</sup> licensing registration required message box will be shown as follow, if you are installed the trial setup or NuGet packages since Syncfusion<sup style="font-size:70%">&reg;</sup> introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio<sup style="font-size:70%">&reg;</sup> release. Please navigate to the [help topic](https://help.syncfusion.com/common/essential-studio/licensing/overview#how-to-generate-syncfusion-license-key) which is shown in the licensing message box to generate and register the Syncfusion<sup style="font-size:70%">&reg;</sup> license key to your project. Refer to this [blog](https://blog.syncfusion.com/post/Whats-New-in-2018-Volume-2-Licensing-Changes-in-the-1620x-Version-of-Essential-Studio.aspx) post for understanding the licensing changes introduced in Essential Studio<sup style="font-size:70%">&reg;</sup>.

   ![Syncfusion license registration required information dialog in Syncfusion Reference Manager](Add-a-Syncfusion-References-via-Syncfusion-Reference-Manger_images/Add-a-Syncfusion-References-via-Syncfusion-Reference-Manger-img7.png)

N> We are providing Syncfusion<sup style="font-size:70%">&reg;</sup> Reference Manager support for specific framework which is shipped (assemblies) in our Syncfusion<sup style="font-size:70%">&reg;</sup> Essential Studio<sup style="font-size:70%">&reg;</sup> setup. So, if we try to add Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies in project and project framework is not supported with selected Syncfusion<sup style="font-size:70%">&reg;</sup> version assemblies, the dialog will be appeared along with **“Current build v{version} is not supported this framework v{Framework Version}”** message.






