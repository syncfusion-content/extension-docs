---
layout: post
title: Syncfusion Troubleshooter | ASP.NET | Syncfusion
description: Syncfusion Troubleshooter is Visual Studio extension to troubleshoot the configuration issues in Syncfusion assembly reference, webconfig entries in projects.
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Troubleshoot the project

Troubleshoot the project with the Syncfusion<sup style="font-size:70%">&reg;</sup> configuration and apply the fix, such as wrong.NET Framework version of a Syncfusion<sup style="font-size:70%">&reg;</sup> assembly to the project or missing any Syncfusion<sup style="font-size:70%">&reg;</sup> dependent assembly of a referred assembly. The Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter can perform the following tasks:

* Report the Configuration issues.  

* Apply the solution

## Report the Configuration issues

The steps below will assist you in using the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter by Visual Studio.

> Before use the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter for ASP.NET Web Forms, check whether the **ASP.NET Web Forms Extensions - Syncfusion<sup style="font-size:70%">&reg;</sup>** installed or not in Visual Studio Extension Manager by clicking on the Tools -> Extensions and Updates -> Installed for Visual Studio 2017 or lower and for Visual Studio 2019 by clicking on the Extensions -> Manage Extensions -> Installed. 

1. To launch the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter Wizard, select one of the options below:
   
   **Option 1**  
   Open an existing Syncfusion<sup style="font-size:70%">&reg;</sup> ASP.NET Web Forms Application, Click **Syncfusion<sup style="font-size:70%">&reg;</sup> Menu** and choose **Essential Studio<sup style="font-size:70%">&reg;</sup> for ASP.NET Web Forms (EJ1) > Troubleshoot…** in Visual Studio.

   ![Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter via Syncfusion<sup style="font-size:70%">&reg;</sup> menu](SyncfusionTroubleshooter_images/Syncfusion_Menu_Troubleshooter.png)

   N> In Visual Studio 2019, Syncfusion<sup style="font-size:70%">&reg;</sup> menu is available under Extensions in Visual Studio menu.

   **Option 2**  
   Right-click the Project file in Solution Explorer, then select the command **Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter…**

   ![Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter add-in](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img1.png)

2. Now, analyze the project, and if any issues are discovered, it will report the project configuration issues of Syncfusion<sup style="font-size:70%">&reg;</sup> components in the Troubleshooter dialogue. If the project has no configuration issues, the dialogue box will indicate that no configuration changes are required in the following areas:

    * Syncfusion<sup style="font-size:70%">&reg;</sup> assembly references.

    * Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet Packages. 

    * Syncfusion<sup style="font-size:70%">&reg;</sup> Web.config Entries.

    * Syncfusion<sup style="font-size:70%">&reg;</sup> Script files.

    * Toolbox Configuration.

   ![No configuration changes required dialog box](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img2.png)

   I> The Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter command will be visible only for Syncfusion<sup style="font-size:70%">&reg;</sup> projects, which means the project must contain the referred Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies or NuGet packages.

   The Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter handles the following project configuration issues: 

   1. Assembly reference issues.

   2. NuGet related issues.

   3. Web.config entries related issues.

   4. Script file related issues.

   5. Toolbox Configuration issues.

### Assembly reference issues

The Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter handles the assembly reference issues listed below in Syncfusion<sup style="font-size:70%">&reg;</sup> Projects.

1. Dependent assemblies are missing for referred assemblies from project. 

   **For Instance:**  If the “Syncfusion.EJ.Pivot” assembly is referenced in the project but “Syncfusion.PivotAnalysis.Base” and other dependent assemblies of Syncfusion.EJ.Pivot are not referenced in the project, the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will report that the dependent assembly is missing.

   ![Dependent assemblies missing issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img3.png)

