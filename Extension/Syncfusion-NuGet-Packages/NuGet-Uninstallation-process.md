---
layout: post
title: NuGet Uninstallation process | Extension | Syncfusion
description: Describing the nuget uninstallation process using NuGet Package Manager dialog and Package Manager console window
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# NuGet Uninstallation process


## NuGet Uninstallation by using NuGet Package Manager

You can uninstall already installed Syncfusion NuGet packages from project using the following steps via NuGet Package Manager dialog.

1. Right-click on Project and select **Manage NuGet Packages** option. 

   ![Installed/Uninstallation Process packages details in NuGet Package Manager dialog](nuget-package-extension-uninstallation-process-package-details.png)
   
2. Select the **Installed** tab from NuGet Package Manager dialog and you can see the installed Syncfusion NuGet packages list by giving the Syncfusion keyword in search.

   ![Installed/Uninstallation packages details in NuGet Package Extension Manager dialog](nuget-package-extension-uninstallation-process-details-dialog.png)

3. Uninstall the Syncfusion NuGet packages which are not required for the project. 

   ![Installed/Uninstalled Process packages details in NuGet Package Extension Manager dialog](nuget-uninstallation-process_images/nuget-package-extension-uninstallation-process-manager-dialog.png)

N> You cannot uninstall the dependent package because of the package being referred in other NuGet Packages. It removes Project Reference and package from the project location.

4. If you don't want to uninstall the dependent NuGet packages when uninstall the Syncfusion NuGet packages, you can select the **Ignore Dependencies** option to ignore the uninstallation for dependent packages.

   ![Installed/Uninstallation packages details in NuGet Package Extension Manager dialog](nuget-uninstallation-process_images/nuget-package-extension-uninstallation-process-manager-dialog-details.png)

## NuGet Uninstallation by using Package Manager Console

You can uninstall already installed Syncfusion NuGet packages from project using the following steps via Package Manager Console window.

1. Select the **Tools-> NuGet Package Manager-> Package Manager Console**.

2. Run the following command to uninstall the specified Syncfusion NuGet Package with the package name. 

   uninstall-package {package name} –RemoveDependencies

   Example: uninstall-package Syncfusion.SfChart.WPF –RemoveDependencies
      
   ![NuGet package uninstallation log in NuGet Package Extension Manager Console window](nuget-package-extension-uninstallation-process-console-window.png)

3. You can uninstall the dependent NuGet package alone even if other NuGet packages depend on it by using the below command.

   uninstall-package {package name} -Force

   Example: uninstall-package Syncfusion.Shared.WPF -Force

   ![NuGet package Extension Uninstallation log in Package Manager Console window](nuget-package-extension-uninstallation-process-log.png)   