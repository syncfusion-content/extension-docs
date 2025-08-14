---
layout: post
title: Upgrade Project in Blazor - Syncfusion
description: Learn here about how to upgrade the project in the Syncfusion Essential Blazor application to latest version.
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Upgrading Syncfusion® Blazor application to latest version

The Syncfusion® Blazor migration add-in for Visual Studio allows you to migrate an existing Syncfusion® Blazor application from one version of Essential Studio® to another. This reduces the amount of manual work required during the migration process.

The steps below will assist you to upgrade the Syncfusion® version in the Syncfusion® Blazor application via Visual Studio 2022:

N> Before use the Syncfusion® Blazor Project Migration, check whether the Syncfusion® Blazor Template Studio Extension installed or not in Visual Studio Extension Manager by clicking on the Extensions -> Manage Extensions -> Installed. If this extension not installed, install the extension by follow the steps from the [download and installation](download-and-installation) help topic. 

1. Open the Syncfusion® Blazor application that uses the Syncfusion® component in the Visual Studio 2022.

2. To open the Migration Wizard, either one of the following options should be followed:

    **Option 1**

    Choose **Extensions -> Syncfusion® -> Essential Studio® for Blazor -> Migrate Project…** from Visual Studio 2022 menu.

    ![MigrationMenu](images/MigrationMenu.PNG)

    **Option 2**

    Right-click the application from the **Solution Explorer** and select the **Syncfusion® Blazor** and choose the **Migrate Syncfusion® Blazor project from another version...**

    ![MigrationAddin](images/MigrationAddin.png)

3. The Syncfusion® Project Migration window will appear. You can choose the required version of Syncfusion® Blazor to migrate.

    N> The versions are loaded from the Syncfusion® Blazor NuGet packages published in [`NuGet.org`](https://www.nuget.org/packages?q=Tags%3A%22blazor%22syncfusion) and it requires internet connectivity.

    ![MigrationWizard](images/Migration.png)

4. Check the **“Enable a backup before migrating”** checkbox if you want to take the project backup and choose the location.

5. Once the migration process is completed, you will get a successful message window

    ![MigrationSuccessMessage](images/MigrationSuccess.png)

    If you enabled project backup before migrating, the old application was saved in the specified backup path location, as shown below once the migration process completed.

    ![MigrationBackupLocation](images/Backuplocation.png)

6. The Syncfusion® Blazor NuGet packages are updated to the respective selected version in the Syncfusion® Blazor application.

7. If you installed the trial setup or NuGet packages from nuget.org you must register the Syncfusion® license key to your application since Syncfusion® introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio® release. Navigate to the [help topic](https://help.syncfusion.com/common/essential-studio/licensing/overview#how-to-generate-syncfusion-license-key) to generate and register the Syncfusion® license key to your application. Refer to this [blog](https://www.syncfusion.com/blogs/post/whats-new-in-2018-volume-2.aspx) post for understanding the licensing changes introduced in Essential Studio®.