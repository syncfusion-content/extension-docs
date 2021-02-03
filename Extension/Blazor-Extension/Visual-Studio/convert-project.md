---
layout: post
title: Project Conversion | Blazor | Syncfusion
description: Project Conversion is a add-in that converts Blazor application into a Syncfusion Blazor application by adding required Syncfusion components
platform: extension
control: Syncfusion Extensions
documentation: ug
---

## Convert project

Syncfusion Blazor conversion is a Visual Studio add-in that converts the existing Blazor application to the Syncfusion Blazor application.

The following steps help you to convert the **Blazor application** to the **Syncfusion Blazor application** via the **Visual Studio 2019**:

> Before use the Syncfusion Blazor Project Conversion, check whether the Syncfusion Blazor Template Studio Extension installed or not in Visual Studio Extension Manager by clicking on the Extensions -> Manage Extensions -> Installed.

1. Open your existing Blazor application.

    To open the Syncfusion Project Conversion Wizard, either follow one of the options below:

    **Option 1:**

    Choose **Extensions- > Syncfusion- > Essential Studio for Blazor->Convert Project...** in the Visual Studio 2019 menu.

    ![ConversionMenu](images/ConversionMenu.PNG)

    **Option 2:**

    Right-click the application from the **Solution Explorer** and select the **Syncfusion Blazor** and choose the **Convert to Syncfusion Blazor application...**

    ![ConversionAddin](images/ConversionAddin.PNG)

2. The Syncfusion Project Conversion window will appear. You can choose the required version of Syncfusion Blazor and Themes to convert the application.

   > The versions are loaded from the Syncfusion Blazor NuGet packages published in [`NuGet.org`](https://www.nuget.org/) and it requires internet connectivity.

3. If you want to retrieve project backup, select Project Backup.

    ![ConversionWizard](images/ConversionWizard.png)

4. Once the conversion process has been completed, you will get a successful message window.

    ![ConversionSuccessMessage](images/ConversionSuccessMessage.png)

5. If you installed the trial setup or NuGet packages from nuget.org you have to register the Syncfusion license key to your project since Syncfusion introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio release. Navigate to the [help topic](https://help.syncfusion.com/common/essential-studio/licensing/license-key#how-to-generate-syncfusion-license-key) to generate and register the Syncfusion license key to your project. Refer to this [blog](https://blog.syncfusion.com/post/Whats-New-in-2018-Volume-2-Licensing-Changes-in-the-1620x-Version-of-Essential-Studio.aspx?_ga=2.11237684.1233358434.1587355730-230058891.1567654773) post for understanding the licensing changes introduced in Essential Studio.

### NuGet Packages

The selected version of the Syncfusion NuGet packages is added in the application dependencies.

| Syncfusion Blazor NuGet packages  | Application type  |
|---|---|
| `Syncfusion.Blazor`  | Syncfusion Blazor Server App <br/> Syncfusion Blazor WebAssembly App <br/> Syncfusion Blazor WebAssembly App (ASPNET Core hosted) <br/> Syncfusion Blazor WebAssembly App (Progressive Web Application) <br/> Syncfusion Blazor WebAssembly App (ASPNET Core hosted and Progressive Web Application) |
| `Syncfusion.Blazor.PdfViewerServer.Windows`  | Syncfusion Blazor Server App  |
| `Syncfusion.Blazor.WordProcessor`  | Syncfusion Blazor Server App <br/> Syncfusion Blazor WebAssembly App <br/> Syncfusion Blazor WebAssembly App (ASPNET Core hosted) <br/> Syncfusion Blazor WebAssembly App (Progressive Web Application) <br/> Syncfusion Blazor WebAssembly App (ASPNET Core hosted and Progressive Web Application)|

The NuGet packages added to the project file as follows.

![NuGetPackage](images/NuGetPackage.png)

### CDN links

Added the selected version of the Syncfusion CDN link to the host.cshtml or index.html file.

| Application type  | File location  |
|---|---|
| Syncfusion Blazor Server App | {Project location}\pages\\_Host.cshtml |
| Syncfusion Blazor WebAssembly App (ASPNET Core hosted) <br/> Syncfusion Blazor WebAssembly App (ASPNET Core hosted and Progressive Web Application) | {Client Project location}\wwwroot\index.html  |
| Syncfusion Blazor WebAssembly App <br/> Syncfusion Blazor WebAssembly App (Progressive Web Application) | {Project location}\wwwroot\index.html|

![CDNLink](images/CDNLink.png)