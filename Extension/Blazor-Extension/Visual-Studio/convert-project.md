---
layout: post
title: Project Conversion | Blazor | Syncfusion
description: Project Conversion is a add-in that converts Blazor application into a Syncfusion Blazor application by adding required Syncfusion components
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Converting Blazor application to Syncfusion Blazor application

Syncfusion Blazor conversion is a Visual Studio add-in that converts an existing Blazor application to the Syncfusion Blazor application by adding the required assemblies and theme files.

The steps below help you to convert the **Blazor application** to the **Syncfusion Blazor application** via the **Visual Studio 2019**:

> Before use the Syncfusion Blazor Project Conversion, check whether the Syncfusion Blazor Template Studio Extension installed or not in Visual Studio Extension Manager by clicking on the Extensions -> Manage Extensions -> Installed. If this extension not installed, please install the extension by follow the steps from the [download and installation](https://blazor.syncfusion.com/documentation/visual-studio-integration/download-and-installation) help topic.

1. Open your existing Blazor application or create a new Blazor application

2. To open the Syncfusion Project Conversion Wizard, follow either one of the options below:

    **Option 1:**

    Choose **Extensions -> Syncfusion -> Essential Studio for Blazor -> Convert Project...** in the Visual Studio 2019 menu.

    ![ConversionMenu](images/ConversionMenu.png)

    **Option 2:**

    Right-click the application from the **Solution Explorer** and select the **Syncfusion Blazor** and choose the **Convert to Syncfusion Blazor application...**

    ![ConversionAddin](images/ConversionAddin.png)

3. The Syncfusion Blazor Project Conversion window will appear. You can choose the required version of Syncfusion Blazor and Themes to convert the application.

    ![ConversionWizard](images/Conversion.png)

    > The versions are loaded from the Syncfusion Blazor NuGet packages published in [`NuGet.org`](https://www.nuget.org/packages?q=Tags%3A%22blazor%22syncfusion) and it requires internet connectivity.

4. Check the **“Enable a backup before converting”** checkbox if you want to take the project backup and choose the location.

5. Once the conversion process has been completed, you will get a successful message window.

    ![ConversionSuccessMessage](images/ConversionSuccess.png)

    If you enabled project backup before converting, the old application was saved in the specified backup path location, as shown below once the conversion process completed.

    ![ConversionBackupLocation](images/Backuplocation.png)

6. If you installed the trial setup or NuGet packages from nuget.org you must register the Syncfusion license key to your application since Syncfusion introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio release. Navigate to the [help topic](https://help.syncfusion.com/common/essential-studio/licensing/overview#how-to-generate-syncfusion-license-key) to generate and register the Syncfusion license key to your application. Refer to this [blog](https://www.syncfusion.com/blogs/post/whats-new-in-2018-volume-2.aspx) post for understanding the licensing changes introduced in Essential Studio.

## NuGet Packages

Based on the application type, the following NuGet packages are added as NuGet references.

| Syncfusion Blazor NuGet packages  | Application type  |
|---|---|
| `Syncfusion.Blazor`  | Syncfusion Blazor Server App <br/> Syncfusion Blazor WebAssembly App <br/> Syncfusion Blazor WebAssembly App (ASPNET Core hosted) <br/> Syncfusion Blazor WebAssembly App (Progressive Web Application) <br/> Syncfusion Blazor WebAssembly App (ASPNET Core hosted and Progressive Web Application)|
| `Syncfusion.Blazor.PdfViewerServer.Windows`  | Syncfusion Blazor Server App  |
| `Syncfusion.Blazor.WordProcessor`  | Syncfusion Blazor Server App <br/> Syncfusion Blazor WebAssembly App <br/> Syncfusion Blazor WebAssembly App (ASPNET Core hosted) <br/> Syncfusion Blazor WebAssembly App (Progressive Web Application) <br/> Syncfusion Blazor WebAssembly App (ASPNET Core hosted and Progressive Web Application)|

The NuGet packages added to the application file as follows.

![NuGetPackage](images/NuGetPackage.png)

## Theme link

While converting the application, the Syncfusion Blazor theme is added in the following location of a Blazor application.

| Application type  | File location  |
|---|---|
| Syncfusion Blazor Server App | {Project location}\Pages\\_Host.cshtml |
| Syncfusion Blazor WebAssembly App (ASPNET Core hosted) <br/> Syncfusion Blazor WebAssembly App (ASPNET Core hosted and Progressive Web Application) | {Client Project location}\wwwroot\index.html  |
| Syncfusion Blazor WebAssembly App <br/> Syncfusion Blazor WebAssembly App (Progressive Web Application) | {Project location}\wwwroot\index.html|

![CDNLink](images/CDNLink.png)