---
layout: post
title: Toolbox Configuration | Wpf | Syncfusion
description: This section provides information regarding all the Syncfusion Essential Studio utilities and its usage
platform: extension
control: Essential Studio
documentation: ug
---

# Toolbox Configuration

The Syncfusion<sup style="font-size:70%">&reg;</sup> Toolbox Installer utility incorporates the Syncfusion<sup style="font-size:70%">&reg;</sup> WPF components into the Visual Studio .NET toolbox.

N> Toolbox configuration support is not available for the Visual Studio Express Edition. However, you can manually configure the Syncfusion<sup style="font-size:70%">&reg;</sup> controls into the Visual Studio Express Toolbox. To do so, refer the [Manual Toolbox Configuration](https://help.Syncfusion.com/common/faq/how-to-configure-the-toolbox-of-visual-studio-manually).

If the <b>“Configure Syncfusion<sup style="font-size:70%">&reg;</sup> Controls in Visual Studio”</b> checkbox is selected from the installer UI while installing the Syncfusion<sup style="font-size:70%">&reg;</sup> WPF installer, Syncfusion<sup style="font-size:70%">&reg;</sup> components will be automatically configured in the Visual Studio toolbox.

To add the Syncfusion<sup style="font-size:70%">&reg;</sup> WPF components via the Syncfusion<sup style="font-size:70%">&reg;</sup> Toolbox Installer, perform the following steps:

1. To launch Toolbox configuration utility, follow either one of the options below:

   **Option 1:**   
   Open the Syncfusion<sup style="font-size:70%">&reg;</sup> Control Panel, click **Add On and Utilities > Toolbox Installer**.
   
   ![Add On and Utilities](Toolbox-Configuration_images/Toolbox-Configuration_img1.png)
   
   **Option 2:**  
   Click **Syncfusion<sup style="font-size:70%">&reg;</sup> menu** and choose **Essential Studio<sup style="font-size:70%">&reg;</sup> for WPF > Toolbox Configuration...** in **Visual Studio**

   ![Toolbox Installer via Syncfusion<sup style="font-size:70%">&reg;</sup> menu](Toolbox-Configuration_images/Syncfusion_Menu_Toolbox.png)

   N> From Visual Studio 2019, Syncfusion<sup style="font-size:70%">&reg;</sup> menu is available under Extensions in Visual Studio menu.

   ![Toolbox Installer via Syncfusion<sup style="font-size:70%">&reg;</sup> menu](Toolbox-Configuration_images/Syncfusion_Menu_Toolbox_2019.png)

2. Toolbox Installer will be opened.

   ![Toolbox Installer](Toolbox-Configuration_images/Toolbox-Configuration_img2.png)

   The following options are available in Toolbox Configuration:

   * Install VS2005 – Configures Framework 2.0 Syncfusion<sup style="font-size:70%">&reg;</sup> controls in VS 2005 toolbox.
   * Install VS2008 – Configures Framework 3.5 Syncfusion<sup style="font-size:70%">&reg;</sup> controls in VS 2008 toolbox.
   * Install VS2010 – Configures Framework 4.0 Syncfusion<sup style="font-size:70%">&reg;</sup> controls in VS 2010 toolbox.
   * Install VS2012 – Configures Framework 4.5 Syncfusion<sup style="font-size:70%">&reg;</sup> controls in VS 2012 toolbox.
   * Install VS2013 – Configures Framework 4.5.1 Syncfusion<sup style="font-size:70%">&reg;</sup> controls in VS 2013 toolbox.
   * Install VS2015 – Configures Framework 4.6 Syncfusion<sup style="font-size:70%">&reg;</sup> controls in VS 2015 toolbox.
   * Install VS2017 – Configures Framework 4.6 Syncfusion<sup style="font-size:70%">&reg;</sup> controls in VS 2017 toolbox.
   * Install VS2019 – Configures Framework 4.6 Syncfusion<sup style="font-size:70%">&reg;</sup> controls in VS 2019 toolbox
   * Install VS2022 – Configures Framework 4.6 Syncfusion<sup style="font-size:70%">&reg;</sup> controls in VS 2022 toolbox.
   * Install VS2026 – Configures Framework 4.6.2 Syncfusion<sup style="font-size:70%">&reg;</sup> controls in VS 2026 toolbox.

    N> You can also configure Syncfusion<sup style="font-size:70%">&reg;</sup> controls from a lower version Framework assembly to higher version of Visual Studio.
   
3. The successful configuration of Toolbox is indicated by an Information message. Click OK.

   ![Toolbox Installer](Toolbox-Configuration_images/Toolbox-Configuration_img3.png)
   
   
   N> * You must reset the toolbox, when the installed controls are not reflected properly in the Toolbox. 
   * This tool configures only the controls that are located under {Installed Location}\Assemblies\{Framework version}. 

   
## Configuring toolbox for WPF .NET 5.0 projects

From 2021 Volume 1,Syncfusion<sup style="font-size:70%">&reg;</sup> started providing toolbox support for the WPF .NET 5.0 framework in Visual Studio. After installing the Syncfusion<sup style="font-size:70%">&reg;</sup> WPF installer, Syncfusion<sup style="font-size:70%">&reg;</sup> controls will be automatically configured in the Visual Studio toolbox for WPF.NET 5.0 projects.

N> * Syncfusion<sup style="font-size:70%">&reg;</sup> included this toolbox support for .NET 5.0 WPF platform from 2021 Volume 1 release version v19.1.0.54 only. 
* If the project was created with TargetFramework.NET Core 3.1 and then changed to.NET 5.0 after installing the WPF setup, you must restart Visual Studio to see the Syncfusion<sup style="font-size:70%">&reg;</sup> controls in the Visual Studio Toolbox. 
* Visual Studio 2019 16.7 Preview 2 and later is required.

### Upgrading the Syncfusion<sup style="font-size:70%">&reg;</sup> WPF toolbox .NET 5.0 controls without installing the build

You can upgrade the Syncfusion<sup style="font-size:70%">&reg;</sup> WPF toolbox for .NET 5.0 control with NuGet packages downloaded from [nuget.org](https://www.nuget.org/). Download ["Syncfusion.UI.WPF.NET"](https://www.nuget.org/packages/Syncfusion.UI.WPF.NET/) package from nuget.org in your machine.

Use the following steps to add the Syncfusion<sup style="font-size:70%">&reg;</sup> WPF controls through Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet packages:

**step 1:** 
   
   Extract **"Syncfusion<sup style="font-size:70%">&reg;</sup>.UI.WPF.NET"** package by using the below commands.
	
   Open Command prompt from nuget.exe path and run the following commands
	
   **Command:** {nuget.exe path} add "F:\Syncfusion\Syncfusion.UI.WPF.NET.{version}.nupkg" -Source "F:\Syncfusion\Expand" -expand
	
   **Example:** F:\Syncfusion>nuget.exe add "F:\Syncfusion\Syncfusion.UI.WPF.NET.19.1.0.50.nupkg" -Source "F:\Syncfusion" -expand
	
   ![Toolbox Installer](Toolbox-Configuration_images/NET_50_Toolbox_Package_Extract.png)
	
**step 2:** 

   Open **"Syncfusion<sup style="font-size:70%">&reg;</sup> Toolbox for WPF.config"** file from the following location.
	
   **Location:** "C:\Program Files (x86)\NuGet\Config\Syncfusion Toolbox for WPF.config"
	
   ![Toolbox Installer](Toolbox-Configuration_images/NET_50_Toolbox.png)

   Or you can create this file in the same location by using the XML format given below
    
   {% tabs %}
   {% highlight XML %}
     <?xml version="1.0" encoding="utf-8"?>
      <configuration>
        <fallbackPackageFolders>
          <add key="Syncfusion<sup style="font-size:70%">&reg;</sup> Toolbox Local NuGet Packages {version}" value="F:\Syncfusion" />
        </fallbackPackageFolders>
      </configuration>
   {% endhighlight %}
   {% endtabs %}
	
**step 3:**
   
   Update extracted Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet package path in **value** attribute.
	
   **Example:**
   ![Toolbox Installer](Toolbox-Configuration_images/NET_50_Toolbox_Package_update.png)
	
**step 4:**
   
   Now restart the Visual Studio 2019 to get populate the latest Syncfusion<sup style="font-size:70%">&reg;</sup> controls in Toolbox.


## Configuring toolbox for .NET Core 3.1 projects

The Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet packages must be installed in the WPF .NET Core application before the Syncfusion<sup style="font-size:70%">&reg;</sup> toolbox can be configured. The corresponding NuGet packages Syncfusion<sup style="font-size:70%">&reg;</sup> components will be configured in Visual Studio toolbox after installing the Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet packages in.NET Core application. 

Please refer the documentation [link](../../wpf/installation/install-nuget-packages), to learn more about how to use the Syncfusion<sup style="font-size:70%">&reg;</sup> components using the Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet packages in .NET Core application.
   
