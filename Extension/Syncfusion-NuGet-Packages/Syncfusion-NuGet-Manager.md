---
layout: post
title: Syncfusion NuGet Manager | Extension | Syncfusion
description: Syncfusion NuGet Package Manager is the utility that allows you to add, remove and update the Syncfusion NuGet sources (available platforms) to NuGet Package Manager
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet Package Manager

## Overview

Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet Package Manager is the utility that allows you to add, remove and update the Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet sources (available platforms) to NuGet Package Manager. Download the Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet Manager utility from [here](http://www.syncfusion.com/downloads/support/directtrac/general/ze/SyncfusionNuGetManager-2143130196).

## Add Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet Package sources 

The following steps directs you to add the Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet Package sources from Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet Manager. 

1. Run the SyncfusionNuGetManager.exe from Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet Manager extracted location. 

   ![Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet Manager extracted location](SyncfusionNuGetManager_images/SyncfusionNuGetManager-img1.png)

2. Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet Manager Window will be opened.

   ![Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet Manager main window](SyncfusionNuGetManager_images/SyncfusionNuGetManager-img2.png)

3. Select the required platforms needed to be configured from “Select platforms to add” (Left side of the window) column and click Add>> button.

   ![Selected platforms NuGet feed configure option in Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet Manager](SyncfusionNuGetManager_images/SyncfusionNuGetManager-img3.png)

4. Now selected platforms will be added under “Selected platforms to remove” (Right side of the window) column. Click “Configure” button to add the required Syncfusion<sup style="font-size:70%">&reg;</sup> Package sources to NuGet Package Manager.

   ![Selected platforms NuGet feed remove option in Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet Manager](SyncfusionNuGetManager_images/SyncfusionNuGetManager-img4.png)

5. Once Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet Manager added the Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet sources, the changes will be reflected in package sources of your Visual Studio. 

   ![NuGet package manager dialog with Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet feeds](SyncfusionNuGetManager_images/SyncfusionNuGetManager-img5.png)

## Remove Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet Package sources 

1. If any configured Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet Package sources are no longer required, Select the unwanted platforms from “Select platforms to remove” (Right side of the window) column and click <<Remove button. 

   ![Remove option in Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet Manager to remove the already configured Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet feed](SyncfusionNuGetManager_images/SyncfusionNuGetManager-img6.png)   

2. Now selected platforms will be added under “Selected platforms to add” (Left side of the window) column. Click “Configure” button to remove the required Syncfusion<sup style="font-size:70%">&reg;</sup> Package sources to NuGet Package Manager.

3. Once Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet Manager removed the Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet sources, the changes will be reflected in NuGet.config file of your machine and updated the same in available package sources of your Visual Studio. 

## Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet Manager command line

The following steps directs you to use the Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet Manager from command line.

1. Open Windows Command Prompt in Administrator Mode.

2. Navigate to SyncfusionNuGetManager.exe from Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet Manager extracted location.  

3. Run SyncfusionNuGetManager.exe with required platforms arguments. Refer the below table for platform as arguments to configure the Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet Packages sources. 

   ![Command to add Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet feed](SyncfusionNuGetManager_images/SyncfusionNuGetManager-img8.jpeg)

**Add**

To add the Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet feed link with below command.

SyncfusionNuGetManager.exe Add [platform key]

Example:SyncfusionNuGetManager.exe Add

**Update**

To update the new feed\local NuGet location with update command.

SyncfusionNuGetManager.exe Update {platform key} {source feed link\Local NuGet location}

Example:SyncfusionNuGetManager.exe Update JavaScript “D:\Syncfusion\JavaScript NuGet”

**Remove**

To remove the configured Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet by below command.

SyncfusionNuGetManager.exe Remove [platform  key] [local NuGet Location]

Example:SyncfusionNuGetManager.exe Remove JavaScript

**Platform Key table**

Here the list of keyword for platform keys to access. 

<table>
 <thead>
  <tr>
    <th>Platform</th>
    <th>Platform Keys</th>
  </tr>
 </thead>
 <tbody>
  <tr>
   <td>ASP.NET</td>
   <td>Aspnet /asp.net</td>
  </tr>
  <tr>
    <td>ASP.NET MVC</td>
    <td>Aspnetmvc /asp.net mvc /mvc</td>
  </tr>
  <tr>
    <td>ASP.NET Core</td>
    <td>Aspnetcore /asp.net core /core</td>
  </tr>
  <tr>
   <td>JavaScript</td>
   <td>JavaScript/JS</td>
  </tr>
  <tr>
    <td>Xamarin</td>
     <td>Xamarin</td>
  </tr>
  <tr>
   <td>UWP</td>
   <td>Uwp /universalwindows</td>
 </tr>
 <tr>
   <td>WPF<br/></td>
   <td>Wpf</td>
 </tr>
 <tr>
   <td>Windows Forms</td>
   <td>WindowsForms /Winforms/WF</td>
 </tr>
 <tr>
  <td>Windows Phone</td>
  <td>WindowsPhone /wp /winphone</td>
 </tr>
 <tr>
  <td>WinRT</td>
  <td>WinRT</td>
 </tr>
 <tr>
  <td>Universal</td>
  <td>Universal</td>
 </tr>
 <tr>
  <td>LightSwitchHTML</td>
  <td>LightSwitch</td>
 </tr>
 <tr>
  <td>Silverlight</td>
  <td>Silverlight</td>
 </tr>
 </tbody>
</table>

4. Once Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet Manager removed the Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet sources, the changes will be reflected in NuGet.config file of your machine and updated the same in available package sources of your Visual Studio. 

   ![NuGet package manager dialog with Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet feeds](SyncfusionNuGetManager_images/SyncfusionNuGetManager-img5.png)

