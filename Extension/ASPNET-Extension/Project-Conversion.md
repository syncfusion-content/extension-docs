---
layout: post
title: ASP.NET Web Forms (Essential JS 1) Project Conversion | Extension | Syncfusion
description: The Syncfusion ASP.NET Web Forms (Essential JS 1) Project Conversion is a Visual Studio add-in that converts an existing ASP.NET project into a Syncfusion Essential JS 1 ASP.NET Project by adding the required Essential JS 1 components
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Syncfusion Project Conversion  

Syncfusion Project Conversion is a Visual Studio add-in that converts an existing ASP.NET project into a Syncfusion ASP.NET Project by adding the required assemblies and resource files.

I> The Syncfusion ASP.NET Web Application Project Conversion utility is available from v13.1.0.30. 

## Convert into Syncfusion ASP.NET Project 

The following steps direct you to use the Syncfusion Project Conversion in the existing ASP.NET Project.


1. Open an existing Microsoft ASP.NET Project or create a new Microsoft ASP.NET Project.

2. Right-click on **Project** from Solution Explorer and select **Syncfusion VS Extensions** and choose the **Convert to Syncfusion ASP.NET Application**. Refer to the following screenshot for more information.

   ![Syncfusion ASP.NET Web Forms (Essential JS 1) Project Conversion add-in](Project-Conversion_images/Project-Conversion-img1.jpeg)

3. Project Conversion Wizard opens to configure the project.

   ![Syncfusion ASP.NET Web Forms (Essential JS 1) Project Conversion wizard](Project-Conversion_images/Project-Conversion-img2.jpg)

   Choose the assembly location:

   * Added From GAC - Refer to the assemblies from Global Assembly Cache. 

   * Added from Installed Location - Refer to the assemblies from Syncfusion Installed locations.

   * Add Referenced Assemblies to Solution - Copy and refer to the assemblies from project's solution file lib directory.     
   
   ![Choose the assembly location for Syncfusion ASP.NET Web Forms (Essential JS 1) Project Conversion](Project-Conversion_images/Project-Conversion-img3.jpeg)
   
   Choose the Theme:
   
   The master page of project will be updated based on selected theme. The Theme Preview section shows the controls preview before convert into a Syncfusion project
   
   ![Choose the Theme for Syncfusion ASP.NET Web Forms (Essential JS 1) Project Conversion](Project-Conversion_images/Project-Conversion-img4.jpeg)

   Choose CDN Support:

   The master page of the project will be updated based on required Syncfusion CDN links.

   ![Choose CDN Support for Syncfusion ASP.NET Web Forms (Essential JS 1) Project Conversion](Project-Conversion_images/Project-Conversion-img13.jpeg)
 
   Choose Copy Global Resources: 
    
   The localization culture files will be shipped into Scripts\ej\i18n directory of the project.

   ![Choose Copy Global Resources for Syncfusion ASP.NET Web Forms (Essential JS 1) Project Conversion](Project-Conversion_images/Project-Conversion-img14.jpeg)   

4. Choose the required controls from Components section and Click the **Convert** button to convert it into a Syncfusion Project.

   ![Components section for Syncfusion ASP.NET Web Forms (Essential JS 1) controls](Project-Conversion_images/ProjectConversion-img5.jpg)
   
   The **Project Backup** dialog will be opened. If click Yes it will backup the current project before converting it to Syncfusion project. If click No it will convert the project to Syncfusion project without backup. 
   
   ![Syncfusion ASP.NET Web Forms (Essential JS 1) Project Conversion backup dialog](Project-Conversion_images/Project-Conversion-img6.jpg)

5. The required Syncfusion Reference Assemblies, Scripts and CSS are included in the ASP.NET Project. Refer to the following screenshots for more information.

   ![Scripts and CSS for Syncfusion ASP.NET Web Forms (Essential JS 1) Project](Project-Conversion_images/Project-Conversion-img7.jpeg)

   ![Reference Assemblies for Syncfusion ASP.NET Web Forms (Essential JS 1) Project](Project-Conversion_images/Project-Conversion-img8.jpeg)

   ![web.config assembly reference for Syncfusion ASP.NET Web Forms (Essential JS 1) Project](Project-Conversion_images/Project-Conversion-img9.jpeg)


## Rendering Control after Syncfusion ASP.NET Conversion

Once you converted your ASP.NET Project to Syncfusion ASP.NET Project using Syncfusion Visual Studio Extension, Perform the following steps to render the Syncfusion controls to your project.
1. The CSS, Scripts, Syncfusion References and required Web.config file entries are added to your project by the Syncfusion ASP.NET Conversion.  

2. Add the required CSS and Script files references in master page (Site.Master file) of the project. Please refer to the below screenshot for more information.

   ![Required CSS and Script files references in master page (Site.Master file) of the project](Project-Conversion_images\Project-Conversion-img10.jpeg)
   
3. Now, include the Syncfusion controls to your project. Refer the following screenshot for more information.

   ![Syncfusion ASP.NET Web Forms (Essential JS 1) datepicker control snippet](Project-Conversion_images\Project-Conversion-img11.jpeg)

4. Run the project and the following output will be displayed.

   ![Syncfusion ASP.NET Web Forms (Essential JS 1) datepicker control output](Project-Conversion_images\Project-Conversion-img12.jpeg)