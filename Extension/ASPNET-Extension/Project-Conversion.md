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

   ![Syncfusion Essential JS 1 ASP.NET Web Forms Project Conversion add-in](Project-Conversion_images/Project-Conversion-img1.jpeg)

3. Project Conversion Wizard opens to configure the project.

   ![Syncfusion Essential JS 1 ASP.NET Web Forms Project Conversion wizard](Project-Conversion_images/Project-Conversion-img2.jpg)

   Choose the assembly location:

   * Added From GAC - Refer to the assemblies from Global Assembly Cache. 

   * Added from Installed Location - Refer to the assemblies from Syncfusion Installed locations.

   * Add Referenced Assemblies to Solution - Copy and refer to the assemblies from project's solution file lib directory.     
   
   ![Choose the assembly location from where assemblies to be referred to the ASP.NET Web Forms project](Project-Conversion_images/Project-Conversion-img3.jpeg)
   
   Choose the Theme:
   
   The master page of project will be updated based on selected theme. The Theme Preview section shows the controls preview before convert into a Syncfusion project
   
   ![Choose the theme to apply on the master page of the ASP.NET Web Forms project](Project-Conversion_images/Project-Conversion-img4.jpeg)

   Choose CDN Support:

   The master page of the project will be updated based on required Syncfusion CDN links.

   ![Choose CDN Support to refer the Syncfusion assets from CDN for ASP.NET Web Forms project](Project-Conversion_images/Project-Conversion-img13.jpeg)
 
   Choose Copy Global Resources: 
    
   The localization culture files will be shipped into Scripts\ej\i18n directory of the project.

   ![Choose Copy Global Resources to ship the localization culture files for ASP.NET Web Forms project](Project-Conversion_images/Project-Conversion-img14.jpeg)   

4. Choose the required controls from Components section and Click the **Convert** button to convert it into a Syncfusion Project.

   ![Select the required components from the Components section in the ASP.NET Web Forms Project Conversion Wizard](Project-Conversion_images/ProjectConversion-img5.jpg)
   
   The **Project Backup** dialog will be opened. If click Yes it will backup the current project before converting it to Syncfusion project. If click No it will convert the project to Syncfusion project without backup. 
   
   ![Syncfusion Essential JS 1 ASP.NET Web Forms Project Conversion backup dialog](Project-Conversion_images/Project-Conversion-img6.jpg)

5. The required Syncfusion Reference Assemblies, Scripts and CSS are included in the ASP.NET Project. Refer to the following screenshots for more information.

   ![Scripts and CSS for Syncfusion Essential JS 1 ASP.NET Web Forms Project](Project-Conversion_images/Project-Conversion-img7.jpeg)

   ![Reference assemblies use of Syncfusion Essential JS 1 ASP.NET Web Forms Project](Project-Conversion_images/Project-Conversion-img8.jpeg)

   ![Web.config assembly reference of Syncfusion Essential JS 1 ASP.NET Web Forms Project](Project-Conversion_images/Project-Conversion-img9.jpeg)


## Rendering Control after Syncfusion ASP.NET Conversion

Once you converted your ASP.NET Project to Syncfusion ASP.NET Project using Syncfusion Visual Studio Extension, Perform the following steps to render the Syncfusion controls to your project.
1. The CSS, Scripts, Syncfusion References and required Web.config file entries are added to your project by the Syncfusion ASP.NET Conversion.  

2. Add the required CSS and Script files references in master page (Site.Master file) of the project. Please refer to the below screenshot for more information.

   ![Required CSS and Script files references in master page file of the project](Project-Conversion_images\Project-Conversion-img10.jpeg)
   
3. Now, include the Syncfusion controls to your project. Refer the following screenshot for more information.

   ![Syncfusion Essential JS 1 ASP.NET Web Forms datepicker control snippet](Project-Conversion_images\Project-Conversion-img11.jpeg)

4. Run the project and the following output will be displayed.

   ![Syncfusion Essential JS 1 ASP.NET Web Forms datepicker control output](Project-Conversion_images\Project-Conversion-img12.jpeg)