---
layout: post
title: Project Migration | Blazor | Syncfusion
description: Project Migration is a add-in that helps migrate existing Syncfusion Blazor project from one Syncfusion version to another version
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Upgrading Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor application to latest version

The Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor migration add-in for Visual Studio allows you to migrate an existing Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor application from one version of Essential Studio<sup style="font-size:70%">&reg;</sup> version to another version. This reduces the amount of manual work required when migrating the Syncfusion<sup style="font-size:70%">&reg;</sup> version.

The steps below will assist you to upgrade the Syncfusion<sup style="font-size:70%">&reg;</sup> version in the Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor application via Visual Studio 2019:

> Before use the Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor Project Migration, check whether the Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor Template Studio Extension installed or not in Visual Studio Extension Manager by clicking on the Extensions -> Manage Extensions -> Installed. If this extension not installed, please install the extension by follow the steps from the [download and installation](https://blazor.Syncfusion.com/documentation/visual-studio-integration/visual-studio-extensions/download-and-installation/) help topic.

1. Open the Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor application that uses the Syncfusion<sup style="font-size:70%">&reg;</sup> component.

2. To open the Migration Wizard, either one of the following options should be followed:

    **Option 1**

    Choose **Extensions -> Syncfusion<sup style="font-size:70%">&reg;</sup> -> Essential Studio<sup style="font-size:70%">&reg;</sup> for Blazor -> Migrate Project…** from Visual Studio 2019 menu.

    ![MigrationMenu](images/MigrationMenu.PNG)

    **Option 2**

    Right-click the application from the **Solution Explorer** and select the **Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor** and choose the **Migrate Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor project from another version...**

    ![MigrationAddin](images/MigrationAddin.png)

3. The Syncfusion<sup style="font-size:70%">&reg;</sup> Project Migration window will appear. You can choose the required version of Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor to migrate.

    > The versions are loaded from the Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor NuGet packages published in [`NuGet.org`](https://www.nuget.org/packages?q=Tags%3A%22blazor%22syncfusion) and it requires internet connectivity.

    ![MigrationWizard](images/Migration.png)

4. Check the **“Enable a backup before migrating”** checkbox if you want to take the project backup and choose the location.

5. Once the migration process is completed, you will get a successful message window

    ![MigrationSuccessMessage](images/MigrationSuccess.png)

    If you enabled project backup before migrating, the old application was saved in the specified backup path location, as shown below once the migration process completed.

    ![MigrationBackupLocation](images/Backuplocation.png)

6. The Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor NuGet packages are updated to the respective version in the application.

7. If you installed the trial setup or NuGet packages from nuget.org you must register the Syncfusion<sup style="font-size:70%">&reg;</sup> license key to your application since Syncfusion<sup style="font-size:70%">&reg;</sup> introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio<sup style="font-size:70%">&reg;</sup> release. Navigate to the [help topic](https://help.Syncfusion.com/common/essential-studio/licensing/overview#how-to-generate-Syncfusion-license-key) to generate and register the Syncfusion<sup style="font-size:70%">&reg;</sup> license key to your application. Refer to this [blog](https://www.Syncfusion.com/blogs/post/whats-new-in-2018-volume-2.aspx) post for understanding the licensing changes introduced in Essential Studio<sup style="font-size:70%">&reg;</sup>.