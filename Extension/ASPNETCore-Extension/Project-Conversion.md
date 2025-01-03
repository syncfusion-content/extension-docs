---
layout: post
title: Project Conversion | ASP.NET Core (Essential JS 1) | Syncfusion
description: Project Conversion is a add-in that converts an existing ASP.NET Core project into Syncfusion ASP.NET Core project by adding required Essential JS 1 components
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Syncfusion<sup style="font-size:70%">&reg;</sup> Project Conversion  

Syncfusion<sup style="font-size:70%">&reg;</sup> Project Conversion is a Visual Studio add-in that converts an existing ASP.NET Core application into a Syncfusion<sup style="font-size:70%">&reg;</sup> ASP.NET Core Web application by adding the required assemblies and resource files.

I> The Syncfusion ASP.NET Core Web Application Project Conversion utility is available from v15.2.0.40. 

## Convert into Syncfusion<sup style="font-size:70%">&reg;</sup> ASP.NET Core Web Application 

The following steps help you to use the Syncfusion<sup style="font-size:70%">&reg;</sup> Project Conversion in the existing ASP.NET Core Web Application.

> Before use, the Syncfusion<sup style="font-size:70%">&reg;</sup> ASP.NET Core (Essential<sup style="font-size:70%">&reg;</sup> JS 1) Project Conversion, check whether the **Syncfusion<sup style="font-size:70%">&reg;</sup> Essential<sup style="font-size:70%">&reg;</sup> JS1 AspNet Core VSExtensions** installed or not in Visual Studio Extension Manager by clicking on the Tools -> Extensions and Updates -> Installed for Visual Studio 2017 or lower and for Visual Studio 2019 by clicking on the Extensions -> Manage Extensions -> Installed. Also, check whether the corresponding Essential Studio<sup style="font-size:70%">&reg;</sup> version build installed or not. If the Essential Studio<sup style="font-size:70%">&reg;</sup> version is not same for both the Extension and build, then the Project Conversion will not be shown.

1. Open an existing Microsoft ASP.NET Core Web Application or create a new Microsoft ASP.NET Core Web Application. 

2. To open Project Conversion Wizard, follow either one of the options below: 

   **Option 1:**  
   Click **Syncfusion<sup style="font-size:70%">&reg;</sup> Menu** and choose **Essential Studio<sup style="font-size:70%">&reg;</sup> for ASP.NET Core (EJ1) > Convert to Syncfusion<sup style="font-size:70%">&reg;</sup> ASP.NET Core Application…** in **Visual Studio**.

   ![Syncfusion Essential JS 1 ASP.NET Core Project Conversion via Syncfusion menu](Project-Conversion_images/Syncfusion_Menu_Project_Conversion.png)

   N> In Visual Studio 2019, Syncfusion<sup style="font-size:70%">&reg;</sup> menu available under Extension in Visual Studio menu.

   **Option 2:**  
   Right-click the Project from Solution Explorer, select **Syncfusion<sup style="font-size:70%">&reg;</sup> Essential<sup style="font-size:70%">&reg;</sup> JS 1**, and then choose **Convert to Syncfusion<sup style="font-size:70%">&reg;</sup> ASP.NET Core (Essential<sup style="font-size:70%">&reg;</sup> JS 1) Application...** Refer to the following screenshot for more information.

   ![Syncfusion Essential JS 1 ASP.NET Core Project Conversion add-in](Project-Conversion_images/Project-Conversion_img1.png)

