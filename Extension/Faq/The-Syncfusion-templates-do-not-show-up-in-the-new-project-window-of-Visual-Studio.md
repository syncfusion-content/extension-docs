---
layout: post
title: Syncfusion template not shown in new project window of Visual Studio
description: The Syncfusion templates do not show up in the new project window of visual studio.  how can to get them installed?
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Syncfusion® template not shown in new project window of Visual Studio


If the Syncfusion® templates do not appear in Visual Studio’s New Project window, it means either the required Visual Studio extension is not installed or the extension is not installed properly.

> **Note:** Installing only the Syncfusion build will not make the templates available in the new project window of Visual Studio. You must also install the corresponding Visual Studio extension from the build.

## Case 1: Syncfusion® Extension is not installed :

Install Syncfusion® Extension in Visual Studio by following below steps:

  - Open Visual Studio  → Extensions → Manage Extensions

  - In the Installed section, search for “{YourSyncfusionPlatform} Extension - Syncfusion”

  - If it is not installed, install it by following one of the options below:

    **Option 1: Install from Syncfusion Setup**

    - Navigate to the following location to install the {YourSyncfusionPlatform} extension:

      _{C:\Program Files (x86)\Syncfusion\Essential Studio\ {YourSyncfusionPlatform} \ {YourBuildVERSION}\Utilities\Extensions\VS2022\}_

    -  Double-click on “.vsix” to begin the installation.

    **Option 2: Install via Visual Studio Marketplace**

    - Open Visual Studio → Extensions → Manage Extensions → Online.

    - Search for “{YourSyncfusionPlatform} Extension - Syncfusion” and install it.

## Case 2: If the Syncfusion® Extension Installed and the template is not shown in project window :

If the extension appears in the Extension Manager after installation but the Syncfusion® template is still not shown in new project window, the issue is usually due to cached or incomplete extension files. In such cases  uninstall existing Syncfusion® extensions and reinstall to resolve this issue as mentioned below:

  - Open Visual Studio  → Extensions → Manage Extensions → Installed.

  - Search for “Syncfusion” and uninstall all related extensions.

  - Manually delete any remaining Syncfusion extension-related files from the following locations:

      _{%appdata%\Local\Microsoft\VisualStudio\{17.0_xx}\Extensions\{Visual Studio Install Path}\Common7\IDE\Extensions\}_

  - Reinstall the extension by one of the option mentioned earlier in the installation steps.