2. The Syncfusion<sup style="font-size:70%">&reg;</sup> assembly version is mismatched. In the same project, compare all Syncfusion<sup style="font-size:70%">&reg;</sup> assembly versions. If any Syncfusion<sup style="font-size:70%">&reg;</sup> assembly version inconsistency is discovered, the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will display the Syncfusion<sup style="font-size:70%">&reg;</sup> assembly’s version mismatch.

   **For Instance:** If the “Syncfusion.OfficeChart.Base” assembly (v15.2450.0.40) is referred to in the project, but the assembly version referred to by other Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies is v15.2450.0.43. The Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will display a mismatched Syncfusion<sup style="font-size:70%">&reg;</sup> assembly version.

   ![Assembly version mismatched issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img4.png)

3.	.NET Framework version mismatch (Syncfusion<sup style="font-size:70%">&reg;</sup> Assemblies) with project's .NET Framework version. The details for the supported .NET Framework for Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies can be found at the following link.

   <https://help.syncfusion.com/common/essential-studio/assembly-information#supported-framework-version-for-essential-studio-assemblies> 

   **For Instance:** The application's .NET Framework is v4.6, and the "Syncfusion.EJ.PdfViewer" assembly (v16.4400.0.42 & .NET Framework version 4.0) is referred to in the same application. The Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will indicate that the Syncfusion<sup style="font-size:70%">&reg;</sup> assembly's .NET Framework version is incompatible with the project's .NET Framework version.

   ![Target Framework version of application](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img5.png)

   ![Framework mismatch issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img6.png)

### NuGet issues

The Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter handles the following NuGet package issues in Syncfusion<sup style="font-size:70%">&reg;</sup> projects.

1. Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet Packages are installed in multiple versions. If one Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet Package version differs from another, the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will indicate that the Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet package version is mismatched.

   **For Instance:** If you have multiple versions of the Syncfusion<sup style="font-size:70%">&reg;</sup> Web platform packages installed (v16.4.0.54 and v17.1.0.38), the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will display Syncfusion<sup style="font-size:70%">&reg;</sup> package version mismatch.
 
   ![Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet Packages version mismatched issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img7.png)

2. Dependent NuGet package of the installed Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet packages is missing.

   **For Instance:** If you install the Syncfusion<sup style="font-size:70%">&reg;</sup> Web NuGet package in your project without any dependencies, the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will report that the Syncfusion.Compression.Base and other dependent NuGet packages are missing.
 
   ![Dependent NuGet package missing issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img8.png)

   I> To restore the missing dependent packages, an Internet connection is required. The dependent packages will not be restored if the internet is not available.

### Web.config issues

The Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter handles with Web.config entry-related issues in Syncfusion<sup style="font-size:70%">&reg;</sup> projects.

1. The version of the Syncfusion<sup style="font-size:70%">&reg;</sup> assembly entry was mismatched. Each Syncfusion assembly entry version/.NET Framework version will be compared to the application's corresponding referred Syncfusion<sup style="font-size:70%">&reg;</sup> assembly.

   **For Instance:** If the “Syncfusion.EJ.Pivot” assembly (v17.1450.0.38) is mentioned in the project, but the “Syncfusion.EJ.Pivot” assembly entry version (v16.4450.0.54) is mentioned in the Web.config file. The Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will display a mismatched Syncfusion<sup style="font-size:70%">&reg;</sup> assembly entry version.
 
   ![Syncfusion<sup style="font-size:70%">&reg;</sup> Toolbox Framework version mismatched issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img9.png)

2. Syncfusion<sup style="font-size:70%">&reg;</sup> assembly entry has multiple versions and is duplicated. When a Syncfusion<sup style="font-size:70%">&reg;</sup> assembly entry is presented in Web.config that is not referred to in the project, or when multiple Syncfusion<sup style="font-size:70%">&reg;</sup> assembly entries are presented in Web.config for the same Syncfusion<sup style="font-size:70%">&reg;</sup> assembly, Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will display the duplicate assembly entry.

   **For Instance:** If the project contains a “Syncfusion.EJ.Web” assembly (v17.1450.0.38) entry in the Web.config file, but the “Syncfusion.EJ.Web” assembly is not referred to in the project. Duplicate assembly entry will be displayed by Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter.
 
   ![Duplicate Syncfusion<sup style="font-size:70%">&reg;</sup> reference assembly entry issue shown in Troubleshooter wizard ](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img10.png)

   **For Instance:** If a project contains multiple “Syncfusion.EJ.Web” assembly entries (v16.4460.0.54 && v17.1460.0.38) with mismatched assembly version/.NET Framework version in Web.config, Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will display the Duplicate assembly entry and Multiple Syncfusion<sup style="font-size:70%">&reg;</sup> assembly entries.

   ![Multiple version Syncfusion<sup style="font-size:70%">&reg;</sup> reference assembly entry issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img11.png)