3. Project Conversion Wizard opens to configure the project.

   ![Syncfusion Essential JS 1 ASP.NET Core Project Conversion wizard](Project-Conversion_images/Project-Conversion-img2.jpg)

   **Choose the assets from:**

   * Bower - Refer to the assets from Bower package manager. 

   * CDN - Refer to the assets from Syncfusion<sup style="font-size:70%">&reg;</sup> CDN links.

   * Installed Location - Refer to the assets from Syncfusion<sup style="font-size:70%">&reg;</sup> installed locations.     
   
   ![Choose the required assets for Syncfusion Essential JS 1 ASP.NET Core project](Project-Conversion_images/Project-Conversion-img3.jpeg)
   
   **Choose the Theme:**
   
   The master page of project will be updated based on selected theme. The Theme Preview section shows the controls preview before convert into a Syncfusion<sup style="font-size:70%">&reg;</sup> project
   
   ![Choose the theme to apply on the master page of the ASP.NET Core project](Project-Conversion_images/Project-Conversion-img4.jpeg)

   **Choose Copy Global Resources:** 
    
   The localization culture files will be shipped into Scripts\ej\i18n directory of the project.

   ![Choose Copy Global Resources to ship the localization culture files for ASP.NET Core project](Project-Conversion_images/Project-Conversion-img14.jpeg)  
4. Choose the required controls from Components section and Click the **Convert** button to convert it into a Syncfusion<sup style="font-size:70%">&reg;</sup> Project.

   ![Select the required components from the Components selection in the Syncfusion ASP.NET Core Project Conversion Wizard](Project-Conversion_images/ProjectConversion-img5.jpg)
   
   The **Project Backup** dialog will be opened. If click Yes it will backup the current project before converting it to Syncfusion<sup style="font-size:70%">&reg;</sup> project. If click No it will convert the project to Syncfusion<sup style="font-size:70%">&reg;</sup> project without backup. 
   
   ![Syncfusion Essential JS 1 ASP.NET Core Project converson backup dialog](Project-Conversion_images/Project-Conversion-img6.jpg)

5. The required Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet/Bower packages, Scripts and CSS are included in the ASP.NET Core Web Application. Refer to the following screenshots for more information.

   ![Required Syncfusion Essential JS 1 ASP.NET Core NuGet/Bower packages](Project-Conversion_images/Project-Conversion-img7.jpeg)

   ![Required Syncfusion Essential JS 1 ASP.NET Core themes and scripts](Project-Conversion_images/Project-Conversion-img8.jpeg)

6. If you installed the trial setup or NuGet packages from nuget.org you have to register the Syncfusion<sup style="font-size:70%">&reg;</sup> license key to your project since Syncfusion<sup style="font-size:70%">&reg;</sup> introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio<sup style="font-size:70%">&reg;</sup> release. Navigate to the [help topic](https://help.syncfusion.com/common/essential-studio/licensing/license-key#how-to-generate-syncfusion-license-key) to generate and register the Syncfusion<sup style="font-size:70%">&reg;</sup> license key to your project. Refer to this [blog](https://blog.syncfusion.com/post/Whats-New-in-2018-Volume-2-Licensing-Changes-in-the-1620x-Version-of-Essential-Studio.aspx?_ga=2.11237684.1233358434.1587355730-230058891.1567654773) post for understanding the licensing changes introduced in Essential Studio<sup style="font-size:70%">&reg;</sup>.
   
## Rendering Control after Syncfusion<sup style="font-size:70%">&reg;</sup> ASP.NET Core Conversion

Once you converted your ASP.NET Core Web Application to Syncfusion<sup style="font-size:70%">&reg;</sup> ASP.NET Core Web Application using Syncfusion<sup style="font-size:70%">&reg;</sup> Visual Studio Extension, Perform the following steps to render the Syncfusion<sup style="font-size:70%">&reg;</sup> controls to your project.

1. Include the Syncfusion<sup style="font-size:70%">&reg;</sup> control snippets to any of the view page of your project. Refer the following screenshot for more information.

   ![Syncfusion Essential JS 1 ASP.NET Core datepicker control code snippet](Project-Conversion_images\Project-Conversion-img11.jpeg)

2. Then run the project and the following output will be displayed.

   ![Syncfusion Essential JS 1 ASP.NET Core datepicker control output](Project-Conversion_images\Project-Conversion-img12.jpeg)
   
   
   I> Refer all the required external and internal scripts only once in the page with proper order. Refer this [link](https://help.syncfusion.com/js/control-initialization#adding-the-required-javascript-files) to know about order of script reference.