---
layout: post
title: Create Project | xamarin | Syncfusion
description: Syncfusion  Project Templates Extension creates the Syncfusion  Xamarin Application by adding the required Syncfusion  NuGet packages.
platform: extension
control: Syncfusion  Extensions
documentation: ug
---

# Creating Syncfusion<sup style="font-size:70%">&reg;</sup>  Xamarin Application

Syncfusion provides Visual Studio Project Templates for the Syncfusion<sup style="font-size:70%">&reg;</sup>  Xamarin platform, allowing you to quickly develop a Syncfusion<sup style="font-size:70%">&reg;</sup>  Xamarin application by just adding the needed Syncfusion<sup style="font-size:70%">&reg;</sup>  NuGet packages for the control you want to use.

I> The Syncfusion<sup style="font-size:70%">&reg;</sup>  Xamarin Project Templates are available from v16.2.0.41.

To create the **Syncfusion Xamarin Application** in Visual Studio 2017, follow these steps

> Check whether the **Xamarin Extensions - Syncfusion** are installed or not in Visual Studio Extension Manager by going to **Tools -> Extensions and Updates -> Installed** for Visual Studio 2017 or lower, and **Extensions -> Manage Extensions -> Installed** for Visual Studio 2019 by going to **Extensions -> Manage Extensions -> Installed**. If this extension not installed, please install the extension by follow the steps from the [download and installation](download-and-installation) help topic.

1.	Follow one of the instructions below to create a Syncfusion<sup style="font-size:70%">&reg;</sup>  Xamarin project

	**Option 1:**  
	Click **Syncfusion Menu** and choose **Essential Studio for Xamarin > Create New Syncfusion<sup style="font-size:70%">&reg;</sup>  Project…** in **Visual Studio**.

	![Choose Syncfusion  Xamarin application from Visual Studio new project dialog via Syncfusion<sup style="font-size:70%">&reg;</sup>  menu](Syncfusion-Project-Templates_images/Syncfusion_Menu_ProjectTemplate.png)

	N> From Visual Studio 2019, Syncfusion<sup style="font-size:70%">&reg;</sup>  menu is available under Extensions in Visual Studio menu.

	![Choose Syncfusion  Xamarin application from Visual Studio new project dialog via Syncfusion<sup style="font-size:70%">&reg;</sup>  menu](Syncfusion-Project-Templates_images/Syncfusion_Menu_ProjectTemplate_2019.png)

	**Option 2:**  
	Choose **File > New > Project** and navigate to **Syncfusion > Cross-Platform > Syncfusion<sup style="font-size:70%">&reg;</sup>  Xamarin Project Template** in **Visual Studio**.

	![Choose Syncfusion Xamarin application from Visual Studio new project dialog](Syncfusion-Project-Templates_images/Syncfusion-Project-Templates-img1.jpeg)

	In Visual Studio 2019, Syncfusion<sup style="font-size:70%">&reg;</sup>  Xamarin project creation wizard like below.

	![Choose Syncfusion  Xamarin application from Visual Studio new project dialog](Syncfusion-Project-Templates_images/Syncfusion-Project-Templates-img1_2019.png)

2.	Click **OK** once you've given the **project  name**, selected a destination location, and set the project's Framework. The Project Configuration Wizard is now displayed.
   
