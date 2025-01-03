---
layout: post
title: Syncfusion Troubleshooter | Extension | Syncfusion
description: Syncfusion Troubleshooter is Visual Studio extension to troubleshoot the configuration issues in Syncfusion assembly reference, webconfig entries in projects.
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Troubleshoot the project

The Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will be installed in Visual Studio along with Syncfusion<sup style="font-size:70%">&reg;</sup> Essential Studio<sup style="font-size:70%">&reg;</sup> setup installation. The Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter can be done the below items,

1. Report the Configuration issues.  

2. Apply the solution

## Report the Configuration issues

The following steps help you to utilize the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter by Visual Studio. 

1. To open Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter Wizard, follow either one of the options below: 
   
   **Option 1:**  
   Open an existing Syncfusion<sup style="font-size:70%">&reg;</sup> Application, choose **Syncfusion<sup style="font-size:70%">&reg;</sup> menu**. Then select corresponding platform menu and click **Troubleshoot…**

   ![Syncfusion Troubleshooter via Syncfusion menu](SyncfusionTroubleshooter_images/Syncfusion_Menu_Troubleshooter.png)

   N> In Visual Studio 2019, Syncfusion<sup style="font-size:70%">&reg;</sup> menu available under Extension in Visual Studio menu.

   **Option 2:**  
   Right-click the Project file in Solution Explorer, then select the command **Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter…** Refer to the following screenshot for more information. 

   ![Syncfusion Troubleshooter add-in](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img1.jpeg)

2. Now it’s analyze the project and it will report the project configuration issues of Syncfusion<sup style="font-size:70%">&reg;</sup> controls in the Troubleshooter dialog if any issues found. If the project doesn’t have any configuration issue, the dialog box will show there is no configuration changes required in following areas,

     * Syncfusion<sup style="font-size:70%">&reg;</sup> assembly references.

     * Syncfusion<sup style="font-size:70%">&reg;</sup> Web.config entries.

     * Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet Packages. 

   ![No configuration changes required dialog box](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img2.jpeg)

I> The Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter command will be visible only for Syncfusion<sup style="font-size:70%">&reg;</sup> projects that means the project should contain Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies or Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet packages referred.

Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter handles the below project configuration issues, 

1. Assembly Reference Issues.

2. Web.config Issues (for Web applications).

3. NuGet related Issues.

### Assembly Reference Issues

The Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter deals with below assembly reference issues in Syncfusion<sup style="font-size:70%">&reg;</sup> Projects. 

1. Dependent assemblies are missing for referred assemblies from project. 

   **For Instance:**  If “Syncfusion.Tools.WPF” assembly referred in project and “Syncfusion.Shared.WPF” (dependent of Syncfusion.Tools.WPF) not referred in project, Syncfusion Troubleshooter will be shown dependent assembly missing.

   ![Dependent assemblies missing issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img3.jpg)

2. Syncfusion<sup style="font-size:70%">&reg;</sup> assembly version mismatched. Compare to all Syncfusion<sup style="font-size:70%">&reg;</sup> assembly’s versions are in same project. If found any Syncfusion<sup style="font-size:70%">&reg;</sup> assembly version inconsistency, Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will be shown Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies version mismatched. 

   **For Instance:**  If “Syncfusion.Tools.WPF” assembly (v15.2450.0.43) referred in project, but other Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies referred assembly version is v15.2450.0.40.  Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will be shown Syncfusion<sup style="font-size:70%">&reg;</sup> assembly version mismatched.

   ![Assembly version mismatched issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img4.jpg)

3. Framework version mismatching (Syncfusion<sup style="font-size:70%">&reg;</sup> Assemblies) with project’s .NET Framework version. Find the supported .NET Framework details for Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies in below link,

   <https://help.syncfusion.com/common/essential-studio/assembly-information#supported-framework-version-for-essential-studio-assemblies> 

   **For Instance:** The.NET Framework of the application is v4.5 and “Syncfusion.Tools.WPF” assembly (v15.2400.0.43 & .NET Framework version 4.0) referred in same application. The Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will be shown Syncfusion<sup style="font-size:70%">&reg;</sup> assembly .NET Framework version is incompatible with project’s .NET Framework version.

   ![Target Framework version of application](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img5.jpg)

   ![Framework mismatch issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img6.jpg)

### Web.config Issues (for Web applications)

The Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter deals with below web.config issues in Syncfusion<sup style="font-size:70%">&reg;</sup> web projects. 

1. Syncfusion<sup style="font-size:70%">&reg;</sup> assembly entry version mismatched. Each Syncfusion<sup style="font-size:70%">&reg;</sup> assembly entry version/.NET Framework version will be compared with corresponding referred Syncfusion<sup style="font-size:70%">&reg;</sup> assembly in the application.

   **For Instance:** If “Syncfusion.EJ.Export” assembly (v15.2450.0.46) referred in project, But “Syncfusion.EJ.Export” assembly entry version (v15.2450.0.33) in Web.config file. Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will be shown Syncfusion<sup style="font-size:70%">&reg;</sup> assembly entry version mismatched.

   ![Syncfusion reference assembly entry version mismatched issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img7.jpg)

