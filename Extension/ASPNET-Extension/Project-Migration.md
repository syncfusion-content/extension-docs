---
layout: post
title: Project Migration | ASP.NET Web Forms | Syncfusion
description: Project Migration is a add-in that allows you to migrate existing Syncfusion ASP.NET Web Forms project from one Essential Studio version to another version
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Syncfusion Project Migration

Syncfusion Project Migration is a Visual Studio add-in that allows you to migrate the existing Syncfusion ASP.NET project from one Essential Studio version to another version.

I> The Syncfusion ASP.NET Web Application Project Migration utility is available from v13.1.0.30. 

## Migrate Syncfusion Project 

The following steps help you to migrate your existing Syncfusion ASP.NET application. 

1. To open Migration Wizard, follow either one of the options below: 

   **Option 1:**   
   Click **Syncfusion Menu** and choose **Essential Studio for ASP.NET (EJ1) > Migrate Project…** in **Visual Studio**.

   ![Syncfusion Essential JS 1 ASP.NET Web Forms Project Migration via Syncfusion menu](Project-Migration_images/Syncfusion_Menu_Project_Migration1.png)

   N> In Visual Studio 2019, Syncfusion menu available under Extension in Visual Studio menu.

   **Option 2:**  
   Right-click the **Syncfusion ASP.NET Application** from Solution Explorer and select **Syncfusion Essential JS 1**. Choose **Migrate the Essential JS 1 Project to Another version…**

   ![Syncfusion Essential JS 1 ASP.NET Web Forms Project Migration add-in](Project-Migration_images/Project-Migration_img1.png)

2. The **Project Migration** window appears. You can choose the required Essential Studio version that is installed in the machine. 

   ![Syncfusion Essential JS 1 ASP.NET Web Forms Project Migration wizard](Project-Migration_images/Project-Migration-img2.jpeg)

3. The **Project Migration** window allows you to configure the following options:

   i. **Essential Studio Version:** Select any version from the list of installed versions.
   
   ii. **Assemblies From:** Choose the assembly location from where it is going to be added to the project.
   
4. Click the Migrate Button. The **Project Backup** dialog will be opened. If click Yes it will backup the current project before migrate the Syncfusion project. If click No it will migrate the project to required Syncfusion version without backup
   
   ![Syncfusion Essential JS 1 ASP.NET Web Forms Project Migration backup dialog](Project-Migration_images/Project-Migration-img3.jpeg)
   
   
5. The Syncfusion Reference Assemblies, Scripts and CSS are updated to the corresponding version in the project.

