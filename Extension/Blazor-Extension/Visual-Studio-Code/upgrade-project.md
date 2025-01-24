---
layout: post
title: Project Migration | Blazor | Syncfusion
description: Project Migration is a add-in that helps migrate existing Syncfusion  Blazor project from one Syncfusion  version to another version
platform: extension
control: Syncfusion  Extensions
documentation: ug
---

# Upgrading Syncfusion<sup style="font-size:70%">&reg;</sup>  Blazor application to latest version

The Syncfusion<sup style="font-size:70%">&reg;</sup>  Blazor Migration is an add-in for Visual Studio Code allows you to migrate an existing Syncfusion<sup style="font-size:70%">&reg;</sup>  Blazor Web Application from one Essential Studio<sup style="font-size:70%">&reg;</sup>  version to another.

   > The Syncfusion<sup style="font-size:70%">&reg;</sup>  Blazor Web Application Project Migration utility is available from `v17.4.0.39`.

The steps below assist you to migrating existing Syncfusion<sup style="font-size:70%">&reg;</sup>  Blazor Web Application.

1. Open an existing Syncfusion<sup style="font-size:70%">&reg;</sup>  Blazor Web Application or create a new Syncfusion<sup style="font-size:70%">&reg;</sup>  Blazor Web Application in Visual Studio Code.

2. Select **Migrate Syncfusion<sup style="font-size:70%">&reg;</sup>  Blazor Application to another version...** from the context menu when you right-click on the **Project file** from Explorer (Workspace). Refer to the screenshot below.

    ![Migration add-in](images/Migration.PNG)

    >  If you have a Syncfusion<sup style="font-size:70%">&reg;</sup>  Blazor reference in your application, the Migration option will be enabled.

3. **Select Blazor Version** (which published in `nuget.org`) from the palette appears.

    ![Select Blazor Version](images/VersionSelection.PNG)

4. The Syncfusion<sup style="font-size:70%">&reg;</sup>  NuGet packages references and themes are updated to the selected version in the application.

    ![NuGetPackage](images/NuGetPackage.png)

    ![CDNLink](images/CDNLink.png)

5. If you installed the trial setup or NuGet packages from nuget.org you must register the Syncfusion<sup style="font-size:70%">&reg;</sup>  license key to your application since Syncfusion<sup style="font-size:70%">&reg;</sup>  introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio<sup style="font-size:70%">&reg;</sup>  release. Navigate to the [help topic](https://help.syncfusion.com/common/essential-studio/licensing/license-key#how-to-generate-syncfusion-license-key) to generate and register the Syncfusion<sup style="font-size:70%">&reg;</sup>  license key to your application. Refer to this [blog](https://www.syncfusion.com/blogs/post/whats-new-in-2018-volume-2.aspx) post for understanding the licensing changes introduced in Essential Studio.