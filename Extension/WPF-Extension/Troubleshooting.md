---
layout: post
title: Troubleshooting | Wpf | Syncfusion
description: Syncfusion Troubleshooter is a Visual Studio extension to troubleshoot the configuration issues in Syncfusion assembly reference entries in WPF projects.
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Troubleshoot the WPF project

Troubleshoot the project with the Syncfusion<sup style="font-size:70%">&reg;</sup> configuration and apply the fix, such as a wrong .NET Framework version of a Syncfusion<sup style="font-size:70%">&reg;</sup> assembly in the project or a missing Syncfusion<sup style="font-size:70%">&reg;</sup> dependent assembly of a referred assembly. The Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter can perform the following tasks:

* Report the configuration issues.
* Apply the solution.

## Report the Configuration issues

The steps below will assist you in using the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter in Visual Studio.

> Check whether the **WPF Extensions - Syncfusion<sup style="font-size:70%">&reg;</sup>** are installed in the Visual Studio Extension Manager. In Visual Studio 2017 or lower, go to **Tools -> Extensions and Updates -> Installed**. In Visual Studio 2019 and later, go to **Extensions -> Manage Extensions -> Installed**. If this extension is not installed, follow the steps from the [download and installation](download-and-installation) help topic to install it.

1. To open the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter wizard, follow one of the options below:

   **Option 1**
   Open an existing Syncfusion<sup style="font-size:70%">&reg;</sup> WPF application, click the **Syncfusion<sup style="font-size:70%">&reg;</sup> Menu**, and choose **Essential Studio<sup style="font-size:70%">&reg;</sup> for WPF > Troubleshoot…** in Visual Studio.

   ![Syncfusion Troubleshooter via Syncfusion menu](SyncfusionTroubleshooter_images/Syncfusion_Menu_Troubleshooter.png)

   N> From Visual Studio 2019 and later, the Syncfusion<sup style="font-size:70%">&reg;</sup> menu is available under **Extensions** in the Visual Studio menu.

   ![Syncfusion Troubleshooter via Syncfusion menu](SyncfusionTroubleshooter_images/Syncfusion_Menu_Troubleshooter_2019.png)

   **Option 2**
   Right-click the project file in **Solution Explorer** and select **Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter…** from the context menu.

   ![Syncfusion Troubleshooter add-in](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img1_2019.png)

2. Analyze the project now. If any Syncfusion<sup style="font-size:70%">&reg;</sup> control project configuration errors are discovered, they are reported in the Troubleshooter dialog. If there are no configuration issues with the project, the dialog box indicates that no modifications are required in the following areas:

   * Syncfusion<sup style="font-size:70%">&reg;</sup> assembly references.
   * Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet Packages.
   * Syncfusion<sup style="font-size:70%">&reg;</sup> Toolbox Configuration.

   ![No configuration changes required dialog box](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img2.png)

I> The Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter options are visible only for Syncfusion<sup style="font-size:70%">&reg;</sup> projects, which means the project should contain Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies or Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet packages referred.

The Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter handles the following project configuration issues:

1. Assembly Reference Issues.

2. NuGet-related Issues.

3. Toolbox Configuration Issues.

### Assembly Reference Issues

The Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter handles the assembly reference issues listed below in Syncfusion<sup style="font-size:70%">&reg;</sup> projects.

1. Dependent assemblies are missing for referred assemblies from the project.

   **For instance:** If the "Syncfusion.Chart.WPF" assembly is referred in the project and "Syncfusion.Shared.WPF" (dependent of Syncfusion.Chart.Base) is not referred in the project, the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will show that the dependent assembly is missing.

   ![Dependent assemblies missing issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img3.png)

2. The Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter compares all Syncfusion<sup style="font-size:70%">&reg;</sup> assembly versions in the same project. If any Syncfusion<sup style="font-size:70%">&reg;</sup> assembly version inconsistency is found, the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will show that the Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies versions are mismatched.

   **For instance:** If the "Syncfusion<sup style="font-size:70%">&reg;</sup>.Tools.WPF" assembly (v17.1.0.32) is referred in the project, but other Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies' referred assembly version is v17.1.0.38, the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will show that the Syncfusion<sup style="font-size:70%">&reg;</sup> assembly version is mismatched.

   ![Assembly version mismatched issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img4.png)

3. Framework version mismatching (Syncfusion<sup style="font-size:70%">&reg;</sup> Assemblies) with the project's .NET Framework version. Find the supported .NET Framework details for Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies in the following link:

   <https://help.syncfusion.com/common/essential-studio/assembly-information#supported-framework-version-for-essential-studio-assemblies>

   **For instance:** The .NET Framework of the application is v4.5 and the "Syncfusion.Tools.WPF" assembly (v17.1.0.38 & .NET Framework version 4.6) is referred in the same application. The Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will show that the Syncfusion<sup style="font-size:70%">&reg;</sup> assembly .NET Framework version is incompatible with the project's .NET Framework version.

   ![Target Framework version of application](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img5.jpg)

   ![Framework mismatch issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img6.png)

