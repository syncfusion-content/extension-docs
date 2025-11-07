---
layout: post
title: Troubleshooting | WinForms | Syncfusion
description: Syncfusion Troubleshooter is Visual Studio extension to troubleshoot the configuration issues in Syncfusion assembly reference, webconfig entries in projects.
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Troubleshoot the project

Troubleshoot the project with the Syncfusion<sup style="font-size:70%">&reg;</sup> configuration and apply the fix, such as adding a Syncfusion<sup style="font-size:70%">&reg;</sup> assembly to the project with the wrong .NET Framework version or missing any Syncfusion<sup style="font-size:70%">&reg;</sup> dependent assembly of a referred assembly. The Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter is capable of performing the following tasks:

* Report the Configuration issues.  
* Apply the solution.

## Report the Configuration issues

The following steps help you to utilize the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter by Visual Studio. 

> Before use the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter for WinForms, check whether the **WinForms Extensions - Syncfusion<sup style="font-size:70%">&reg;</sup>** installed or not in Visual Studio Extension Manager by clicking on the Tools -> Extensions and Updates -> Installed for Visual Studio 2017 or lower and for Visual Studio 2019 by clicking on the Extensions -> Manage Extensions -> Installed.If this extension not installed, please install the extension by follow the steps from the [download and installation](https://help.Syncfusion.com/windowsforms/visual-studio-integration/vs2019-extensions/download-and-installation/) help topic.

1. To open Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter Wizard, follow either one of the options below: 
   
   **Option 1:**  
   Open an existing Syncfusion<sup style="font-size:70%">&reg;</sup> WinForms Application, Click **Syncfusion<sup style="font-size:70%">&reg;</sup> Menu** and choose **Essential Studio<sup style="font-size:70%">&reg;</sup> for WinForms > Troubleshoot…** in Visual Studio.

   ![Syncfusion Troubleshooter via Syncfusion<sup style="font-size:70%">&reg;</sup> menu](SyncfusionTroubleshooter_images/Syncfusion_Menu_Troubleshooter.png)

   N> From Visual Studio 2019, Syncfusion<sup style="font-size:70%">&reg;</sup> menu is available under Extensions in Visual Studio menu.

   **Option 2:**  
   Right-click the Project file in Solution Explorer, then select the command Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter…

   ![Syncfusion Troubleshooter add-in](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img1.jpeg)

2. Analyze the project now, and if any Syncfusion<sup style="font-size:70%">&reg;</sup> controls project configuration errors are discovered, they will be reported in the Troubleshooter dialog.  If there are no configuration issues with the project, the dialog box will indicate that no modifications are required in the following areas:

* Syncfusion<sup style="font-size:70%">&reg;</sup> assembly references.
* Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet Packages. 
* Syncfusion<sup style="font-size:70%">&reg;</sup> Toolbox Configuration.

   ![No configuration changes required dialog box](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img2.png)

I> The Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter command will be visible only for Syncfusion<sup style="font-size:70%">&reg;</sup> projects that means Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies or Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet packages should be referred in to the project.

The Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter handles the following project configuration issues: 

1. Assembly Reference Issues.

2. NuGet related Issues.

3. Toolbox Configuration Issues.

### Assembly Reference Issues

The Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter deals with the following assembly reference issues in Syncfusion<sup style="font-size:70%">&reg;</sup> Projects. 

1. Dependent assemblies are missing for referred assemblies from project. 

   **For Instance:**  If “Syncfusion.Grid.Windows” assembly referred in project and “Syncfusion.Shared.Windows” (dependent of Syncfusion.Grid.Windows) not referred in project, the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will show dependent assembly missing.

   ![Dependent assemblies missing issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img3.png)

2. Syncfusion<sup style="font-size:70%">&reg;</sup> assembly version mismatched. Compare to all Syncfusion<sup style="font-size:70%">&reg;</sup> assembly’s versions in the same project. If found any Syncfusion<sup style="font-size:70%">&reg;</sup> assembly version inconsistency, the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will show Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies version mismatched. 

   **For Instance:**  If “Syncfusion.Tools.Windows” assembly (v15.2450.0.40) referred in project, but other Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies referred assembly version is v15.2450.0.43. Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will be shown Syncfusion<sup style="font-size:70%">&reg;</sup> assembly version mismatched.

   ![Assembly version mismatched issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img4.png)

3. Framework version mismatching (Syncfusion<sup style="font-size:70%">&reg;</sup> Assemblies) with project’s .NET Framework version. Find the supported .NET Framework details for Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies in the following link,

   <https://help.Syncfusion.com/common/essential-studio/assembly-information#supported-framework-version-for-essential-studio-assemblies> 

   **For Instance:** The.NET Framework of the application is v4.5 and “Syncfusion.Tools.Windows” assembly (v17.1460.0.38 & .NET Framework version 4.6) referred in same application. The Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will show Syncfusion<sup style="font-size:70%">&reg;</sup> assembly .NET Framework version is incompatible with project’s .NET Framework version.

   ![Target Framework version of application](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img5.png)

   ![Framework mismatch issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img6.png)

### NuGet Issues

The Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter deals with the following NuGet package related issues in Syncfusion<sup style="font-size:70%">&reg;</sup> projects. 

1. Multiple versions of Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet Packages are installed. If Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet Package version is differ from other Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet Package version, the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will show Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet package version is mismatched. 

   **For Instance:** Syncfusion<sup style="font-size:70%">&reg;</sup> WinForms platform packages installed multiple version (v16.4.0.54 & v17.1.0.38), Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will be shown Syncfusion<sup style="font-size:70%">&reg;</sup> package version mismatched.
 
   ![Syncfusion NuGet Packages version mismatched issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img7.png)

2. Installed Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet package’s Framework version is differing from the project’s .NET Framework version.

   **For Instance:** Syncfusion<sup style="font-size:70%">&reg;</sup>.SfBulletGraph.Windows40 NuGet package version(v15.2.0.17 with 4.0 Framework) installed in project, But the project .NET Framework version is 4.5. So, the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will show Syncfusion<sup style="font-size:70%">&reg;</sup> package Framework version is mismatched.
  
   ![Syncfusion NuGet packages Framework version mismatched issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img8.png)

3. Dependent NuGet package of the installed Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet packages is missing.

   **For Instance:** If install Syncfusion<sup style="font-size:70%">&reg;</sup>.Chart.Windows NuGet package alone in project, the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will show the Syncfusion<sup style="font-size:70%">&reg;</sup>.Chart.Base and other dependent NuGet package missing.
 
   ![Dependent NuGet package missing issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img9.png)

I> Internet connection is required to restore the missing dependent packages. If internet is not available, the dependent packages will not be restored.

### Toolbox Configuration Issues

The Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter deals with the following Toolbox Configuration related issues in Syncfusion<sup style="font-size:70%">&reg;</sup> projects. 

1. If the project .NET Framework version is not installed/configured Syncfusion<sup style="font-size:70%">&reg;</sup> Toolbox, the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will show Syncfusion<sup style="font-size:70%">&reg;</sup> Toolbox .NET Framework version is mismatched. 

   **For Instance:** The project .NET Framework version is 4.5 and Syncfusion<sup style="font-size:70%">&reg;</sup> Toolbox is not configured 4.6 framework assemblies only in corresponding Visual Studio, the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will show Syncfusion<sup style="font-size:70%">&reg;</sup> Toolbox framework version mismatched.
 
   ![Syncfusion Toolbox Framework version mismatched issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img10.png)

2. If Syncfusion<sup style="font-size:70%">&reg;</sup> Toolbox configured version is differed from latest Syncfusion<sup style="font-size:70%">&reg;</sup> assembly reference version or NuGet package version in same project, the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will show Syncfusion<sup style="font-size:70%">&reg;</sup> Toolbox version is mismatched.

   **For Instance:** If latest Syncfusion<sup style="font-size:70%">&reg;</sup> assembly reference version is v17.1.0.38 but Toolbox assemblies configured v17.1.0.32, the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will show Syncfusion<sup style="font-size:70%">&reg;</sup> Toolbox version mismatched.
  
   ![Syncfusion Toolbox version mismatched issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img11.png)

## Apply the solution

1. After loading the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter dialog, check the corresponding check box of the issue to be resolved. Then click the “Fix Issue(s)” button. 

   ![Syncfusion Troubleshooter wizard with project configuration issues](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img12.png)

2. A dialog appears, which will ask to take a backup of the project before performing the troubleshooting process. If you need to backup the project before troubleshooting, click “Yes” button. 

   ![Syncfusion Troubleshooter backup dialog](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img13.jpeg)

3. Wait for a while, the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter is resolving the selected issues. After the troubleshooting process completed, there will be a status message in the Visual Studio status bar as “Troubleshooting process completed successfully”.

   ![Syncfusion Troubleshooter process success status message in visual studio status bar](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img14.jpeg)

4. Then, Syncfusion<sup style="font-size:70%">&reg;</sup> licensing registration required message box will be shown, if you installed the trial setup or NuGet packages since Syncfusion<sup style="font-size:70%">&reg;</sup> introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio<sup style="font-size:70%">&reg;</sup> release. Navigate to the  [help topic](https://help.Syncfusion.com/common/essential-studio/licensing/license-key#how-to-generate-Syncfusion-license-key), which is shown in the licensing message box to generate and register the Syncfusion<sup style="font-size:70%">&reg;</sup> license key to your project. Refer to this [blog](https://blog.Syncfusion.com/post/Whats-New-in-2018-Volume-2-Licensing-Changes-in-the-1620x-Version-of-Essential-Studio.aspx) post for understanding the licensing changes introduced in Essential Studio<sup style="font-size:70%">&reg;</sup>.   

   ![Syncfusion license registration required information dialog in Syncfusion Troubleshooter](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img15.jpeg)