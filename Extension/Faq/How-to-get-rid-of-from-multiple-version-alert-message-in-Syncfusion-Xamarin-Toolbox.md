---
layout: post
title: Get rid of from multiple version alert message in Xamarin Toolbox | Extension | Syncfusion
description: how to get rid of from multiple version alert message when drag and drop a Syncfusion Xamarin component from Syncfusion Xamarin Toolbox?
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Get rid of from multiple version alert message in Xamarin Toolbox

When drag and drop a Syncfusion Xamarin control from Syncfusion Xamarin Toolbox in a project with multiple version NuGet packages which is already installed, two types of alert message will be displayed based on the following  scenarios:

* Same NuGet with multiple version installed.
* Different NuGet with multiple version installed.

## Same NuGet with multiple version installed

Following alert message will be displayed when multiple version of the same Syncfusion Xamarin NuGet package (e.g.,  Syncfusion.Xamarin.SfChart v16.1.0.xx and v16.2.0.xx) was found to be already installed in your project. Recommend to maintain the same version NuGet reference.

![Syncfusion Xamarin toolbox alert message when multiple version of the same Syncfusion Xamarin NuGet package already installed in the project](Alert-message-in-Syncfusion-Xamarin-Toolbox_images\Same-NuGet-Multiple-Version-Installed.jpg)

Hence, uninstall the multiple version of same Syncfusion Xamarin NuGet package (e.g.,  Syncfusion.Xamarin.SfChart) installed and re-install the single version of Syncfusion Xamarin NuGet package (e.g., Syncfusion.Xamarin.SfChart v16.2.0.xx) by manually and add the required control render code snippet to your project.

## Different NuGet with multiple version installed

Following alert message will be displayed when different Syncfusion Xamarin NuGet packages are installed with multiple version in your project. Hence, not aware of which version of Syncfusion NuGet package need to install in your project.

![Syncfusion Xamarin toolbox alert message when different Syncfusion Xamarin NuGet packages are installed with multiple version in the project](Alert-message-in-Syncfusion-Xamarin-Toolbox_images\Diferent-NuGet-Multiple-Version-Installed.jpg)

So, manually install all the required version Syncfusion Xamarin NuGet packages in the same version to your project and Drag the required control from the Syncfusion Xamarin Toolbox and Drop the render code snippet in the XAML file of your project. Please refer the [help link](https://help.syncfusion.com/extension/xamarin-extension/toolbox) to use the Syncfusion Xamarin Toolbox.




