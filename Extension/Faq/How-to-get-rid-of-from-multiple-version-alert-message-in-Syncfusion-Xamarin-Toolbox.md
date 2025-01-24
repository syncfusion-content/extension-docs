---
layout: post
title: Get rid of from multiple version alert in Syncfusion  Toolbox
description: how to get rid of from multiple version alert message when drag and drop a Syncfusion  component from Syncfusion Toolbox?
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Get rid of the Multiple Version Alert Messages in Syncfusion<sup style="font-size:70%">&reg;</sup>  Toolbox

When dragging and dropping a Syncfusion<sup style="font-size:70%">&reg;</sup>  control from either the **Syncfusion Xamarin Toolbox or the Syncfusion<sup style="font-size:70%">&reg;</sup>  .NET MAUI Toolbox** into a project containing multiple versions of NuGet packages that are already installed, two types of alert message will be displayed based on the following scenarios:

* Same NuGet with multiple versions installed.
* Different NuGet with multiple versions installed.

## Same NuGet with multiple versions installed

The following alert message will be displayed if multiple versions of the same Syncfusion<sup style="font-size:70%">&reg;</sup>  NuGet package (e.g., Syncfusion.Xamarin.SfChart **v24.1.xx** and **v24.2.xx**(xamarin) / Syncfusion.MAUI.Buttons **v24.1.xx** and **24.2.xx**(Maui)) are already installed in your project. Recommend maintaining the same version NuGet reference.

![Syncfusion Xamarin toolbox alert message when multiple version of the same Syncfusion<sup style="font-size:70%">&reg;</sup>  Xamarin NuGet package already installed in the project](Alert-message-in-Syncfusion-Xamarin-Toolbox_images\Same-NuGet-Multiple-Version-Installed.jpg)

To resolve this, follow these steps:
1.	Uninstall the multiple versions of the same Syncfusion<sup style="font-size:70%">&reg;</sup>  NuGet package currently installed in your project. 
2.	Now, manually reinstall a single version of the Syncfusion<sup style="font-size:70%">&reg;</sup>  NuGet package (e.g., Syncfusion.Xamarin.SfChart **v24.2.xx**(xamarin)  / Syncfusion.MAUI.Buttons **v24.2.xx** (Maui)) and add the necessary control render code sample to your project.

## Different NuGet with multiple versions installed

The following alert message will be displayed when different versions of Syncfusion<sup style="font-size:70%">&reg;</sup>  NuGet packages are installed in your project. Hence, you are not aware of which version of the Syncfusion<sup style="font-size:70%">&reg;</sup>  NuGet package you need to install in your project.

![Syncfusion Xamarin toolbox alert message when different Syncfusion<sup style="font-size:70%">&reg;</sup>  Xamarin NuGet packages are installed with multiple version in the project](Alert-message-in-Syncfusion-Xamarin-Toolbox_images\Diferent-NuGet-Multiple-Version-Installed.jpg)

To resolve this, manually install all the required versions of Syncfusion<sup style="font-size:70%">&reg;</sup>  NuGet packages in the same version of your project. Then, drag the required Syncfusion<sup style="font-size:70%">&reg;</sup>  component from the Syncfusion<sup style="font-size:70%">&reg;</sup>  Toolbox (Xamarin/.NET MAUI) and drop the render code snippet in the XAML file of your project. Please refer to the following help topics to use the Syncfusion<sup style="font-size:70%">&reg;</sup>  Toolbox:

1. [Xamarin ToolBox](https://help.syncfusion.com/extension/xamarin-extension/toolbox)
2. [.NET MAUI ToolBox](https://help.syncfusion.com/maui/visual-studio-integration/toolbox-control)



