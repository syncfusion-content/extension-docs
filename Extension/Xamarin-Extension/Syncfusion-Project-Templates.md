---
layout: post
title: Syncfusion Xamarin Project Templates | Extension | Syncfusion
description: Syncfusion provides the Visual Studio Project Templates for the Syncfusion Xamarin platform to create the Syncfusion Xamarin Application by adding the required assemblies and NuGet packages
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Syncfusion Project Templates

Syncfusion provides the **Visual** **Studio** **Project** **Templates** for the Syncfusion Xamarin platform to create the Syncfusion Xamarin Application.

I> The Syncfusion Xamarin Project Templates are available from v16.2.0.41.


## Create Syncfusion Xamarin Application

The following steps help you to create the **Syncfusion** **Xamarin** **Application** through the **Visual** **Studio** **2017:**

1. To create a Syncfusion Xamarin project, follow either one of the options below:

   **Option 1:**  
   Click **Syncfusion Menu** and choose **Essential Studio for Xamarin > Create New Syncfusion Project…** in **Visual Studio**.

   ![Choose Syncfusion Xamarin application from Visual Studio new project dialog via Syncfusion menu](Syncfusion-Project-Templates_images/Syncfusion_Menu_ProjectTemplate.png)

   N> In Visual Studio 2019, Syncfusion menu available under Extension in Visual Studio menu.

   **Option 2:**  
   Choose **File > New > Project** and navigate to **Syncfusion > Cross-Platform > Syncfusion Xamarin Project Template** in **Visual Studio**.

   ![Choose Syncfusion Xamarin application from Visual Studio new project dialog](Syncfusion-Project-Templates_images/Syncfusion-Project-Templates-img1.jpeg)

2. Name the **Project**, choose the destination location, and set the Framework of the project, and then click **OK**. The Project Configuration Wizard appears.
   
3. Choose the options to configure the Syncfusion Xamarin Application by using the following Project Configuration dialog.

### Project Configuration:

Choose the Project, Android, iOS, and UWP by on/off 

   ![Syncfusion Xamarin project configuaration wizard](Syncfusion-Project-Templates_images/Syncfusion-Project-Templates-img2.jpeg)

**Assemblies From:** Load the Syncfusion Xamarin reference to Xamarin Application, either NuGet or Installed Location.

  N> *Installed location option will be available only when installed the Syncfusion Xamarin setup has been installed*.

**Android:**

1.	**Minimum Android Version:** Select the oldest Android version that you want to support your application. 
2.	**Target Android Version:** Select the version of Android to run your application. 

**iOS:**

1.	**Target Device:**  Select the device of Xamarin.iOS Project, either Unified, iPhone/iPod, or iPad.
2.	**Target Version:** Choose the version of Xamarin.iOS Project.

**Choose controls**

Choose the Xamarin application needs to create with the Syncfusion controls. 

4.Click **Create**, the Syncfusion Xamarin Application has been created.

   N> *Choose any one of the project type and controls from Project Configuration Wizard.*

5.Required Syncfusion NuGet/Assemblies and configuration have been added to the project based on the control chosen.

**Net Standard /PCL:**

![Selected Syncfusion Xamarin control NuGet package installed in project](Syncfusion-Project-Templates_images/Syncfusion-Project-Templates-img3.jpeg)

![Selected Syncfusion Xamarin control assemblies added to the project](Syncfusion-Project-Templates_images/Syncfusion-Project-Templates-img4.jpeg)

**Android:**

![Selected Syncfusion Xamarin control Android NuGet package](Syncfusion-Project-Templates_images/Syncfusion-Project-Templates-img5.jpeg)

![Selected Syncfusion Xamarin control assemblies added to the Android project](Syncfusion-Project-Templates_images/Syncfusion-Project-Templates-img6.jpeg)

**iOS:**

![Selected Syncfusion Xamarin control iOS NuGet package](Syncfusion-Project-Templates_images/Syncfusion-Project-Templates-img7.jpeg)

![Selected Syncfusion Xamarin control assemblies added to the iOS project](Syncfusion-Project-Templates_images/Syncfusion-Project-Templates-img8.jpeg)

**UWP:**

![Selected Syncfusion Xamarin control UWP NuGet package](Syncfusion-Project-Templates_images/Syncfusion-Project-Templates-img9.jpeg)

![Selected Syncfusion Xamarin control assemblies added to the UWP project](Syncfusion-Project-Templates_images/Syncfusion-Project-Templates-img10.jpeg)

6.Then, Syncfusion licensing registration required message box will be shown as follow, if you are installed the trial setup or NuGet packages since Syncfusion introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio release. Please navigate to the [help topic](https://help.syncfusion.com/common/essential-studio/licensing/license-key#how-to-generate-syncfusion-license-key) which is shown in the licensing message box to generate and register the Syncfusion license key to your project. Refer to this [blog](https://blog.syncfusion.com/post/Whats-New-in-2018-Volume-2-Licensing-Changes-in-the-1620x-Version-of-Essential-Studio.aspx) post for understanding the licensing changes introduced in Essential Studio.

![Syncfusion license registration required information dialog in Syncfusion Xamarin Project](Syncfusion-Project-Templates_images/Syncfusion-Project-Templates-img11.jpeg)


