---
layout: post
title: Project Migration | ASP.NET MVC (Essential JS 1) | Syncfusion
description: Project Migration is a add-in that helps migrate existing Syncfusion Essential JS 1 ASP.NET MVC project from one Syncfusion version to another version
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# ASP.NET MVC Project Migration

Project Migration is a Visual Studio add-in that helps migrate the existing Syncfusion<sup style="font-size:70%">&reg;</sup> ASP.NET MVC (Web), Syncfusion<sup style="font-size:70%">&reg;</sup> ASP.NET MVC (Mobile) Or Syncfusion<sup style="font-size:70%">&reg;</sup> ASP.NET MVC (Classic) project from one Syncfusion<sup style="font-size:70%">&reg;</sup> version to another Syncfusion<sup style="font-size:70%">&reg;</sup> version.

Syncfusion<sup style="font-size:70%">&reg;</sup> ASP.NET MVC and ASP.NET MVC (Classic) Project Migration Utility is included here,

* Essential Studio<sup style="font-size:70%">&reg;</sup> for Enterprise Edition with the platforms ASP.NET MVC or ASP.NET MVC(Classic)
* Essential Studio<sup style="font-size:70%">&reg;</sup> for ASP.NET MVC
* Essential Studio<sup style="font-size:70%">&reg;</sup> for ASP.NET MVC (Classic)

I> This is not applicable from v.12.1.0.43 to v.13.1.0.30. The Syncfusion<sup style="font-size:70%">&reg;</sup> ASP.NET MVC and ASP.NET MVC (Classic) Project Migration Utilities are excluded from MVC Extension setup and integrated into Essential Studio<sup style="font-size:70%">&reg;</sup> ASP.NET MVC and ASP.NET MVC (Classic) platforms.

## ASP.NET MVC (Classic) Conversion\Migration:

By default, the Syncfusion<sup style="font-size:70%">&reg;</sup> ASP.NET MVC Extensions are configured in Visual Studio. When you want the ASP.NET MVC (Classic) extension, you can install it from the installed location.