3. The version of the namespace entry was mismatched. If any Namespace entry version (assembly version) in ASP.NET Web Application is mismatched with the corresponding referred assembly version, Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will display Namespace entry version mismatched.

   **For Instance:** If the “Syncfusion.EJ” assembly (v17.1450.0.38) is referenced in the project and the “Syncfusion.JavaScript.DataVisualization” Namespace entry version (v16.4450.0.54) is referenced in the Web.config file. The Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will display a mismatched Syncfusion<sup style="font-size:70%">&reg;</sup> namespace entry version.
   
   ![Namespace entry missing issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img12.png)

4. Mismatch HTTP/Server handler entry. If any Syncfusion<sup style="font-size:70%">&reg;</sup> HTTP/Server handler entry version is mismatched when compared to the corresponding referred assembly version in the project, the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will show HTTP/Server handler entry mismatched.

   **For Instance:** If the “Syncfusion.EJ.” assembly (v17.1450.0.38) is mentioned in the project, but the “Syncfusion.JavaScript.ImageHandler” HTTP/Server handler entry version (v16.4450.0.54) is specified in the Web.config file. The Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will display a mismatched Syncfusion<sup style="font-size:70%">&reg;</sup> HTTP/Server handler entry version.
   
   ![Syncfusion<sup style="font-size:70%">&reg;</sup> HTTP/Server handler entry mismatched issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img13.png)

### Toolbox Configuration Issues

The Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter handles the Toolbox Configuration issues listed below in Syncfusion<sup style="font-size:70%">&reg;</sup> projects.

1. If the project's .NET Framework version is not installed/configured, the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will report that the Syncfusion<sup style="font-size:70%">&reg;</sup> Toolbox .NET Framework version is mismatched.

   **For Instance:** The .NET Framework version of the project is 4.5, and Syncfusion<sup style="font-size:70%">&reg;</sup> Toolbox is not installed. 4.6 framework assemblies only in the corresponding Visual Studio, the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will display Syncfusion<sup style="font-size:70%">&reg;</sup> Toolbox framework version mismatch.
 
   ![Syncfusion<sup style="font-size:70%">&reg;</sup> Toolbox Framework version mismatched issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img14.png)

2. If the configured version of Syncfusion<sup style="font-size:70%">&reg;</sup> Toolbox differs from the most recent Syncfusion<sup style="font-size:70%">&reg;</sup> assembly reference version or NuGet package version in the same project, the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will indicate that the Syncfusion<sup style="font-size:70%">&reg;</sup> Toolbox version is mismatch.

   **For Instance:** If the most recent Syncfusion<sup style="font-size:70%">&reg;</sup> assembly reference version is v17.1.0.38 but the Toolbox assemblies are configured with v17.1.0.32, the Syncfusion Troubleshooter will report Syncfusion<sup style="font-size:70%">&reg;</sup> Toolbox version mismatch.
  
   ![Syncfusion<sup style="font-size:70%">&reg;</sup> Toolbox version mismatched issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img15.png)

### Script file issues

The Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter handles the following Script file issues in Syncfusion<sup style="font-size:70%">&reg;</sup> projects.

