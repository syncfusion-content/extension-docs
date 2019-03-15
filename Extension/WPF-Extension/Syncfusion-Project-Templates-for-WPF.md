---
layout: post
title: Syncfusion Project Templates for WPF | Extension | Syncfusion
description: Syncfusion provides the Visual Studio Project Templates for the Syncfusion WPF platform to create Syncfusion WPF Application by addiing the required assemblies
platform: extension
control: Syncfusion Extensions
documentation: ug
---


# Syncfusion Project Templates

Syncfusion provides the Visual Studio Project Templates for the Syncfusion WPF platform to create Syncfusion WPF Application. 

I> The Syncfusion WPF templates are available from v16.1.0.24. 

## Create Syncfusion WPF Project 

The following steps help you to create the Syncfusion WPF project through the Visual Studio Project Template. 

1. To create a Syncfusion WPF project, follow either one of the options below:

   **Option 1:**  
    Click **Syncfusion Menu** and choose **Essential Studio for WPF > Create New Syncfusion Project…** in **Visual Studio**.
    
    ![Choose Syncfusion WPF Application from Visual Studio new project dialog via Syncfusion menu](Project-Template-images\Syncfusion_Menu_ProjectTemplate.png)

    N> In Visual Studio 2019, Syncfusion menu available under Extension in Visual Studio menu.

    **Option 2:**   
    Choose **File > New > Project** and navigate to **Syncfusion > Windows > Syncfusion WPF Application** in **Visual Studio**.

   ![Choose Syncfusion WPF Application from Visual Studio new project dialog](Project-Template-images\Syncfusion-Project-Template-Gallery-1.png)

2. Name the Project, choose the destination location when required and set the Framework of the project, then click OK.  

   N> Minimum target Framework is 4.0 for Syncfusion WPF project templates. 

3. Choose the options to configure the Syncfusion WPF Application by using the following Project Configuration Wizard.  
  
   ![Syncfusion WPF project configuration wizard](Project-Template-images\Syncfusion-Project-Template-Gallery-2.png)
                                                     
   ### Project configurations: 

   **Language:** Select the language, either C# or VB. 

   ![Choose the language in Syncfusion WPF project configuration wizard](Project-Template-images\Syncfusion-Project-Template-Gallery-3.png)

   **Choose Theme:** Choose the required theme. 

   ![Choose theme in Syncfusion WPF project configuration wizard](Project-Template-images\Syncfusion-Project-Template-Gallery-4.png)

   **Assemblies From:** Choose the assembly location from where it is going to be added to the project. 

   ![Choose the required assemblies from option from where assemblies to be referred in the project](Project-Template-images\Syncfusion-Project-Template-Gallery-5.png)

   **Select Control:** Choose the control based on your need. 

   ![Choose the control based in Syncfusion WPF project configuration wizard](Project-Template-images\Syncfusion-Project-Template-Gallery-6.png)
      
4. Once the Project Configuration Wizard is done, the Syncfusion WPF project is created with required references and XAML. 

   ![Syncfusion WPF project created with required Syncfusion WPF assemblies](Project-Template-images\Syncfusion-Project-Template-Gallery-7.png)

   ![Syncfusion WPF project created with required Syncfusion XAML files](Project-Template-images\Syncfusion-Project-Template-Gallery-8.png)

5. Then, Syncfusion licensing registration required message box will be shown as follow, if you are installed the trial setup or NuGet packages since Syncfusion introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio release. Please navigate to the [help topic](https://help.syncfusion.com/common/essential-studio/licensing/license-key#how-to-generate-syncfusion-license-key) which is shown in the licensing message box to generate and register the Syncfusion license key to your project. Refer to this [blog](https://blog.syncfusion.com/post/Whats-New-in-2018-Volume-2-Licensing-Changes-in-the-1620x-Version-of-Essential-Studio.aspx) post for understanding the licensing changes introduced in Essential Studio.

   ![Syncfusion license registration required information dialog in Syncfusion WPF project](Project-Template-images\Syncfusion-Project-Template-Gallery-9.png)   