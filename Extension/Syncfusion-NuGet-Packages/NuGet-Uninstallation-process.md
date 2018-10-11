---
layout: post
title: NuGet Uninstallation process | Extension | Syncfusion
description: Describing the nuget uninstallation process using NuGet Package Manager and Package Manager console
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# NuGet Uninstallation process


## NuGet Uninstallation

You can uninstall the installed packages from WPF project using the following steps via Manage NuGet Packages dialog.

1. Right-click Project and select Manage NuGet Packages. 
2. Select the Installed packages and see the installed packages list.
3. Uninstall packages that are not required for the project. 

![Installed packages details in NuGet Package Manager dialog](NuGet-Uninstallation_images/NuGet-Uninstallation-img1.png)

N> You cannot uninstall the dependent package because of the package being referred in other NuGet Packages. It removes Project Reference and package from the project location.

## Uninstall from Package Manager Console

To uninstall the Syncfusion NuGet Packages by Package Manager Console, follow the given steps.

1. Select the Tools-> NuGet Package Manager-> Package Manager Console.
2. Run the following command to uninstall the specified NuGet Package with the package name. 

   uninstall-package {package name} –RemoveDependencies

   Example: uninstall-package Syncfusion.Chart.WPF45 –RemoveDependencies

3. Refer to the following screenshot for more information.
   
   
   
   ![NuGet package uninstallation log in Package Manager Console window](Uninstall-from-Package-Manager-Console_images/Uninstall-from-Package-Manager-Console-img1.png)