2. Multiple version and Duplicate Syncfusion<sup style="font-size:70%">&reg;</sup> assembly entry. Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will show the duplicate assembly entry when Syncfusion<sup style="font-size:70%">&reg;</sup> assembly entry presented in Web.config which is not referred in project or multiple Syncfusion<sup style="font-size:70%">&reg;</sup> assembly entry in Web.config for same Syncfusion<sup style="font-size:70%">&reg;</sup> assembly. 

   **For Instance:** If project have “Syncfusion.EJ.Pivot” assembly (v15.2450.0.43) entry in Web.config file, But “Syncfusion.EJ.Pivot” assembly not referred in project. Syncfusion Troubleshooter will be show Duplicate assembly entry.
 
   ![Duplicate Syncfusion reference assembly entry issue shown in Troubleshooter wizard ](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img8.jpg)

   **For Instance:** If project Multiple “Syncfusion.EJ” assembly (v15.2400.0.46 && v15.2460.0.46) entry with mismatched assembly version/.NET Framework version in Web.config, Syncfusion Troubleshooter will show the Duplicate assembly entry and Multiple Syncfusion<sup style="font-size:70%">&reg;</sup> assembly entries.

   ![Multiple version Syncfusion reference assembly entry issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img9.jpg)

3. Namespace entry missing. If any Syncfusion<sup style="font-size:70%">&reg;</sup> namespaces are missing in Web.config that is related to referred Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies in project, Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will show namespace entry is missing.

   **For Instance:** If “Syncfusion.EJ.MVC” assembly (v15.2450.0.46) referred in project and “Syncfusion.MVC.EJ” namespace entry missing in Web.config file, Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will show Syncfusion<sup style="font-size:70%">&reg;</sup> namespace entry missing.
   
   ![Namespace entry missing issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img10.jpg)

4. Namespace entry version mismatched. If any Namespace entry version (assembly version) mismatched with corresponding referred assembly version in ASP.NET Web Application, Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will be shown Namespace entry version mismatched.

   **For Instance:** If “Syncfusion.EJ” assembly (v15.2450.0.46) referred in project and “Syncfusion.JavaScript.DataVisualization” Namespace entry version (v15.2450.0.43) in Web.config file. Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will be show Syncfusion<sup style="font-size:70%">&reg;</sup> namespace entry version mismatched.

   ![Syncfusion namespace entry version mismatched issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img11.jpg)

5. HTTP/Server handler entry mismatched. HTTP/Server handler entry version compare to corresponding referred assembly version in project. If any Syncfusion<sup style="font-size:70%">&reg;</sup> HTTP/Server handler entry version mismatched, Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will show HTTP/Server handler entry mismatched.  

   **For Instance:** If “Syncfusion.EJ.” assembly (v15.2450.0.46) referred in project, But “Syncfusion.JavaScript.ImageHandler” HTTP/Server handler entry version (v15.2450.0.43) in Web.config file. Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will be show Syncfusion<sup style="font-size:70%">&reg;</sup> HTTP/Server handler entry version mismatched.
   
   ![Syncfusion HTTP/Server handler entry mismatched issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img12.jpg)

### NuGet Issues

The Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter deals with below NuGet package related issues in Syncfusion<sup style="font-size:70%">&reg;</sup> projects. 

1. Multiple versions of Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet Packages are installed. If Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet Package version is differ from other Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet Package version, Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will be shown Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet package version is mismatched. 

   **For Instance:** Syncfusion.Web,Base package installed multiple version(v15.2.0.43 & v15.2.0.46), Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will be shown Syncfusion<sup style="font-size:70%">&reg;</sup> package version mismatched.
 
   ![Syncfusion NuGet Packages version mismatched issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img13.jpg)

2. Installed Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet package’s Framework version is differing from the project’s .NET Framework version.

   **For Instance:** Syncfusion.Calculate.Base NuGet package version(v15.2.0.46 with 4.0 Framework) installed in project, But the project .NET Framework version is 4.5. So, Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will be show Syncfusion<sup style="font-size:70%">&reg;</sup> package Framework version is mismatched.
  
   ![Syncfusion NuGet packages Framework version mismatched issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img14.jpg)

3. Dependent NuGet package of the installed Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet packages is missing.

   **For Instance:** If install Syncfusion.Calculate.WPF NuGet package alone in project, Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will show the Syncfusion.Calculate.Base dependent NuGet package missing.
 
   ![Dependent NuGet package missing issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img15.jpg)

I> Internet connection is required to restore the missing dependent packages. If no Internet is available, the dependent packages will not be restored.

## Apply the solution

1. Once the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter dialog loads, check the corresponding check box of the issue which you need to resolve. Then click the "Fix Issue(s)" button. 

   ![Syncfusion Troubleshooter wizard with project configuration issues](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img16.jpeg)

2. A dialog appears, which will ask to take a backup of the project before perform the troubleshooting process. If you need to backup the project before troubleshooting click “Yes” button. 

   ![Syncfusion Troubleshooter backup dialog](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img17.jpeg)

3. Wait for a while, the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter is being resolve the selected issues. Once the troubleshooting process completed, there will be a status message in the Visual Studio status bar as “Troubleshooting process completed successfully.” 

   ![Syncfusion Troubleshooter process success status message in visual studio status bar](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img18.jpeg)

4. Then, Syncfusion<sup style="font-size:70%">&reg;</sup> licensing registration required message box will be shown as follow, if you are installed the trial setup or NuGet packages since Syncfusion<sup style="font-size:70%">&reg;</sup> introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio<sup style="font-size:70%">&reg;</sup> release. Please navigate to the [help topic](https://help.syncfusion.com/common/essential-studio/licensing/overview#how-to-generate-syncfusion-license-key) which is shown in the licensing message box to generate and register the Syncfusion<sup style="font-size:70%">&reg;</sup> license key to your project. Refer to this [blog](https://blog.syncfusion.com/post/whats-new-in-2018-volume-2-licensing-changes-in-the-1620x-version-of-essential-studio.aspx) post for understanding the licensing changes introduced in Essential Studio<sup style="font-size:70%">&reg;</sup>.   

   ![Syncfusion license registration required information dialog in Syncfusion Troubleshooter](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img19.jpeg)