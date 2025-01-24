---
layout: post
title: Project Migration | ASP.NET Core (Essential JS 1) | Syncfusion
description: Project Migration is a add-in that allows you to migrate existing Syncfusion ASP.NET Core Web Application from one Essential Studio version to another version
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Syncfusion<sup style="font-size:70%">&reg;</sup> Project Migration for ASP.NET Core Web Application

Syncfusion<sup style="font-size:70%">&reg;</sup> Project Migration is a Visual Studio add-in that allows you to migrate the existing Syncfusion<sup style="font-size:70%">&reg;</sup> ASP.NET Core Web Application from one Essential Studio<sup style="font-size:70%">&reg;</sup> version to another version.

I> The Syncfusion<sup style="font-size:70%">&reg;</sup> ASP.NET Core Web Application Project Migration utility is available from v15.2.0.40.

## Migrate Syncfusion<sup style="font-size:70%">&reg;</sup> Project 

The following steps help you to migrate your existing Syncfusion<sup style="font-size:70%">&reg;</sup> ASP.NET Core Web Application. 

> Before use, the Syncfusion<sup style="font-size:70%">&reg;</sup> ASP.NET Core (Essential<sup style="font-size:70%">&reg;</sup> JS 1) Project Migration, check whether the **Syncfusion<sup style="font-size:70%">&reg;</sup> Essential<sup style="font-size:70%">&reg;</sup> JS1 AspNet Core VSExtensions** installed or not in Visual Studio Extension Manager by clicking on the Tools -> Extensions and Updates -> Installed for Visual Studio 2017 or lower and for Visual Studio 2019 by clicking on the Extensions -> Manage Extensions -> Installed. Also, check whether the corresponding Essential Studio<sup style="font-size:70%">&reg;</sup> version build installed or not. If the Essential Studio version<sup style="font-size:70%">&reg;</sup> is not same for both the Extension and build, then the Project Migration will not be shown.

1. To open Migration Wizard, follow either one of the options below: 

   **Option 1:**  
   Click **Syncfusion<sup style="font-size:70%">&reg;</sup> Menu** and choose **Essential Studio<sup style="font-size:70%">&reg;</sup> for ASP.NET Core (EJ1) > Migrate Project…** in **Visual Studio**.
   
   ![Syncfusion<sup style="font-size:70%">&reg;</sup> Essential<sup style="font-size:70%">&reg;</sup> JS 1 ASP.NET Core Project Migration via Syncfusion<sup style="font-size:70%">&reg;</sup> menu](Project-Migration_images/Syncfusion_Menu_Project_Migration.png)

   N> In Visual Studio 2019, Syncfusion<sup style="font-size:70%">&reg;</sup> menu available under Extension in Visual Studio menu.
   
   **Option 2:**  
   Right-click the **Syncfusion<sup style="font-size:70%">&reg;</sup> ASP.NET Core Web Application** from Solution Explorer and select **Syncfusion<sup style="font-size:70%">&reg;</sup> Essential<sup style="font-size:70%">&reg;</sup> JS 1**. Choose **Migrate the Essential<sup style="font-size:70%">&reg;</sup> JS 1 Project to Another Version...**

   ![Syncfusion<sup style="font-size:70%">&reg;</sup> Essential<sup style="font-size:70%">&reg;</sup> JS 1 ASP.NET Core Project Migration add-in](Project-Migration_images/Project-Migration_img1.png)

2. The **Project Migration** window appears. You can choose the required Essential Studio<sup style="font-size:70%">&reg;</sup> version that is installed in the machine. 

   ![Syncfusion<sup style="font-size:70%">&reg;</sup> Essential<sup style="font-size:70%">&reg;</sup> JS 1 ASP.NET Core Project Migration window](Project-Migration_images/Project-Migration-img2.jpeg)

3. The **Project Migration** window allows you to configure the following options:

   i. **Essential Studio<sup style="font-size:70%">&reg;</sup> Version:** Select any version from the list of installed versions.
   
   ii. **Assets From:** Load the Syncfusion<sup style="font-size:70%">&reg;</sup> assets to ASP.NET Core Project, either Bower, CDN or Installed Location.
   
4. Click the Migrate Button. The **Project Backup** dialog will be opened. If click Yes it will backup the current project before migrate the Syncfusion<sup style="font-size:70%">&reg;</sup> project. If click No it will migrate the project to required Syncfusion<sup style="font-size:70%">&reg;</sup> version without backup
   
   ![Syncfusion<sup style="font-size:70%">&reg;</sup> Essential<sup style="font-size:70%">&reg;</sup> JS 1 ASP.NET Core Project Migration backup dialog](Project-Migration_images/Project-Migration-img3.jpeg)
      
5. The Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet/Bower Packages, Scripts and CSS are updated to the corresponding version in the project.

6. If you installed the trial setup or NuGet packages from nuget.org you have to register the Syncfusion<sup style="font-size:70%">&reg;</sup> license key to your project since Syncfusion<sup style="font-size:70%">&reg;</sup> introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio<sup style="font-size:70%">&reg;</sup> release. Navigate to the [help topic](https://help.syncfusion.com/common/essential-studio/licensing/license-key#how-to-generate-syncfusion-license-key) to generate and register the Syncfusion<sup style="font-size:70%">&reg;</sup> license key to your project. Refer to this [blog](https://www.syncfusion.com/blogs/post/whats-new-in-2018-volume-2.aspx) post for understanding the licensing changes introduced in Essential Studio<sup style="font-size:70%">&reg;</sup>.