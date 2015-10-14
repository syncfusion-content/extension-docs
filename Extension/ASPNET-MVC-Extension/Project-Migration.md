---
layout: post
title: Project Migration | Extension | Syncfusion
description: Project Migration
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Project Migration

Project Migration is a Visual Studio add-in that helps migrate the existing Syncfusion ASP.NET MVC (Web), Syncfusion ASP.NET MVC (Mobile) Or Syncfusion ASP.NET MVC (Classic) project from one Syncfusion version to another Syncfusion version.

Syncfusion ASP.NET MVC and ASP.NET MVC (Classic) Project Migration Utility is included here,

* Essential Studio for Enterprise Edition with the platforms ASP.NETMVC or ASP.NET MVC(Classic)
* Essential Studio for ASP.NET MVC
* Essential Studio for ASP.NET MVC (Classic)

**NOTE******

This is not applicable from v.12.1.0.43 to v.13.1.0.30. The Syncfusion ASP.NET MVC and ASP.NET MVC (Classic) Project Migration Utilities are excluded from MVC Extension setup and integrated into Essential Studio ASP.NET MVC and ASP.NET MVC (Classic) platforms.

## ASP.NET MVC (Classic) Conversion\Migration:

By default, the Syncfusion ASP.NET MVC Extensions are configured in Visual Studio. When you want the ASP.NET MVC (Classic) extension, you can install it from the installed location.

Project Conversion and Migration (ASP.NET MVC(Classic):

Location: __{____Drive____}\____Program__ __Files__ __(____x86____)\____Syncfusion____\____Essential__ __Studio____\<____Version____>\____Utilities____\____Extensions____\____ASP____.____NET__ __MVC____\____Project__ __Conversion__

For Example – VS2013: __C____:\____Program__ __Files__ __(____x86____)\____Syncfusion____\____Essential__ __Studio____\____13____.____2____.____0____.____18____\____Utilities____\____Extensions____\____ASP____.____NET__ __MVC____\____Project__ __Conversion____\____4____.____5____.____1____\____Syncfusion__ __Web__ __(____Classic____)__ __Conversion__ __and__ __Migration____.____vsix__

## Migrate Syncfusion MVC Project

The following steps help you migrate from one version to another version of your existing Syncfusion ASP.NET MVC application.

1. Right-click on Syncfusion MVC Project and select Syncfusion VS Extensions. Choose Migrate the project to another version.

![http://help.syncfusion.com/extension/aspnet-mvc-extension/Migrate-Syncfusion-Project_images/Migrate-Syncfusion-Project_img1.png](Migrate-Syncfusion-Project_images/ProjectMigration_img1.jpeg)


2. The Project Migration window appears. You can choose the required Syncfusion version that is installed in the machine that is either Syncfusion ASP.NET 
MVC or Syncfusion ASP.NET MVC (Classic).

![](Migrate-Syncfusion-Project_images/ProjectMigration_img2.jpeg)


3. The Project Migration window allows you to configure the following options:
      i. Essential Studio Version: Select any version from the list of Installed Versions.
      ii. Backup: The option Backup copies the original project into the Backup folder in the same project location before migration.
      iii. Assemblies From: The option Assemblies from add the assembly to project from the following locations.
1. Added From GAC - Refer the assemblies from the Global Assembly Cache
2. Added from Installed Location - Refer the assemblies from the Syncfusion Installed locations.

4. Press the Migrate button corresponding to the Syncfusion References, CSS, Script files and Web.Config version changes to update it in the project.
