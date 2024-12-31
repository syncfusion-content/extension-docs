---
layout: post
title: Syncfusion Item Template | WinForms | Syncfusion
description: Syncfusion Item Templates provides to add the predefined forms with Syncfusion component in Windows Forms application.
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Add Syncfusion<sup style="font-size:70%">&reg;</sup> Components to the WinForms Application

Syncfusion<sup style="font-size:70%">&reg;</sup> supports Visual Studio Item Templates to add Syncfusion<sup style="font-size:70%">&reg;</sup> WinForms Components to a WinForms application with Syncfusion<sup style="font-size:70%">&reg;</sup> WinForms references. 

I> The Syncfusion<sup style="font-size:70%">&reg;</sup> Windows Forms item templates are available from v13.1.0.21.

The following steps will guide you in adding the Syncfusion<sup style="font-size:70%">&reg;</sup> WinForms components to your Visual Studio WinForms application.

> Check whether the **WinForms Extensions - Syncfusion<sup style="font-size:70%">&reg;</sup>** are installed or not in Visual Studio Extension Manager by going to **Extensions -> Manage Extensions -> Installed** for Visual Studio 2019 or later and Visual Studio 2017 or lower by going to **Tools -> Extensions and Updates -> Installed**. If this extension is not installed, please install the extension by following the steps from the [download and installation](https://help.Syncfusion.com/windowsforms/visual-studio-integration/download-and-installation) help topic.

## Add Components using Syncfusion<sup style="font-size:70%">&reg;</sup> Item Template

1.	Open a new or existing WinForms application.

	**Option 1:**

2.	From the **Solution Explorer, right-click** on the WinForms application. Choose **Add Syncfusion<sup style="font-size:70%">&reg;</sup> Item...**.

	![Choose Add Syncfusion<sup style="font-size:70%">&reg;</sup> Item option from right click project](Item-Template-images/Add-Syncfusion-item.png)

	**Option 2:**

3.	Click **Extensions > Essential Studio<sup style="font-size:70%">&reg;</sup> for WinForms > Add Syncfusion<sup style="font-size:70%">&reg;</sup> Item…** in Visual Studio.

	![Choose Add Syncfusion<sup style="font-size:70%">&reg;</sup> Item option from menu](Item-Template-images/Add-item.png)


4.	The Syncfusion<sup style="font-size:70%">&reg;</sup> WinForms Item Template wizard will be launched as follows.

	![Syncfusion<sup style="font-size:70%">&reg;</sup> WinForms Item template Components](Item-Template-images/Add-Syncfusion-ui.png)

5.	Select the WinForms Components from the Component list within your WinForms Item Template. The features associated with the selected Component will be presented. From here, 		choose the specific features that are essential for your project.

6.	Choose an assembly reference option such as GAC location, Essential Studio<sup style="font-size:70%">&reg;</sup> installed location, or NuGet packages to specify where the required Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies 	are added to the project.

	N> If the Syncfusion<sup style="font-size:70%">&reg;</sup> Essential WindowsForm build is installed, the Installed location and GAC options will be enabled. Without installing the Syncfusion<sup style="font-size:70%">&reg;</sup> Essential WindowsForm setup, use the NuGet option. The GAC option will not be available when using the Syncfusion<sup style="font-size:70%">&reg;</sup> WinForms Components in a .NET Core application. The Version drop-down lists the installed WinForms versions.

7.  Click **Add**, and a pop-up will appear providing information about adding Component **files** and **NuGet/Assemblies** details.

	![Syncfusion<sup style="font-size:70%">&reg;</sup> WinForms Item template details](Item-Template-images/Add-Syncfusion-item-3.png)	

8.	Click **OK** to incorporate the chosen Components into the WinForms application, along with the necessary Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies.

	![Syncfusion<sup style="font-size:70%">&reg;</sup> WinForms Item template Gallery](Item-Template-images/Add-Syncfusion-item-details.png)

9.	Then, Syncfusion<sup style="font-size:70%">&reg;</sup> licensing registration required message box will be shown if you installed the trial setup or NuGet packages since Syncfusion<sup style="font-size:70%">&reg;</sup> introduced the 			licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio<sup style="font-size:70%">&reg;</sup> release. Navigate to the [help topic](https://help.Syncfusion.com/common/essential-studio/licensing/license-key#how-to-generate-Syncfusion-license-key), which is shown in the licensing message box to generate and register the Syncfusion<sup style="font-size:70%">&reg;</sup> license key to 		your project. Refer to this [blog](https://blog.Syncfusion.com/post/Whats-New-in-2018-Volume-2-Licensing-Changes-in-the-1620x-Version-of-Essential-Studio.aspx) post 	 for understanding the licensing changes introduced in Essential Studio<sup style="font-size:70%">&reg;</sup>.

    ![Syncfusion<sup style="font-size:70%">&reg;</sup> WinForms Item template Gallery](Item-Template-images/Syncfusion-Item-Template-Gallery-7.png)