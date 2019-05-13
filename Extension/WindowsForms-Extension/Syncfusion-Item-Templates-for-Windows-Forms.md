---
layout: post
title: Syncfusion Item Templates for Windows Forms | Extension | Syncfusion
description: Syncfusion Item Templates provides to add the predefined forms with Syncfusion component in Windows Forms application.
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Syncfusion Item Templates for Windows Forms

The Syncfusion Item Templates Add new item feature provides support to Windows Forms platform. 

I> The Syncfusion Windows Forms item templates are available from v13.1.0.21.

## Using Syncfusion Item Template Gallery

Follow the given steps to add the Syncfusion item in Visual Studio:

1. Open a new or existing Windows Forms application.
2. Right-click on the Windows Forms Project from the Solution Explorer. Select the Add Syncfusion Item  New Item... option. Refer to the following screenshot for more information.

   ![Syncfusion Item Template add-in](Item-Template-images\Syncfusion-Item-Template-Gallery-1.png)

3. Now, the Syncfusion Item Template Gallery window will open.

   ![Syncfusion Item Template wizard](Item-Template-images\Syncfusion-Item-Template-Gallery-2.png)
   
4. Select the required assembly location, version, and themes or Form from the Syncfusion Item Template Gallery. 

   ![Select the required themes or Form from the Syncfusion Item Template Wizard](Item-Template-images\Syncfusion-Item-Template-Gallery-3.png)

   **Assembly From:** Choose the assembly location, from where the assembly is added to the project.

   ![Select required Assembly Location in Syncfusion Item Template Wizard](Item-Template-images\Syncfusion-Item-Template-Gallery-7.png)

   N> Installed location and GAC option will be available only when the Syncfusion Essential Windows Forms setup has been installed. You can use NuGet option without installing the Syncfusion Essential Windows Forms setup. If you add the Syncfusion item files in .NET Core Windows Forms application, GAC option will not be listed in the Assembly From option.

   **Version:** Choose the build version to add the corresponding version assemblies to the project.

   ![Select required Essential Studio version in Syncfusion Item Template Wizard](Item-Template-images\Syncfusion-Item-Template-Gallery-4.png)

   N> Version option will be available only when you install the Syncfusion Essential Windows Forms setup and choose the assembly location as Installed Location or GAC.

   **Template Gallery:** This part contains a set of Syncfusion Item Templates, and you can choose the Item Templates as required.
   
   When Add button is clicked, then the selected item template is added to the project.

   ![Selected Item Template](Item-Template-images\Syncfusion-Item-Template-Gallery-5.png)

5. Then, the Syncfusion licensing registration required message box will be shown, if you installed the trial setup or NuGet packages since Syncfusion introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio release. Navigate to the  [help topic](https://help.syncfusion.com/common/essential-studio/licensing/license-key#how-to-generate-syncfusion-license-key), which is shown in the licensing message box to generate and register the Syncfusion license key to your project. Refer to this [blog](https://blog.syncfusion.com/post/Whats-New-in-2018-Volume-2-Licensing-Changes-in-the-1620x-Version-of-Essential-Studio.aspx) post to learn more about the licensing changes introduced in Essential Studio.

   ![Syncfusion license registration required information dialog in Syncfusion Item Template](Item-Template-images\Syncfusion-Item-Template-Gallery-6.png)

## Using Visual Studio Add new Item

Syncfusion Project Template can also be added from the Visual Studio Item Template.

1. To create a Syncfusion Windows Forms item template, follow either one of the options below:
   
   **Option 1:**  
   Click **Syncfusion Menu** and choose **Essential Studio for WinForms > Add Office2010Form...** or any other Form in **Visual Studio**.

   ![Syncfusion Project Template can be also add from the Visual Studio Item Template via Syncfusion Menu](Item-Template-images\Syncfusion_Menu_ItemTemplate.png)

   N> In Visual Studio 2019, Syncfusion menu available under Extension in Visual Studio menu.

   **Option 2:**
   Right-click the Windows Forms Project, select **Add > New Item**, and then navigate to **Visual C# Items or VB Items > Syncfusion > Windows**. Refer to the following screenshot for more information.
   
   ![Syncfusion Project Template can be also add from the Visual Studio Item Template](Item-Template-images\Syncfusion-Add-New-Item-1.png)

2. The Syncfusion Item Templates are available under the Syncfusion tab. It is available for both C# Items and VB Items. 

   ![Select required Item Template from Visual Studio Item Template Wizard](Item-Template-images\Syncfusion-Add-New-Item-2.png)

3. Now the selected template is added to the project along with Syncfusion references.

   ![Selected Syncfusion Item Template added to the project with Forms](Item-Template-images\Syncfusion-Add-New-Item-3.png)

   ![Selected Syncfusion Item Template required reference assemblies](Item-Template-images\Syncfusion-Add-New-Item-4.png)

4. Then, Syncfusion licensing registration required message box will be shown as follow, if you are installed the trial setup or NuGet packages since Syncfusion introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio release. Please navigate to the [help topic](https://help.syncfusion.com/common/essential-studio/licensing/license-key#how-to-generate-syncfusion-license-key) which is shown in the licensing message box to generate and register the Syncfusion license key to your project. Refer to this [blog](https://blog.syncfusion.com/post/Whats-New-in-2018-Volume-2-Licensing-Changes-in-the-1620x-Version-of-Essential-Studio.aspx) post for understanding the licensing changes introduced in Essential Studio.

   ![Syncfusion license registration required information dialog in Windows Forms project](Item-Template-images\Syncfusion-Item-Template-Gallery-6.png)