1. The version of the Syncfusion<sup style="font-size:70%">&reg;</sup> script file is mismatch. Each Syncfusion<sup style="font-size:70%">&reg;</sup> script file version will be compared to the latest version of the corresponding referred Syncfusion<sup style="font-size:70%">&reg;</sup> assembly in the application.

   **For Instance:** If Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies (v17.1450.0.38) and Syncfusion<sup style="font-size:70%">&reg;</sup> script file (v16.4.0.54) are referenced in the project. The Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will display a Syncfusion<sup style="font-size:70%">&reg;</sup> script file version (v16.4.0.54) that is incompatible with the project's/package version of Syncfusion<sup style="font-size:70%">&reg;</sup> (v17.1.0.38).
 
   ![Syncfusion<sup style="font-size:70%">&reg;</sup> script file version mismatched issue shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img16.png)

   **For Instance:** If Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies (v17.1450.0.38) are referred to in the project, but Syncfusion<sup style="font-size:70%">&reg;</sup> script file version (v16.4.0.54) is referred to in View files when script files are referred to via a CDN link. The Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will report that the Syncfusion<sup style="font-size:70%">&reg;</sup> script file version (v16.4.0.54) is incompatible with the project's Syncfusion<sup style="font-size:70%">&reg;</sup> assembly/package version (v17.1.0.38) from CDN.

   ![Syncfusion<sup style="font-size:70%">&reg;</sup> script file version mismatched issue based on CDN link shown in Troubleshooter wizard](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img17.png)

2. Syncfusion<sup style="font-size:70%">&reg;</sup> script files that are duplicates. When a Syncfusion<sup style="font-size:70%">&reg;</sup> script file is presented in the project location, which is referred to in View files by CDN link, or when Syncfusion<sup style="font-size:70%">&reg;</sup> script files are presented in multiple locations in the same project, Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will display duplicate script files.

   **For Instance:** If the project has a “ej.web.all.min.js” script file entry in the View file and a “ej.web.all.min.js” script file in the project location (Scripts\ej), the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will show duplicate Syncfusion<sup style="font-size:70%">&reg;</sup> script files presented in Scripts\ej due to this script file being referred from CDN.
  
   ![Syncfusion<sup style="font-size:70%">&reg;</sup> script file duplicate issue by CDN with local script](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img18.png)

   **For Instance:** If a project has the “ej.web.all.min.js” script file available in multiple project locations ("\Scripts\ej" and "\Scripts\"), the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter will display Duplicate Syncfusion<sup style="font-size:70%">&reg;</sup> script files in Scripts.
  
   ![Syncfusion<sup style="font-size:70%">&reg;</sup> script file duplicate issue by mulitple location ](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img19.png)

## Apply the solution

1. Check the corresponding check box of the issue to be resolved after loading the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter dialog. Then, check “Fix Issue(s)” button.

   ![Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter wizard with project configuration issues](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img20.png)

2. A dialog appears, prompting you to create a backup of the project before proceeding with the troubleshooting process. Click the "Yes" button if you need to backup the project before troubleshooting.

   ![Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter backup dialog](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img21.jpeg)

3. Wait a moment while the Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter resolves the issues you selected. When the troubleshooting process is finished, a message will appear in the Visual Studio status bar that says, "Troubleshooting process completed successfully."

   ![Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter process success status message in visual studio status bar](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img22.jpeg)

4. Then, Syncfusion<sup style="font-size:70%">&reg;</sup> licensing registration required message box will be shown if you installed the trial setup or NuGet packages since Syncfusion<sup style="font-size:70%">&reg;</sup> introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio<sup style="font-size:70%">&reg;</sup> release. Navigate to the  [help topic](https://help.syncfusion.com/common/essential-studio/licensing/license-key#how-to-generate-syncfusion-license-key), which is shown in the licensing message box to generate and register the Syncfusion<sup style="font-size:70%">&reg;</sup> license key to your project. Refer to this [blog](https://blog.syncfusion.com/post/Whats-New-in-2018-Volume-2-Licensing-Changes-in-the-1620x-Version-of-Essential-Studio.aspx) post for understanding the licensing changes introduced in Essential Studio<sup style="font-size:70%">&reg;</sup>.   

   ![Syncfusion<sup style="font-size:70%">&reg;</sup> license registration required information dialog in Syncfusion<sup style="font-size:70%">&reg;</sup> Troubleshooter](SyncfusionTroubleshooter_images/SyncfusionTroubleshooter-img23.jpeg)