---
layout: post
title: Upgrade Project to Latest Version in Blazor | Syncfusion
description: Learn here all about upgrading project to use latest version using Syncfusion Blazor Extension for Visual Studio Code.
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Upgrading Syncfusion® Blazor application to latest version

The Syncfusion® Blazor Migration is an add-in for Visual Studio Code allows you to migrate an existing Syncfusion® Blazor Web Application from one Essential Studio® version to another.

   N> The Syncfusion® Blazor Web Application Project Migration utility is available from `v17.4.0.39`.

The steps below assist you to migrating existing Syncfusion® Blazor Web Application.

1. Open an existing Syncfusion® Blazor Web Application or create a new Syncfusion® Blazor Web Application in Visual Studio Code.

2. Select **Migrate Syncfusion® Blazor Application to another version...** from the context menu when you right-click on the **Project file** from Explorer (Workspace). Refer to the screenshot below.

    ![Migration add-in](images/Migration.PNG)

    N>  If you have a Syncfusion® Blazor reference in your application, the Migration option will be enabled.

3. **Select Blazor Version** (which published in `nuget.org`) from the palette appears.

    ![Select Blazor Version](images/VersionSelection.PNG)

4. The Syncfusion® NuGet packages references and themes are updated to the selected version in the application.

    ![NuGetPackage](images/NuGetPackage.png)

    ![CDNLink](images/CDNLink.png)

5. If you installed the trial setup or NuGet packages from nuget.org you must register the Syncfusion® license key to your application since Syncfusion® introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio® release. Navigate to the [help topic](https://help.syncfusion.com/common/essential-studio/licensing/overview#how-to-generate-syncfusion-license-key) to generate and register the Syncfusion® license key to your application. Refer to this [UG](https://blazor.syncfusion.com/documentation/getting-started/license-key/overview) topic for understanding the licensing details in Essential Studio® for Blazor.