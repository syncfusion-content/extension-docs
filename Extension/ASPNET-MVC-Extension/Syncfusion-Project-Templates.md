---
layout: post
title: ASP.NET MVC (Essential JS 1) Project Templates | ASP.NET MVC (Essential JS 1) | Syncfusion
description: Syncfusion provides the Visual Studio Project Templates for the Syncfusion ASP.NET MVC (Essential JS 1), Syncfusion Essential JS 1 ASP.NET MVC (Classic) and Essential JS 1 ASP.NET MVC (Mobile) platforms to create a Syncfusion MVC application using Essential JS 1 components
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Syncfusion Project Templates

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

The following steps help you create the Syncfusion ASP.NET MVC Project via the Visual Studio Project Template.

1. To create a Syncfusion Project, choose New Project-> Syncfusion->Web->Syncfusion ASP.NET MVC Web Application from Visual Studio.

   ![Choose Syncfusion ASP.NET MVC Web Application from Visual Studio new project dialog](Create-Syncfusion-MVC-Project_images/CreateSyncfusionMVCProject-img1.jpeg)

2. Name the Project, choose the destination location as required and set the Framework of the project then click OK. The Project Configuration Wizard appears.  

3. Choose the options to configure the Syncfusion ASP.NET MVC Application by using the following Project Configuration window.

   ![Syncfusion Essential JS 1 ASP.NET MVC Web Project configuration wizard](Create-Syncfusion-MVC-Project_images/CreateSyncfusionMVCProject-img2.jpeg)

   ### Project configurations:

   **Target MVC Version:** Choose the required MVC Version.

   ![Choose required MVC version](Create-Syncfusion-MVC-Project_images/CreateSyncfusionMVCProject-img3.jpeg)

   **View Engine:** Choose the View Engine of the Sample.

   ![Choose rquired View Engine](Create-Syncfusion-MVC-Project_images/CreateSyncfusionMVCProject-img4.jpeg)

   **Theme:** Choose the Required Theme.

   ![Choose required theme](Create-Syncfusion-MVC-Project_images/CreateSyncfusionMVCProject-img5.jpeg)

   **Language:** Select the language, either C# or VB.

   ![Choose required language](Create-Syncfusion-MVC-Project_images/CreateSyncfusionMVCProject-img6.jpeg)

   **Assemblies From:** Choose the assembly location from where it is going to be added to the project.

   ![Choose required assemblies location](Create-Syncfusion-MVC-Project_images/CreateSyncfusionMVCProject-img7.jpeg)

   **Use CDN Support:** The master page of the project will be updated based on required Syncfusion CDN links.

   ![Choose CDN support](Create-Syncfusion-MVC-Project_images/CreateSyncfusionMVCProject-img28.jpeg)

4. When you have not chosen the Add Samples option then the Syncfusion ASP.NET MVC/ Syncfusion ASP.NET MVC (Classic) project is created with required assemblies, CSS and Script files only.

5. By choosing the Add Samples option you can add the code examples for your selected controls and its features.

   ![Syncfusion Essential JS 1 ASP.NET MVC Web Feature section](Create-Syncfusion-MVC-Project_images/CreateSyncfusionMVCProject-img8.jpeg)

   **Select Control:** Choose the control based on your need.

   ![Choose required controls](Create-Syncfusion-MVC-Project_images/CreateSyncfusionMVCProject-img9.jpeg)

   **Select Feature:** Choose Feature based on your need.

   ![Choose required features](Create-Syncfusion-MVC-Project_images/CreateSyncfusionMVCProject-img10.jpeg)

6. Once the Project Configuration Wizard is done, the Syncfusion MVC Project is created.

   ![Required View and Controller files for Syncfusion Essential JS 1 ASP.NET MVC Web controls](Create-Syncfusion-MVC-Project_images/CreateSyncfusionMVCProject-img11.jpeg)

7. Syncfusion references, Scripts, CSS and required Web.config entries are added to the Project.

   ![Syncfusion Essential JS 1 ASP.NET MVC web controls required assemblies](Create-Syncfusion-MVC-Project_images/CreateSyncfusionMVCProject-img12.jpeg)

   ![Syncfusion Essential JS 1 ASP.NET MVC web controls required scripts and themes](Create-Syncfusion-MVC-Project_images/CreateSyncfusionMVCProject-img13.jpeg)

   ![Syncfusion Essential JS 1 ASP.NET MVC web controls required web.config entries](Create-Syncfusion-MVC-Project_images/CreateSyncfusionMVCProject-img14.jpeg)

