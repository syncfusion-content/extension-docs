---
layout: post
title: Project Templates | ASP.NET MVC (Essential JS 1) | Syncfusion
description: Syncfusion provides the Visual Studio Project Templates for the ASP.NET MVC platform to create a Syncfusion MVC application using Essential JS 1 components
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Syncfusion Project Templates for ASP.NET MVC (Essential JS 1)

Syncfusion provides the Visual Studio Project Templates for the Syncfusion ASP.NET MVC, Syncfusion ASP.NET MVC (Classic) and ASP.NET MVC (Mobile) platforms to create a Syncfusion MVC application.

Syncfusion ASP.NET MVC and ASP.NET MVC (Classic) Project Templates are included here,

* Essential Studio for Enterprise Edition with the platforms ASP.NETMVC or ASP.NET MVC(Classic)
* Essential Studio for ASP.NET MVC
* Essential Studio for ASP.NET MVC (Classic)

I> This is not applicable from v.12.1.0.43 to v.13.1.0.30. Syncfusion ASP.NET MVC and ASP.NET MVC (Classic) Project Templates are excluded from MVC Extension setup and integrated into Essential Studio ASP.NET MVC and ASP.NET MVC (Classic) platforms.

## ASP.NET MVC Extensions:

By default, the Syncfusion ASP.NET MVC extensions are configured in Visual Studio. When you want the ASP.NET MVC (Classic) extension, you can install it from the installed location.

