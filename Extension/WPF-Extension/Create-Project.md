---
layout: post
title: Create Project | Wpf | Syncfusion
description: Syncfusion provides the Visual Studio Project Templates for the Syncfusion WPF platform to create Syncfusion WPF Application by addiing the required assemblies
platform: extension
control: Syncfusion Extensions
documentation: ug
---


# Create WPF application

The Visual Studio Project Templates for the Syncfusion<sup style="font-size:70%">&reg;</sup> WPF platform allow you to quickly develop a Syncfusion<sup style="font-size:70%">&reg;</sup> WPF application by just adding the appropriate Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies and XAML. 

I> The Syncfusion<sup style="font-size:70%">&reg;</sup> WPF templates are available from v16.1.0.24. 

> WPF Project Template works seamlessly with Visual Studio 2015 or lower. For the Visual Studio 2017 or later versions, it is recommended to use a [WPF Template Studio](https://help.Syncfusion.com/wpf/visual-studio-integration/template-studio).

Create the Syncfusion<sup style="font-size:70%">&reg;</sup> WPF project using the Visual Studio Project Template by following the steps below: 

> Check whether the **WPF Extensions - Syncfusion<sup style="font-size:70%">&reg;</sup>** are installed or not in Visual Studio 2015 or lower by going to **Tools -> Extensions and Updates -> Installed**. If this extension not installed, please install the extension by follow the steps from the [download and installation](https://help.Syncfusion.com/wpf/visual-studio-integration/download-and-installation) help topic.

1.	To create a Syncfusion<sup style="font-size:70%">&reg;</sup> WPF project, follow either one of the options below:

	**Option 1:**  
	Click **Syncfusion<sup style="font-size:70%">&reg;</sup>** Menu and choose **Essential Studio<sup style="font-size:70%">&reg;</sup> for WPF > Create New Syncfusion<sup style="font-size:70%">&reg;</sup> Project…**  in **Visual Studio**.
    
	![Choose Syncfusion<sup style="font-size:70%">&reg;</sup> WPF Application from Visual Studio new project dialog via Syncfusion<sup style="font-size:70%">&reg;</sup> menu](Project-Template-images/Syncfusion-Menu.png)

	N> In Visual Studio 2015 or lower, you can see the  Syncfusion<sup style="font-size:70%">&reg;</sup> menu directly in the Visual Studio menu.

	**Option 2:**   
	Choose **File -> New -> Project**. Opens a new dialog to create a new project. By filtering the project type with Syncfusion<sup style="font-size:70%">&reg;</sup> or using the Syncfusion<sup style="font-size:70%">&reg;</sup> keyword in the search option, you can get the templates offered by Syncfusion<sup style="font-size:70%">&reg;</sup> for WPF.

	![Choose Syncfusion<sup style="font-size:70%">&reg;</sup> WPF Application from Visual Studio new project dialog](Project-Template-images/Syncfusion-Project-Template-Gallery2019-1.png)

	In Visual Studio 2015 or lower, Select **File > New > Project** and navigate to **Syncfusion<sup style="font-size:70%">&reg;</sup> > Windows > Syncfusion<sup style="font-size:70%">&reg;</sup> WPF Application** in Visual Studio. 

	![Choose Syncfusion<sup style="font-size:70%">&reg;</sup> WPF Application from Visual Studio new project dialog](Project-Template-images/Syncfusion-Project-Template-Gallery-1.png)

2.	Name the **Project**, select the destination location when required, and specify the Framework of the project, then click **OK**.  

	N> For Syncfusion<sup style="font-size:70%">&reg;</sup> WPF project templates, the minimum target Framework is 4.0. 

3.	Using the following Project Configuration Wizard, choose the options to configure the Syncfusion<sup style="font-size:70%">&reg;</sup> WPF Application.  
  
	![Syncfusion<sup style="font-size:70%">&reg;</sup> WPF project configuration wizard](Project-Template-images/Syncfusion-Project-Template-Gallery2019-2.png)
                                                 
	In Visual Studio 2015 or lower, Syncfusion<sup style="font-size:70%">&reg;</sup> WPF Application project configuration wizard. 

	![Syncfusion<sup style="font-size:70%">&reg;</sup> WPF project configuration wizard](Project-Template-images/Syncfusion-Project-Template-Gallery-2.png)

	**Project Configurations**

	**Language:** Select the language, either CSharp or VB.

	N> VB language is available only when you choose .NET Framework from option in Visual Studio.

	**Choose Theme:** Select the required theme.

	**Reference From:** Choose the assembly location such as NuGet, GAC Location, or Essential Studio<sup style="font-size:70%">&reg;</sup> installed location, from where the assembly is added to the project.

	N> The installed location and GAC options will be available only after the Syncfusion<sup style="font-size:70%">&reg;</sup> Essential<sup style="font-size:70%">&reg;</sup> WPF setup has been installed. You can use the NuGet option instead of installing the Syncfusion<sup style="font-size:70%">&reg;</sup> Essential<sup style="font-size:70%">&reg;</sup> WPF setup.

	**Installed ES Build Version:** To add the appropriate version assemblies to the project, choose the build version.

	N> Installed ES build version option will be available only if you install the Syncfusion<sup style="font-size:70%">&reg;</sup> Essential<sup style="font-size:70%">&reg;</sup> WPF setup and select Installed Location or GAC as the assembly location.

	**Size Mode:** Select the Size Mode either Default or Touch.

	**Select Window:** Choose the window as required for application.

	N> Project create option will be enabled only if you have selected the window
      
4.	After choosing above project configuration options in the Project Configuration Wizard, click the create button then Syncfusion<sup style="font-size:70%">&reg;</sup> WPF project is created with the necessary XAML files and required Syncfusion<sup style="font-size:70%">&reg;</sup> WPF assemblies/NuGet packages. 

	![Syncfusion<sup style="font-size:70%">&reg;</sup> WPF project created with required Syncfusion<sup style="font-size:70%">&reg;</sup> WPF assemblies](Project-Template-images/Syncfusion-Project-Template-Gallery-7.png)

	![Syncfusion<sup style="font-size:70%">&reg;</sup> WPF project created with required Syncfusion<sup style="font-size:70%">&reg;</sup> XAML files](Project-Template-images/Syncfusion-Project-Template-Gallery-8.png)

	![Syncfusion<sup style="font-size:70%">&reg;</sup> WPF project created with readme](Project-Template-images/Syncfusion-Project-Template-Gallery-10.png)

5.	Then, Syncfusion<sup style="font-size:70%">&reg;</sup> licensing registration required message box will be shown if you installed the trial setup or NuGet packages since Syncfusion<sup style="font-size:70%">&reg;</sup> introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio<sup style="font-size:70%">&reg;</sup> release. Navigate to the [help topic](https://help.Syncfusion.com/common/essential-studio/licensing/overview#how-to-generate-Syncfusion-license-key), which is shown in the licensing message box to generate and register the Syncfusion<sup style="font-size:70%">&reg;</sup> license key to your project. Refer to this [blog](https://www.Syncfusion.com/blogs/post/whats-new-in-2018-volume-2.aspx) post for understanding the licensing changes introduced in Essential Studio<sup style="font-size:70%">&reg;</sup>.

	![Syncfusion<sup style="font-size:70%">&reg;</sup> license registration required information dialog in Syncfusion<sup style="font-size:70%">&reg;</sup> WPF project](Project-Template-images/Syncfusion-Project-Template-Gallery-9.png)   