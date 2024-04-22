---
layout: post
title: Get rid of from multiple version alert in Syncfusion Toolbox
description: how to get rid of from multiple version alert message when drag and drop a Syncfusion component from Syncfusion Toolbox?
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Get rid of from multiple version alert message in Syncfusion Toolbox

When dragging and dropping a Syncfusion control from either the **Syncfusion Xamarin Toolbox or the Syncfusion .NET MAUI Toolbox** into a project containing multiple versions of NuGet packages that are already installed, two types of alert message will be displayed based on the following scenarios:

* Same NuGet with multiple version installed.
* Different NuGet with multiple version installed.

## Same NuGet with multiple version installed

Following alert message will be displayed if multiple versions of the same Syncfusion NuGet package (e.g., Syncfusion.Xamarin.SfChart **v24.1.xx** and **v24.2.xx**(xamarin) / Syncfusion.MAUI.Buttons **v24.1.xx** and **24.2.xx**(maui)) are found already installed in your project. Recommend maintaining the same version NuGet reference.

![Syncfusion Xamarin toolbox alert message when multiple version of the same Syncfusion Xamarin NuGet package already installed in the project](Alert-message-in-Syncfusion-Xamarin-Toolbox_images\Same-NuGet-Multiple-Version-Installed.jpg)

To resolve this, follow the steps below,
1.	Uninstall the multiple versions of the same Syncfusion NuGet package currently installed in your project. 
2.	Now manually reinstall a single version of the Syncfusion NuGet package (e.g., Syncfusion.Xamarin.SfChart **v24.2.xx**(xamarin)  / Syncfusion.MAUI.Buttons **v24.2.xx** (maui)) and add the necessary control render code snippet to your project.


## Different NuGet with multiple version installed

Following alert message will be displayed when different versions of Syncfusion NuGet packages are installed in your project. Hence, not aware of which version of Syncfusion NuGet package need to install in your project.

![Syncfusion Xamarin toolbox alert message when different Syncfusion Xamarin NuGet packages are installed with multiple version in the project](Alert-message-in-Syncfusion-Xamarin-Toolbox_images\Diferent-NuGet-Multiple-Version-Installed.jpg)

To resolve this, manually install all the required versions of Syncfusion NuGet packages in the same version to your project. Then, drag the required Syncfusion component from the Syncfusion Toolbox (Xamarin/.NET MAUI) and drop the render code snippet in the XAML file of your project. Please refer to the following help topics to use the Syncfusion Toolbox:

1. [Xamarin ToolBox](https://help.syncfusion.com/extension/xamarin-extension/toolbox)
2. [.NET MAUI ToolBox](https://help.syncfusion.com/maui/visual-studio-integration/toolbox-control)