Project Templates (ASP.NET MVC (Classic):

Location: `{Drive}\Program Files (x86)\Syncfusion\Essential Studio\<Version>\Utilities\Extensions\ASP.NET MVC \Classic`

For Example – VS2013:`C:\Program Files (x86)\Syncfusion\Essential Studio\13.2.0.18\Utilities\Extensions\ASP.NET MVC\Classic\4.5.1\Syncfusion.MVC.VSPackage.Web.Classic.vsix`

Refer to the following steps to create the Syncfusion ASP.NET MVC and ASP.NET MVC (Classic) applications.

## Create Syncfusion MVC (Web) Project    

The following steps help you create the Syncfusion ASP.NET MVC (Essential JS 1) Application via the Visual Studio Project Template:

> Before use the Syncfusion ASP.NET MVC (Essential JS 1) Project Template, check whether the **Syncfusion Essential JS1 AspNet MVC VSExtensions** installed or not in Visual Studio Extension Manager by clicking on the Tools -> Extensions and Updates -> Installed for Visual Studio 2017 or lower and for Visual Studio 2019 by clicking on the Extensions -> Manage Extensions -> Installed.

1. To create a Syncfusion ASP.NET MVC (Essential JS 1) project, follow either one of the options below:

   **Option 1:**  
    Click **Syncfusion Menu** and choose **Essential Studio for ASP.NET MVC (EJ1) > Create New Syncfusion Project…** in **Visual Studio**.

    ![Choose Syncfusion ASP.NET MVC Extension Web Application from Visual Studio new project dialog via Syncfusion menu project template](create-syncfusion-mvc-project_images/syncfusion-menu-project-template-in-aspnet-mvc-extension.png)

    N> In Visual Studio 2019, Syncfusion menu available under Extension in Visual Studio menu.

   **Option 2:**  
   Choose **File > New > Project** and navigate to **Syncfusion > Web > Syncfusion ASP.NET MVC (Essential JS 1) Application** in **Visual Studio**.
   
   ![Choose Syncfusion ASP.NET MVC Extension Web Application from Visual Studio new project dialog via syncfusion mVC Project Template](reate-syncfusion-mvc-project_images/create-syncfusion-mvc-project-with aspnet-mvc-extension-web-application.png)

2. Name the Project, choose the destination location as required and set the Framework of the project then click OK. The Project Configuration Wizard appears.  

3. Choose the options to configure the Syncfusion ASP.NET MVC Application by using the following Project Configuration window.

   ![Syncfusion Essential JS 1 ASP.NET MVCExtension for Web Project created templates configuration wizard](create-syncfusion-mvc-project_images/create-syncfusion-mvc-project-template-with-aspnet-mvc-extension-configuration-option.jpeg)

   ### Project configurations:

   **Target MVC Version:** Choose the required MVC Version.

   ![Choose required MVC version in ASP.NET MVC Extension for created project Template ](create-syncfusion-mvc-project_images/create-syncfusion-mvc-project-template-with-aspnet-mvc-extension-target-version.jpeg)

   **View Engine:** Choose the View Engine of the Sample.

   ![Choose required View Engine in ASP.NET MVC Extension for created project Template](create-syncfusion-mvc-project_images/create-syncfusion-mvc-project-template-with-aspnet-mvc-extension-view-engine.jpeg)

   **Theme:** Choose the Required Theme.

   ![Choose required theme in ASP.NET MVC Extension for created project Template](create-syncfusion-mvc-project_images/create-syncfusion-mvc-project-template-with-aspnet-mvc-extension-required-theme.jpeg)

   **Language:** Select the language, either C# or VB.

   ![Choose required language in ASP.NET MVC Extension for created project Template](create-syncfusion-mvc-project_images/create-syncfusion-mvc-project-template-with-aspnet-mvc-extension-language-selection.jpeg)

   **Assemblies From:** Choose the assembly location from where it is going to be added to the project.

   ![Choose the assembly location from where it is going to be added to the ASP.NET MVC Extension created template project](create-syncfusion-mvc-project_images/create-syncfusion-mvc-project-template-with-aspnet-mvc-extension-project-assembly-location.jpeg)

   **Use CDN Support:** The master page of the project will be updated based on required Syncfusion CDN links.

   ![Choose CDN support in ASP.NET MVC Extension for created project Template ](create-syncfusion-mvc-project_images/create-syncfusion-mvc-project-template-with-aspnet-mvc-extension-cdn-support.jpeg)

4. When you have not chosen the Add Samples option then the Syncfusion ASP.NET MVC/ Syncfusion ASP.NET MVC (Classic) project is created with required assemblies, CSS and Script files only.

5. By choosing the Add Samples option you can add the code examples for your selected controls and its features.

   ![Syncfusion Essential JS 1 ASP.NET MVC Extension for Web Feature selection with project template created](create-syncfusion-mvc-project_images/create-syncfusion-mvc-project-template-with-aspnet-mvc-extension-add-sample-option.jpeg)

   **Select Control:** Choose the control based on your need.

   ![Choose required controls in ASP.NET MVC Extension to create syncfusion MVC created project Template](create-syncfusion-mvc-project_images/create-syncfusion-mvc-project-template-with-aspnet-mvc-extension-control-selection.jpeg)

   **Select Feature:** Choose Feature based on your need.

   ![Choose required features in ASP.NET MVC Extension to create syncfusion MVC project Template](create-syncfusion-mvc-project_images/create-syncfusion-mvc-project-template-with-aspnet-mvc-extension-feature.jpeg)

6. Once the Project Configuration Wizard is done, the Syncfusion MVC Project is created.

   ![Required View and Controller files are added in ASP.NEt MVC Extension with the syncfusion MVC project template for the selected controls](create-syncfusion-mvc-project_images/create-syncfusion-mvc-project-template-with-aspnet-mvc-extension-files.jpeg)

7. Syncfusion references, Scripts, CSS and required Web.config entries are added to the Project.

   ![Required Syncfusion ASP.NET MVC Extension assemblies added in the project created templates for the selected controls](create-syncfusion-mvc-project_images/create-syncfusion-mvc-project-template-with-aspnet-mvc-extension-required-entries.jpeg)

   ![Required Syncfusion ASP.NET MVC Extension scripts and themes added in the Template project created](create-syncfusion-mvc-project_images/create-syncfusion-mvc-project-template-with-aspnet-mvc-extension-for-added-scripts-and-themes.jpeg)

   ![Web.config file configured for the selected controls in Syncfusion ASP.NET MVC Extension project Template created](create-syncfusion-mvc-project_images/created-syncfusion-mvc-project-template-with-aspnet-mvc-extension-web-config-files.jpeg)

8. Then, Syncfusion licensing registration required message box will be shown as follow, if you are installed the trial setup or NuGet packages since Syncfusion introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio release. Please navigate to the [help topic](https://help.syncfusion.com/common/essential-studio/licensing/overview#how-to-generate-syncfusion-license-key) which is shown in the licensing message box to generate and register the Syncfusion license key to your project. Refer to this [blog](https://www.syncfusion.com/blogs/post/whats-new-in-2018-volume-2.aspx) post for understanding the licensing changes introduced in Essential Studio.

   ![Syncfusion license registration required message box for Syncfusion Essential JS 1 ASP.NET MVC Extension web created in projects Templates](create-syncfusion-mvc-project_images/created-syncfusion-mvc-project-template-with-aspnet-mvc-extension-license-message-box.jpeg)

## Create Syncfusion MVC (Mobile) Project

The following steps help you create the Syncfusion ASP.NET MVC (Mobile) Project via the Visual Studio Project Template.

1. To create a Syncfusion Project, choose **New Project -> Syncfusion -> Mobile -> Syncfusion ASP.NET MVC(Mobile) Application** from Visual Studio.

   ![Choose Syncfusion ASP.NET MVC Extension in Mobile Application from Visual Studio new project dialog](Create-Syncfusion-MVC-Project_images/CreateSyncfusionMVCProject-img15.jpeg)

2. Name the Project, choose the destination location as required and set the Framework of the project then click OK. The Project Configuration Wizard appears.  
3. Choose the options to configure the Syncfusion ASP.NET MVC Application by using the following Project Configuration window.

   ![Syncfusion Essential JS 1 ASP.NET MVC Extension for Mobile project created templates with configuration wizard](create-syncfusion-mvc-project_images/created-syncfusion-mvc-project-template-with-aspnet-mvc-extension-mobile-wizard.jpeg)

   ### Project configurations:

   **Target MVC Version:** Choose the required MVC Version.

   ![Choose the target MVC Version for Syncfusion ASP.NET MVC Extension created project template](create-syncfusion-mvc-project_images/created-syncfusion-mvc-project-template-with-aspnet-mvc-extension-target-version.jpeg)

   **View Engine:** Choose the View Engine of the Sample.

   ![Choose View Engine in Syncfusion ASP.NET MVC Extension created project template](create-syncfusion-mvc-project_images/created-syncfusion-mvc-project-template-with-aspnet-mvc-extension-view-engine.jpeg)

   **Theme:** Choose the Required Theme.

   ![Choose the required theme in Syncfusion ASP.NET MVC Extension created project template](create-syncfusion-mvc-project_images/created-syncfusion-mvc-project-template-with-aspnet-mvc-extension-required-theme.jpeg)

   **Language:** Select the language, either C# or VB.

   ![Choose the created project template language for syncfusion ASP.NET MVC Extension](create-syncfusion-mvc-project_images/created-syncfusion-mvc-project-template-with-aspnet-mvc-extension-language.jpeg)

   **Assemblies From:** Choose the assembly location from where it is going to be added to the project.

   ![Choose the assembly location in Syncfusion ASP.NET MVC Extension created project template](create-syncfusion-mvc-project_images/created-syncfusion-mvc-project-template-with-aspnet-mvc-extension-assembly-location.jpeg)

   **Project templates:** Choose the required Control.

   ![Choose the required controls for syncfusion ASP.NET MVC Extension with created project templates](create-syncfusion-mvc-project_images/created-syncfusion-mvc-project-template-with-aspnet-mvc-extension-projet-template-control.jpeg)

4. Once the Project Configuration Wizard is done, the Syncfusion MVC Project is created.

   ![Required view and controller files added in the Syncfusion Essential JS 1 ASP.NET MVC Extension Mobile project created templates](create-syncfusion-mvc-project_images/created-syncfusion-mvc-project-template-with-aspnet-mvc-extension-required-files.jpeg)

5. Syncfusion references, Scripts, CSS and required Web.config entries are added to the Project.

   ![Required assemblies added as a reference in syncfusion ASP.NET MVC Extension with the project created templates](create-syncfusion-mvc-project_images/create-syncfusion-mvc-project_images/created-syncfusion-mvc-project-template-with-aspnet-mvc-extension-refrence-assemblies.jpeg)

   ![Required themes and scripts added to the project created templates in syncfusion ASP.NET MVC Extension](create-syncfusion-mvc-project_images/created-syncfusion-mvc-project-template-with-aspnet-mvc-extension-required-themes-and-scripts.jpeg)
 
   ![Syncfusion Essential JS 1 ASP.NET MVC in syncfusion ASP.NET MVC Extension Mobile project created templates required scripts](create-syncfusion-mvc-project_images/created-syncfusion-mvc-project-template-with-aspnet-mvc-extension-mobile-project.jpeg)

   ![Syncfusion Essential JS 1 ASP.NET MVC Extension in Mobile project created templates for Web.config configuration](create-syncfusion-mvc-project_images/created-syncfusion-mvc-project-template-with-aspnet-mvc-extension-web-config-configuration.jpeg)


