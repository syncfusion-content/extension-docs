---
layout: post
title: Xamarin Item Template | Extension | Syncfusion
description: The Syncfusion Xamarin Item Templates extension provides the predefined design for the Xamarin.Forms.
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Syncfusion Item Templates for Xamarin

The Syncfusion item templates extension provides a predefined design for the Xamarin.Forms. Follow the given steps to add the Syncfusion predefined files in Visual Studio. 

 N> Syncfusion Xamarin item template is available in Essential Studio version 17.1.0.32

## Add Syncfusion Xamarin Item Template 
Follow these steps to add the Syncfusion Xamarin item in Visual Studio:

1. Open a new or existing **Xamarin** application.
 
2. Select the **Xamarin.Forms** project. Follow any of the given options:

   **Option1:**  Right-click the **Xamarin.Form** Project from the **Solution Explorer**. Select the **Syncfusion UI for Xamarin** option. Refer to the following screenshot for more information.

    ![Syncfusion Item Template Context menu](Syncfusion-Item-Templates_images/Item-Template-Context-Menu.png)

   **Option2:** Select **Syncfusion > Essential Studio for Xamarin** from the top-level menu in Visual Studio and select the item template. Refer to the following screenshot for more information.


    ![Syncfusion Menu for item template](Syncfusion-Item-Templates_images/Syncfuion-menu.png)
   
      N> The **Syncfusion>Essential Studio for Xamarin** menu is not visible and it can be made visible by installing the Xamarin project template extension. It will not be visible if only Xamarin UI template is installed.
   
   **Option3:** Right-click the **Xamarin.Form** Project from the **Solution Explorer**. Select **Add > New Item**. Refer to the following screenshot for more information.
 
     
     ![Add New Item menu](Syncfusion-Item-Templates_images/Add-new-item.png)

   The **Add New Item Dialog box** opens.

     ![Add new item dialog box](Syncfusion-Item-Templates_images/Add-New-Item-dialog-box.png)

3. Now, click **ADD**. The selected template is added to the project along with **Syncfusion NuGet package references**.

   ![After item template is add in project](Syncfusion-Item-Templates_images/After-add-item.png)

   ![Syncfusion Packages is installed in project](Syncfusion-Item-Templates_images/syncfusion-package.png)

   ![After Resource files add in project](Syncfusion-Item-Templates_images/Resource-file.png)

4. If you installed the trial setup or NuGet packages from nuget.org you have to register the Syncfusion license key to your project since Syncfusion introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio release. Navigate to the [help topic](https://help.syncfusion.com/common/essential-studio/licensing/license-key#how-to-generate-syncfusion-license-key) to generate and register the Syncfusion license key to your project. Refer to this [blog](https://blog.syncfusion.com/post/Whats-New-in-2018-Volume-2-Licensing-Changes-in-the-1620x-Version-of-Essential-Studio.aspx?_ga=2.11237684.1233358434.1587355730-230058891.1567654773) post for understanding the licensing changes introduced in Essential Studio.

## How to render the Syncfusion Xamarin item template
You should make the selected template page as startup page in this application. To do this, open the **App.xaml.cs** and make the following changes.

MainPage=new application name.Views. 
**Item name**.selected template page name();

Eg: If you added Login Page,

MainPage=new App1.Views.Login1.LoginPage();