8. Then, Syncfusion licensing registration required message box will be shown as follow, if you are installed the trial setup or NuGet packages since Syncfusion introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio release. Please navigate to the [help topic](https://help.syncfusion.com/common/essential-studio/licensing/license-key#how-to-generate-syncfusion-license-key) which is shown in the licensing message box to generate and register the Syncfusion license key to your project. Refer to this [blog](https://blog.syncfusion.com/post/Whats-New-in-2018-Volume-2-Licensing-Changes-in-the-1620x-Version-of-Essential-Studio.aspx) post for understanding the licensing changes introduced in Essential Studio.

   ![Syncfusion licensing registration required message box for Syncfusion Essential JS 1 ASP.NET MVC web projects](Create-Syncfusion-MVC-Project_images/CreateSyncfusionMVCProject-img29.jpeg)

## Create Syncfusion MVC (Mobile) Project

The following steps help you create the Syncfusion ASP.NET MVC (Mobile) Project via the Visual Studio Project Template.

1. To create a Syncfusion Project, choose **New Project -> Syncfusion -> Mobile -> Syncfusion ASP.NET MVC(Mobile) Application** from Visual Studio.

   ![Choose Syncfusion ASP.NET MVC(Mobile) Application from Visual Studio new project dialog](Create-Syncfusion-MVC-Project_images/CreateSyncfusionMVCProject-img15.jpeg)

2. Name the Project, choose the destination location as required and set the Framework of the project then click OK. The Project Configuration Wizard appears.  
3. Choose the options to configure the Syncfusion ASP.NET MVC Application by using the following Project Configuration window.

   ![Syncfusion Essential JS 1 ASP.NET MVC Mobile project configuration wizard](Create-Syncfusion-MVC-Project_images/CreateSyncfusionMVCProject-img16.jpeg)

   ### Project configurations:

   **Target MVC Version:** Choose the required MVC Version.

   ![Choose MVC Version](Create-Syncfusion-MVC-Project_images/CreateSyncfusionMVCProject-img17.jpeg)

   **View Engine:** Choose the View Engine of the Sample.

   ![Choose View Engine](Create-Syncfusion-MVC-Project_images/CreateSyncfusionMVCProject-img18.jpeg)

   **Theme:** Choose the Required Theme.

   ![Choose theme](Create-Syncfusion-MVC-Project_images/CreateSyncfusionMVCProject-img19.jpeg)

   **Language:** Select the language, either C# or VB.

   ![Choose language](Create-Syncfusion-MVC-Project_images/CreateSyncfusionMVCProject-img20.jpeg)

   **Assemblies From:** Choose the assembly location from where it is going to be added to the project.

   ![Choose assemblies location](Create-Syncfusion-MVC-Project_images/CreateSyncfusionMVCProject-img7.jpeg)

   **Project templates:** Choose the required Control.

   ![Choose required controls](Create-Syncfusion-MVC-Project_images/CreateSyncfusionMVCProject-img22.jpeg)

4. Once the Project Configuration Wizard is done, the Syncfusion MVC Project is created.

   ![Syncfusion Essential JS 1 ASP.NET MVC Mobile project required View and controller files](Create-Syncfusion-MVC-Project_images/CreateSyncfusionMVCProject-img23.jpeg)

5. Syncfusion references, Scripts, CSS and required Web.config entries are added to the Project.

   ![Syncfusion Essential JS 1 ASP.NET MVC Mobile project required assemblies](Create-Syncfusion-MVC-Project_images/CreateSyncfusionMVCProject-img24.jpeg)

   ![Syncfusion Essential JS 1 ASP.NET MVC Mobile project required themes](Create-Syncfusion-MVC-Project_images/CreateSyncfusionMVCProject-img25.jpeg)
 
   ![Syncfusion Essential JS 1 ASP.NET MVC Mobile project required scripts](Create-Syncfusion-MVC-Project_images/CreateSyncfusionMVCProject-img26.jpeg)

   ![Syncfusion Essential JS 1 ASP.NET MVC Mobile project required web.config entries](Create-Syncfusion-MVC-Project_images/CreateSyncfusionMVCProject-img27.jpeg)