3.	Choose the Project, Android, iOS, and UWP by on/off in the following Project Configuration window to configure the Syncfusion<sup style="font-size:70%">&reg;</sup>  Xamarin Application.

    ![Syncfusion Xamarin project configuaration wizard](Syncfusion-Project-Templates_images/Syncfusion-Project-Templates-img2.jpeg)

	**Project Configuration:**

	**Assemblies From:** Choose NuGet or Installed Location to load the Syncfusion<sup style="font-size:70%">&reg;</sup>  Xamarin reference into Xamarin Application.

	N> Installed location option will be shown only when the Syncfusion<sup style="font-size:70%">&reg;</sup>  Xamarin setup has been installed.

	**Android**

	1. **Minimum Android Version:** Choose the earliest Android version for which you want to provide support for your app. 
	2. **Target Android Version:** Choose the Android version on which your app will run. 

	**iOS**

	1. **Target Device:**  Choose the Xamarin.iOS device of Xamarin.iOS project either Unified, iPhone/iPod, or iPad.
	2. **Target Version:** Select the Xamarin.iOS Project version.

	**Choose controls:** To create the Syncfusion<sup style="font-size:70%">&reg;</sup>  Xamarin application, choose at least one Syncfusion<sup style="font-size:70%">&reg;</sup>  control. 

	N> If you want to add other Syncfusion<sup style="font-size:70%">&reg;</sup>  Xamarin controls in the created Syncfusion<sup style="font-size:70%">&reg;</sup>  Xamarin application, you can use our [Syncfusion Xamarin toolbox](https://help.syncfusion.com/xamarin/visual-studio-integration/toolbox-control)

	![Choose Syncfusion  Xamarin control](Syncfusion-Project-Templates_images/Syncfusion-Project-Templates-img4.png)

4.	The Syncfusion<sup style="font-size:70%">&reg;</sup>  Xamarin Application has been created when you click **Create**.

	N> Choose any one of the project type and controls from Project Configuration Wizard.

	![Selected Syncfusion  Xamarin control assemblies added to the UWP project](Syncfusion-Project-Templates_images/Syncfusion-Project-Templates-img13.PNG)

5.	Based on the control selected, required Syncfusion<sup style="font-size:70%">&reg;</sup>  NuGet/Assemblies and configuration have been added to the project.

	**Net Standard /PCL**

	![Selected Syncfusion  Xamarin control NuGet package installed in project](Syncfusion-Project-Templates_images/Syncfusion-Project-Templates-img3.jpeg)

	![Selected Syncfusion  Xamarin control assemblies added to the project](Syncfusion-Project-Templates_images/Syncfusion-Project-Templates-img5.jpeg)

	**Android**

	![Selected Syncfusion  Xamarin control Android NuGet package](Syncfusion-Project-Templates_images/Syncfusion-Project-Templates-img6.jpeg)

	![Selected Syncfusion  Xamarin control assemblies added to the Android project](Syncfusion-Project-Templates_images/Syncfusion-Project-Templates-img7.jpeg)

	**iOS**

	![Selected Syncfusion  Xamarin control iOS NuGet package](Syncfusion-Project-Templates_images/Syncfusion-Project-Templates-img8.jpeg)

	![Selected Syncfusion Xamarin control assemblies added to the iOS project](Syncfusion-Project-Templates_images/Syncfusion-Project-Templates-img9.jpeg)

	**UWP**

	![Selected Syncfusion  Xamarin control UWP NuGet package](Syncfusion-Project-Templates_images/Syncfusion-Project-Templates-img10.jpeg)

	![Selected Syncfusion Xamarin control assemblies added to the UWP project](Syncfusion-Project-Templates_images/Syncfusion-Project-Templates-img11.jpeg)

6.	Then, Syncfusion<sup style="font-size:70%">&reg;</sup>  licensing registration required message box will be shown if you installed the trial setup or NuGet packages since Syncfusion<sup style="font-size:70%">&reg;</sup>  introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio<sup style="font-size:70%">&reg;</sup>  release. Navigate to the [help topic](https://help.syncfusion.com/common/essential-studio/licensing/overview#how-to-generate-syncfusion-license-key), which is shown in the licensing message box to generate and register the Syncfusion<sup style="font-size:70%">&reg;</sup>  license key to your project. Refer to this [blog](https://blog.syncfusion.com/post/Whats-New-in-2018-Volume-2-Licensing-Changes-in-the-1620x-Version-of-Essential-Studio.aspx) post for understanding the licensing changes introduced in Essential Studio.

	![Syncfusion license registration required information dialog in Syncfusion  Xamarin Project](Syncfusion-Project-Templates_images/Syncfusion-Project-Templates-img12.jpeg)


