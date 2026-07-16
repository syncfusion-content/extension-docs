---
layout: post
title: Troubleshooting | WinForms | Syncfusion
description: Syncfusion Troubleshooter is a Visual Studio extension to troubleshoot the configuration issues in Syncfusion assembly references and web.config entries in projects.
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Troubleshoot the project

Troubleshoot the project with the Syncfusion<sup style="font-size:70%">&reg;</sup> configuration and apply the fix for issues such as adding a Syncfusion<sup style="font-size:70%">&reg;</sup> assembly to the project with the wrong .NET Framework version, or missing any Syncfusion<sup style="font-size:70%">&reg;</sup> dependent assembly of a referred assembly. The Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter is capable of performing the following tasks:

* Report the configuration issues.
* Apply the solution.

## Report the Configuration issues

The following steps help you use the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter in Visual Studio.

> Before using the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter for WinForms, check whether the **WinForms Extensions - Syncfusion<sup style="font-size:70%">&reg;</sup>** is installed or not in the Visual Studio Extension Manager by clicking on Tools -> Extensions and Updates -> Installed for Visual Studio 2017 or lower, and for Visual Studio 2019 or later by clicking on Extensions -> Manage Extensions -> Installed. If this extension is not installed, please install the extension by following the steps from the [download and installation](https://help.Syncfusion.com/windowsforms/visual-studio-integration/vs2019-extensions/download-and-installation/) help topic.

1. To open the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter Wizard, follow either one of the options below: 
   
   **Option 1:**  
   Open an existing Syncfusion<sup style="font-size:70%">&reg;</sup> WinForms Application, click **Syncfusion<sup style="font-size:70%">&reg;</sup> Menu** and choose **Essential Studio<sup style="font-size:70%">&reg;</sup> for WinForms > Troubleshoot…** in Visual Studio.

   ![Syncfusion Troubleshooter via Syncfusion menu](SyncfusionTroubleshooter_images/Syncfusion_Menu_Troubleshooter.png)

   N> From Visual Studio 2019, Syncfusion<sup style="font-size:70%">&reg;</sup> menu is available under Extensions in Visual Studio menu.

   **Option 2:**  
   Right-click the Project file in Solution Explorer, then select the command Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter…

   ![Syncfusion Troubleshooter add-in](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img1.jpeg)

2. The project will now be analyzed, and if any Syncfusion<sup style="font-size:70%">&reg;</sup> project configuration errors are discovered, they will be reported in the Troubleshooter dialog. If there are no configuration issues with the project, the dialog box will indicate that no modifications are required in the following areas:

* Syncfusion<sup style="font-size:70%">&reg;</sup> assembly references.
* Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet Packages. 
* Syncfusion<sup style="font-size:70%">&reg;</sup> Toolbox Configuration.

   ![No configuration changes required dialog box](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img2.png)

I> The Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter command will be visible only for Syncfusion<sup style="font-size:70%">&reg;</sup> projects, which means Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies or Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet packages should be referred to in the project.

The Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter handles the following project configuration issues: 

1. Assembly Reference Issues.

2. NuGet related Issues.

3. Toolbox Configuration Issues.

### Assembly Reference Issues

The Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter deals with the following assembly reference issues in Syncfusion<sup style="font-size:70%">&reg;</sup> Projects. 

1. Dependent assemblies are missing for referred assemblies in the project. 

   **For Instance:** If the "Syncfusion.Grid.Windows" assembly is referred in the project and "Syncfusion.Shared.Windows" (a dependent of Syncfusion.Grid.Windows) is not referred in the project, the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will show a dependent assembly as missing.

   ![Dependent assemblies missing issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img3.png)

2. Syncfusion<sup style="font-size:70%">&reg;</sup> assembly version mismatched. Compare all the Syncfusion<sup style="font-size:70%">&reg;</sup> assembly versions in the same project. If any Syncfusion<sup style="font-size:70%">&reg;</sup> assembly version inconsistency is found, the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will show the Syncfusion<sup style="font-size:70%">&reg;</sup> assembly version mismatched. 

   **For Instance:** If the "Syncfusion.Tools.Windows" assembly (v15.2450.0.40) is referred in the project, but the other referred Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies have an assembly version of v15.2450.0.43, the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will show the Syncfusion<sup style="font-size:70%">&reg;</sup> assembly version mismatched.

   ![Assembly version mismatched issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img4.png)

3. Framework version mismatching (Syncfusion<sup style="font-size:70%">&reg;</sup> Assemblies) with the project's .NET Framework version. Find the supported .NET Framework details for Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies in the following link:

   <https://help.Syncfusion.com/common/essential-studio/assembly-information#supported-framework-version-for-essential-studio-assemblies> 

   **For Instance:** The .NET Framework of the application is v4.5 and the "Syncfusion.Tools.Windows" assembly (v17.1460.0.38 & .NET Framework version 4.6) is referred in the same application. The Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will show that the Syncfusion<sup style="font-size:70%">&reg;</sup> assembly .NET Framework version is incompatible with the project's .NET Framework version.

   ![Target Framework version of application](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img5.png)

   ![Framework mismatch issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img6.png)

### NuGet Issues

The Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter deals with the following NuGet package related issues in Syncfusion<sup style="font-size:70%">&reg;</sup> projects. 

1. Multiple versions of Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet packages are installed. If a Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet package version differs from another Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet package version, the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will show the Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet package version as mismatched. 

   **For Instance:** Syncfusion<sup style="font-size:70%">&reg;</sup> WinForms platform packages are installed in multiple versions (v16.4.0.54 & v17.1.0.38); the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will show the Syncfusion<sup style="font-size:70%">&reg;</sup> package version mismatched.
 
   ![Syncfusion NuGet Packages version mismatched issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img7.png)

2. The installed Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet package's Framework version differs from the project's .NET Framework version.

   **For Instance:** The Syncfusion<sup style="font-size:70%">&reg;</sup>.SfBulletGraph.Windows40 NuGet package version (v15.2.0.17 with 4.0 Framework) is installed in the project, but the project's .NET Framework version is 4.5. So, the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will show the Syncfusion<sup style="font-size:70%">&reg;</sup> package Framework version as mismatched.
  
   ![Syncfusion NuGet packages Framework version mismatched issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img8.png)

3. A dependent NuGet package of the installed Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet packages is missing.

   **For Instance:** If you install the Syncfusion<sup style="font-size:70%">&reg;</sup>.Chart.Windows NuGet package alone in the project, the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will show the Syncfusion<sup style="font-size:70%">&reg;</sup>.Chart.Base and other dependent NuGet packages as missing.
 
   ![Dependent NuGet package missing issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img9.png)

I> Internet connection is required to restore the missing dependent packages. If internet is not available, the dependent packages will not be restored.

### Toolbox Configuration Issues

The Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter deals with the following Toolbox Configuration related issues in Syncfusion<sup style="font-size:70%">&reg;</sup> projects. 

1. If the Syncfusion<sup style="font-size:70%">&reg;</sup> Toolbox is not installed/configured for the project's .NET Framework version, the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will show the Syncfusion<sup style="font-size:70%">&reg;</sup> Toolbox .NET Framework version as mismatched. 

   **For Instance:** The project's .NET Framework version is 4.5, but the Syncfusion<sup style="font-size:70%">&reg;</sup> Toolbox is configured only with 4.6 framework assemblies in the corresponding Visual Studio, so the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will show the Syncfusion<sup style="font-size:70%">&reg;</sup> Toolbox framework version as mismatched.
 
   ![Syncfusion Toolbox Framework version mismatched issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img10.png)

2. If the Syncfusion<sup style="font-size:70%">&reg;</sup> Toolbox configured version differs from the latest Syncfusion<sup style="font-size:70%">&reg;</sup> assembly reference version or NuGet package version in the same project, the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will show the Syncfusion<sup style="font-size:70%">&reg;</sup> Toolbox version as mismatched.

   **For Instance:** If the latest Syncfusion<sup style="font-size:70%">&reg;</sup> assembly reference version is v17.1.0.38, but the Toolbox assemblies are configured with v17.1.0.32, the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will show the Syncfusion<sup style="font-size:70%">&reg;</sup> Toolbox version as mismatched.
  
   ![Syncfusion Toolbox version mismatched issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img11.png)

## Apply the solution

1. After loading the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter dialog, check the corresponding check box of the issue to be resolved. Then click the “Fix Issue(s)” button. 

   ![Syncfusion Troubleshooter wizard with project configuration issues](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img12.png)

2. A dialog appears, which will ask you to take a backup of the project before performing the troubleshooting process. If you need to back up the project before troubleshooting, click the "Yes" button.

   ![Syncfusion Troubleshooter backup dialog](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img13.jpeg)

3. Wait for a while; the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter is resolving the selected issues. After the troubleshooting process is completed, there will be a status message in the Visual Studio status bar as "Troubleshooting process completed successfully".

   ![Syncfusion Troubleshooter process success status message in visual studio status bar](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img14.jpeg)

4. Then, a Syncfusion<sup style="font-size:70%">&reg;</sup> licensing registration required message box will be shown if you installed the trial setup or NuGet packages, since Syncfusion<sup style="font-size:70%">&reg;</sup> introduced the licensing system from the 2018 Volume 2 (v16.2.0.41) Essential Studio<sup style="font-size:70%">&reg;</sup> release. Navigate to the  [help topic](https://help.Syncfusion.com/common/essential-studio/licensing/license-key#how-to-generate-Syncfusion-license-key), which is shown in the licensing message box to generate and register the Syncfusion<sup style="font-size:70%">&reg;</sup> license key to your project. Refer to this [blog](https://blog.Syncfusion.com/post/Whats-New-in-2018-Volume-2-Licensing-Changes-in-the-1620x-Version-of-Essential-Studio.aspx) post to understand the licensing changes introduced in Essential Studio<sup style="font-size:70%">&reg;</sup>.   

   ![Syncfusion license registration required information dialog in Syncfusion Troubleshooter](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img15.jpeg)