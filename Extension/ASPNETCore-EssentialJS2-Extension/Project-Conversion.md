---
layout: post
title: Project Conversion | ASP.NET Core (Essential JS 2) | Syncfusion
description: Project Conversion is a add-in that converts ASP.NET Core application into a Syncfusion ASP.NET Core application by adding required Essential JS 2 components
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Syncfusion Project Conversion  

Syncfusion Project Conversion is a Visual Studio add-in that converts an existing ASP.NET Core application into a Syncfusion ASP.NET Core (Essential JS 2) Web application by adding the required assemblies and resource files

I> The Syncfusion ASP.NET Core (Essential JS 2) Web Application Project Conversion utility is available from v16.3.0.17. 

## Convert into Syncfusion ASP.NET Core (Essential JS 2) Web Application 

The following steps direct you to use the Syncfusion Project Conversion in the existing ASP.NET Core Web Application.

1. Open an existing Microsoft ASP.NET Core Web Application or create a new Microsoft ASP.NET Core Web Application. 

2. To open Project Conversion Wizard, follow either one of the options below:

   **Option 1:**   
   Click **Syncfusion Menu** and choose **Essential Studio for ASP.NET Core (EJ2) > Convert to Syncfusion ASP.NET Core Application…** in **Visual Studio**.

   ![Syncfusion Essential JS 2 ASP.NET Core Project Conversion add-in](Project-Conversion_images/Syncfusion_Menu_Project_Conversion.png)

   N> In Visual Studio 2019, Syncfusion menu available under Extension in Visual Studio menu.

   **Option 2:**                             
   Right-click the **Project** from Solution Explorer, select **Syncfusion Essential JS 2**, and choose the **Convert to Syncfusion ASP.NET Core (Essential JS 2) Application...** Refer to the following screenshot for more information.

   ![Syncfusion Essential JS 2 ASP.NET Core Project Conversion add-in](Project-Conversion_images/Project-Conversion-img1.jpg)

3. Project Conversion Wizard opens to configure the project.

   ![Syncfusion Essential JS 2 ASP.NET Core Project Conversion Wizard](Project-Conversion_images/Project-Conversion-img2.jpg)

   **Choose the assets from:**

   * **NPM** - Refer to the assets from NPM package manager. 

   * **CDN** - Refer to the assets from Syncfusion CDN links.

   * **Installed Location** - Refer to the assets from Syncfusion installed locations.    

   N> *Installed location option will be available only when the Syncfusion Essential JavaScript 2 setup has been installed*.   
   
   ![Choose the required assets need to add to the project](Project-Conversion_images/Project-Conversion-img3.jpg)
   
   **Choose the Theme:**
   
   Choose the required theme. The Theme Preview section shows the controls preview before convert into a Syncfusion project.
   
   ![Choose the required theme to apply on the project](Project-Conversion_images/Project-Conversion-img4.jpg)

   The **Project Backup** dialog will be opened. If click **Yes**, it will backup the current project before converting it to Syncfusion project. If click **No**, it will convert the project to Syncfusion project without backup.
    
   ![Syncfusion Essential JS 2 ASP.NET Core Project Backup dialog](Project-Conversion_images/Project-Conversion-img5.jpg)   

4. The required Syncfusion NuGet packages, Scripts and CSS are included in the ASP.NET Core Web Application. Refer to the following screenshots for more information.

   ![Syncfusion Essential JS 2 ASP.NET Core required NuGet packages](Project-Conversion_images/Project-Conversion-img6.jpg)

   ![Syncfusion Essential JS 2 ASP.NET Core required Scripts and Themes](Project-Conversion_images/Project-Conversion-img7.jpg)
   
   ![Syncfusion Essential JS 2 ASP.NET Core Scripts and Themes references in _Layout.cshtml file](Project-Conversion_images/Project-Conversion-img8.jpg)

5. If you installed the trial setup or NuGet packages from nuget.org you have to register the Syncfusion license key to your project since Syncfusion introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio release. Navigate to the [help topic](https://help.syncfusion.com/common/essential-studio/licensing/license-key#how-to-generate-syncfusion-license-key) to generate and register the Syncfusion license key to your project. Refer to this [blog](https://blog.syncfusion.com/post/Whats-New-in-2018-Volume-2-Licensing-Changes-in-the-1620x-Version-of-Essential-Studio.aspx?_ga=2.11237684.1233358434.1587355730-230058891.1567654773) post for understanding the licensing changes introduced in Essential Studio.
   
## Rendering Control after Syncfusion ASP.NET Core Conversion

Once you convert your ASP.NET Core Web Application to Syncfusion ASP.NET Core (Essential JS 2) Web Application using Syncfusion Visual Studio Extension, perform the following steps to render the Syncfusion controls to your project.

1. Include the Syncfusion control snippets to any of the view page of your project. Refer the following screenshot for more information.

   ![Syncfusion Essential JS 2 ASP.NET Core Calendar control code snippet](Project-Conversion_images\Project-Conversion-img9.jpg)

2. Then run the project and the following output will be displayed.

   ![Syncfusion Essential JS 2 ASP.NET Core Calendar control output](Project-Conversion_images\Project-Conversion-img10.jpg)
   
   