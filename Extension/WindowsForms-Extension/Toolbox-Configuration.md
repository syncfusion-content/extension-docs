---
layout: post
title: Toolbox Configuration | WinForms | Syncfusion
description: This section provides information regarding all the Syncfusion Essential Studio utilities and its usage
platform: extension
control: Essential Studio
documentation: ug
---

# Toolbox Configuration

The Syncfusion<sup style="font-size:70%">&reg;</sup> Toolbox utility adds the Syncfusion<sup style="font-size:70%">&reg;</sup> WinForms controls into the Visual Studio .NET toolbox.

N> Visual Studio Express Edition does not support toolbox configuration. However, you can manually configure the Syncfusion<sup style="font-size:70%">&reg;</sup> controls into the Visual Studio Express Toolbox. To do so, refer the [Manual Toolbox Configuration](https://help.Syncfusion.com/common/faq/how-to-configure-the-toolbox-of-visual-studio-manually).

Syncfusion<sup style="font-size:70%">&reg;</sup> controls will be automatically configured in the Visual Studio toolbox, while installing the Syncfusion<sup style="font-size:70%">&reg;</sup> Windows Forms installer, if the <b>“Configure Syncfusion<sup style="font-size:70%">&reg;</sup> Controls in Visual Studio”</b> checkbox is selected from installer UI.

Use the following steps to add the Syncfusion<sup style="font-size:70%">&reg;</sup> WinForms controls through the Syncfusion<sup style="font-size:70%">&reg;</sup> Toolbox Installer:

1. To launch Toolbox configuration utility, follow either one of the options below:

   **Option 1:**   
   To open the Syncfusion<sup style="font-size:70%">&reg;</sup> Control Panel, click **Add On and Utilities > Toolbox Installer**.
   
   ![Add On and Utilities](Toolbox-Configuration_images/Toolbox-Configuration_img1.png)
   
   **Option 2:**  
   Click **Syncfusion<sup style="font-size:70%">&reg;</sup> menu** and choose **Essential Studio<sup style="font-size:70%">&reg;</sup> for WinForms > Toolbox Configuration...** in **Visual Studio**.

   ![Toolbox Installer via Syncfusion<sup style="font-size:70%">&reg;</sup> menu](Toolbox-Configuration_images/Syncfusion_Menu_Toolbox.png)

   N> From Visual Studio 2019, Syncfusion<sup style="font-size:70%">&reg;</sup> menu is available under Extensions in Visual Studio menu.

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
   * Install VS2022 – Configures Framework 4.6 Syncfusion<sup style="font-size:70%">&reg;</sup> controls in VS 2019 toolbox
   
    N> You can also configure Syncfusion<sup style="font-size:70%">&reg;</sup> controls from a lower version Framework assembly to higher version of Visual Studio.
   
3. The successful configuration of Toolbox is indicated by an Information message. Click **OK**.

   ![Toolbox Installer](Toolbox-Configuration_images/Toolbox-Configuration_img3.png)
   
   
   N> * You must reset the toolbox, when the installed controls are not reflected properly in the Toolbox. * This tool configures only the controls that are located under {Installed Location}\Assemblies\{Framework version}.
   
