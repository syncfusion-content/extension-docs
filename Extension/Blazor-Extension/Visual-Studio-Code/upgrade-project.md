---
layout: post
title: Project Migration | Blazor | Syncfusion
description: Project Migration is a add-in that helps migrate existing Syncfusion Blazor project from one Syncfusion version to another version
platform: extension
control: Syncfusion Extensions
documentation: ug
---

## Upgrade project

Syncfusion Project Migration is a Visual Studio Code add-in that allows you to migrate the existing Syncfusion Blazor Web Application from one Essential Studio version to another version.

   > The Syncfusion Blazor Web Application Project Migration utility is available from `v17.4.0.39`.

The following steps help you to migrate your existing Syncfusion Blazor Web Application.

1. Open an existing Syncfusion Blazor Web Application or create a new Syncfusion Blazor Web Application in Visual Studio Code.

2. Right-click the Project file from Explorer (Workspace), select the Migrate Syncfusion Blazor Application to another version… Refer to the following screenshot for more information.

    ![Migration add-in](images/Migration.png)

    >  The Migration option will enable if Syncfusion reference is added in your application.

3. Select Blazor Version (which published in `nuget.org`) from the palette appears.

    ![Select Blazor Version](images/VersionSelection.png)

4. The Syncfusion NuGet packages references, Scripts, and CSS are updated to the selected version in the project.

    ![NuGetPackage](images/NuGetPackage.png)

    ![CDNLink](images/CDNLink.png)

5. If you installed the trial setup or NuGet packages from nuget.org you have to register the Syncfusion license key to your project since Syncfusion introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio release. Navigate to the [help topic](https://help.syncfusion.com/common/essential-studio/licensing/license-key#how-to-generate-syncfusion-license-key) to generate and register the Syncfusion license key to your project. Refer to this [blog](https://blog.syncfusion.com/post/Whats-New-in-2018-Volume-2-Licensing-Changes-in-the-1620x-Version-of-Essential-Studio.aspx?_ga=2.11237684.1233358434.1587355730-230058891.1567654773) post for understanding the licensing changes introduced in Essential Studio.