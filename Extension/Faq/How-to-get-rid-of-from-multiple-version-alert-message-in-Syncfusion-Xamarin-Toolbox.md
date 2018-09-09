---
layout: post
title: How to get rid of from multiple version alert message in Syncfusion Xamarin Toolbox | Extension | Syncfusion
description: how to get rid of from multiple version alert message in syncfusion xamarin toolbox?
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# How to get rid of from multiple version alert message in Syncfusion Xamarin Toolbox?

When drag and drop a Syncfusion Xamarin control from Syncfusion Xamarin Toolbox in a project with multiple version NuGet packages which is already installed, two types of alert message will be displayed based on the following  scenarios:

* Same NuGet with multiple version installed.
* Different NuGet with multiple version installed.

## Same NuGet with multiple version installed

Following alert message will be displayed when multiple version of the same Syncfusion Xamarin NuGet package (e.g.,  Syncfusion.Xamarin.SfChart v16.1.0.xx and v16.2.0.xx) was found to be already installed in your project. Recommend to maintain the same version NuGet reference.

![](Alert-message-in-Syncfusion-Xamarin-Toolbox_images\Same_NuGet_Multiple_Version_Installed.jpg)

Hence, uninstall the multiple version of same Syncfusion Xamarin NuGet package (e.g.,  Syncfusion.Xamarin.SfChart) installed and re-install the single version of Syncfusion Xamarin NuGet package (e.g., Syncfusion.Xamarin.SfChart v16.2.0.xx) by manually and add the required control render code snippet to your project.

## Different NuGet with multiple version installed

Following alert message will be displayed when different Syncfusion Xamarin NuGet packages are installed with multiple version in your project. Hence, not aware of which version of Syncfusion NuGet package need to install in your project.

![](Alert-message-in-Syncfusion-Xamarin-Toolbox_images\Diferent_NuGet_Multiple_Version_Installed.jpg)

So, install the required version Syncfusion Xamarin NuGet package by manually and add the render code snippet to your project.