Project Conversion and Migration (ASP.NET MVC(Classic):

Location: `{Drive}\Program Files (x86)\Syncfusion\Essential Studio\<Version>\Utilities\Extensions\ASP.NET MVC\Project Conversion`

For Example - VS2013: `C:\Program Files (x86)\Syncfusion\Essential Studio\13.2.0.18\Utilities\Extensions\ASP.NET MVC\Project Conversion\4.5.1\Syncfusion Web (Classic) Conversion and Migration.vsix`

## Migrate Syncfusion<sup style="font-size:70%">&reg;</sup> MVC Project

The following steps help you migrate from one version to another version of your existing Syncfusion<sup style="font-size:70%">&reg;</sup> ASP.NET MVC application.

> Before use, the Syncfusion<sup style="font-size:70%">&reg;</sup> ASP.NET MVC (Essential<sup style="font-size:70%">&reg;</sup> JS 1) Project Migration, check whether the **Syncfusion<sup style="font-size:70%">&reg;</sup> Essential<sup style="font-size:70%">&reg;</sup> JS1 AspNet MVC VSExtensions** installed or not in Visual Studio Extension Manager by clicking on the Tools -> Extensions and Updates -> Installed for Visual Studio 2017 or lower and for Visual Studio 2019 by clicking on the Extensions -> Manage Extensions -> Installed. Also, check whether the corresponding Essential Studio<sup style="font-size:70%">&reg;</sup> version build installed or not. If the Essential Studio<sup style="font-size:70%">&reg;</sup> version is not same for both the Extension and build, then the Project Migration will not be shown.

1. To open Migration Wizard, follow either one of the options below: 

   **Option 1:**  
   Click **Syncfusion<sup style="font-size:70%">&reg;</sup> Menu** and choose **Essential Studio<sup style="font-size:70%">&reg;</sup> for ASP.NET MVC (EJ1) > Migrate Project…** in **Visual Studio**.

   ![Syncfusion<sup style="font-size:70%">&reg;</sup> Essential<sup style="font-size:70%">&reg;</sup> JS 1 ASP.NET MVC Project Migration via Syncfusion<sup style="font-size:70%">&reg;</sup> menu](Migrate-Syncfusion-Project_images/SyncfusionMenu_ProjectMigration_img.png)

   N> In Visual Studio 2019, Syncfusion<sup style="font-size:70%">&reg;</sup> menu available under Extension in Visual Studio menu.

   **Option 2:**  
   Right-click the **Syncfusion<sup style="font-size:70%">&reg;</sup> ASP.NET MVC Application** from Solution Explorer and select **Syncfusion<sup style="font-size:70%">&reg;</sup> Essential<sup style="font-size:70%">&reg;</sup> JS 1**. Choose **Migrate the Essential<sup style="font-size:70%">&reg;</sup> JS 1 Project to Another Version...**

   ![Syncfusion<sup style="font-size:70%">&reg;</sup> Essential<sup style="font-size:70%">&reg;</sup> JS 1 ASP.NET MVC Project Migration add-in](Migrate-Syncfusion-Project_images/ProjectMigration_img.png)

2. The Project Migration window appears. You can choose the required Syncfusion<sup style="font-size:70%">&reg;</sup> version that is installed in the machine that is either Syncfusion<sup style="font-size:70%">&reg;</sup> ASP.NET MVC or Syncfusion<sup style="font-size:70%">&reg;</sup> ASP.NET MVC (Classic).

   ![Syncfusion<sup style="font-size:70%">&reg;</sup> Essential<sup style="font-size:70%">&reg;</sup> JS 1 ASP.NET MVC Project Migration wizard](Migrate-Syncfusion-Project_images/ProjectMigration-img2.jpeg)

3. The Project Migration window allows you to configure the following options:

   * Essential Studio<sup style="font-size:70%">&reg;</sup> Version: Select any version from the list of Installed Versions.
	  
   * Assemblies From: The option Assemblies from add the assembly to project from the following locations.
	  
	    1. Added From GAC - Refer the assemblies from the Global Assembly Cache
		2. Added from Installed Location - Refer the assemblies from the Syncfusion<sup style="font-size:70%">&reg;</sup> Installed locations.
        3. Add Referenced Assemblies to Solution - Copy and refer to the assemblies from project's solution file lib directory.  

4. Click the Migrate Button. The **Project Backup** dialog will be opened. If click Yes it will backup the current project before migrate the Syncfusion<sup style="font-size:70%">&reg;</sup> project. If click No it will migrate the project to required Syncfusion<sup style="font-size:70%">&reg;</sup> version without backup. 

     ![Syncfusion<sup style="font-size:70%">&reg;</sup> Essential<sup style="font-size:70%">&reg;</sup> JS 1 ASP.NET MVC Project Migration backup dialog](Migrate-Syncfusion-Project_images/ProjectMigration-img3.jpeg)
      
5. The Syncfusion<sup style="font-size:70%">&reg;</sup> Reference Assemblies, Scripts and CSS are updated to the corresponding version in the project.

6. If you installed the trial setup or NuGet packages from nuget.org you have to register the Syncfusion<sup style="font-size:70%">&reg;</sup> license key to your project since Syncfusion<sup style="font-size:70%">&reg;</sup> introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio<sup style="font-size:70%">&reg;</sup> release. Navigate to the [help topic](https://help.syncfusion.com/common/essential-studio/licensing/overview#how-to-generate-syncfusion-license-key) to generate and register the Syncfusion<sup style="font-size:70%">&reg;</sup> license key to your project. Refer to this [blog](https://www.syncfusion.com/blogs/post/whats-new-in-2018-volume-2.aspx) post for understanding the licensing changes introduced in Essential Studio<sup style="font-size:70%">&reg;</sup>.