### NuGet Issues

The Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter addresses the following NuGet package-related issues in Syncfusion<sup style="font-size:70%">&reg;</sup> projects.

1. If the application has Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet packages in multiple versions, the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will show that the Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet package version is mismatched.

   **For instance:** Syncfusion<sup style="font-size:70%">&reg;</sup> WPF platform packages are installed in multiple versions (v16.4.0.54 & v17.1.0.38), so the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will show that the Syncfusion<sup style="font-size:70%">&reg;</sup> package version is mismatched.

   ![Syncfusion NuGet Packages version mismatched issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img7.png)

2. The installed Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet package's Framework version differs from the project's .NET Framework version.

   **For instance:** If the "Syncfusion.SfBulletGraph.WPF40" NuGet package version (v15.4.0.17 with 4.0 Framework) is installed in the project, but the project .NET Framework version is 4.5, the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will show that the Syncfusion<sup style="font-size:70%">&reg;</sup> package Framework version is mismatched.

   ![Syncfusion NuGet packages Framework version mismatched issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img8.png)

3. A dependent NuGet package of the installed Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet packages is missing.

   **For instance:** If you install the Syncfusion.Chart.WPF NuGet package alone in the project, the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will show that the Syncfusion.Chart.Base and other dependent NuGet packages are missing.

   ![Dependent NuGet package missing issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img9.png)

I> An internet connection is required to restore the missing dependent packages. If the internet is not available, the dependent packages will not be restored.

### Toolbox Configuration Issues

In Syncfusion<sup style="font-size:70%">&reg;</sup> projects, the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter addresses the following Toolbox Configuration issues.

1. If the project .NET Framework version's Syncfusion<sup style="font-size:70%">&reg;</sup> Toolbox is not installed or configured, the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will show that the Syncfusion<sup style="font-size:70%">&reg;</sup> Toolbox .NET Framework version is mismatched.

   **For instance:** If the latest Syncfusion<sup style="font-size:70%">&reg;</sup> assembly reference version is v17.1.0.38 but the Toolbox assemblies are configured to v17.1.0.32, the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will show that the Syncfusion<sup style="font-size:70%">&reg;</sup> Toolbox version is mismatched.

   ![Syncfusion Toolbox Framework version mismatched issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img10.png)

2. If the configured version of the Syncfusion<sup style="font-size:70%">&reg;</sup> Toolbox differs from the latest Syncfusion<sup style="font-size:70%">&reg;</sup> assembly reference version or NuGet package version in the same project, the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will indicate that the Syncfusion<sup style="font-size:70%">&reg;</sup> Toolbox version is mismatched.

   **For instance:** If the latest Syncfusion<sup style="font-size:70%">&reg;</sup> assembly reference version is v17.1.0.38 but the Toolbox assemblies are configured to v17.1.0.32, the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will show that the Syncfusion<sup style="font-size:70%">&reg;</sup> Toolbox version is mismatched.

   ![Syncfusion Toolbox version mismatched issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img11.png)

## Apply the solution

1. After loading the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter dialog, check the corresponding check box of the issue to be resolved. Then click the **"Fix Issue(s)"** button.

   ![Syncfusion Troubleshooter wizard with project configuration issues](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img12.png)

2. A dialog appears, asking you to take a backup of the project before performing the troubleshooting process. If you need to back up the project before troubleshooting, click the **"Yes"** button.

   ![Syncfusion Troubleshooter backup dialog](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img13.jpeg)

3. Wait while the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter resolves the selected issues. After the troubleshooting process is complete, a status message appears in the Visual Studio status bar: **"Troubleshooting process completed successfully"**.

   ![Syncfusion Troubleshooter process success status message in visual studio status bar](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img14.jpeg)

4. If you installed the trial setup or NuGet packages, the Syncfusion<sup style="font-size:70%">&reg;</sup> license registration message box is displayed, since Syncfusion<sup style="font-size:70%">&reg;</sup> introduced the licensing system in 2018 Volume 2 (v16.2.0.41) of the Essential Studio<sup style="font-size:70%">&reg;</sup> release. Navigate to the [help topic](https://help.syncfusion.com/common/essential-studio/licensing/license-key#how-to-generate-syncfusion-license-key) shown in the licensing message box to generate and register the Syncfusion<sup style="font-size:70%">&reg;</sup> license key for your project. Refer to this [blog post](https://blog.syncfusion.com/post/Whats-New-in-2018-Volume-2-Licensing-Changes-in-the-1620x-Version-of-Essential-Studio.aspx) to understand the licensing changes introduced in Essential Studio<sup style="font-size:70%">&reg;</sup>.

   ![Syncfusion license registration required information dialog in Syncfusion Troubleshooter](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img15.jpeg)