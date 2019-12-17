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

### NuGet Packages

The selected version of the Syncfusion NuGet packages is added in the application dependencies.

| Syncfusion Blazor NuGet packages  | Application type  |
|---|---|
| `Syncfusion.EJ2.Blazor`  | Syncfusion Blazor Server App <br/> Syncfusion Blazor WebAssembly App (ASPNET Core hosted) <br/> Syncfusion Blazor WebAssembly App |
| `Syncfusion.EJ2.Blazor.PdfViewerServer.Windows`  | Syncfusion Blazor Server App  |
| `Syncfusion.EJ2.WordEditor.Blazor`  | Syncfusion Blazor Server App <br/> Syncfusion Blazor WebAssembly App (ASPNET Core hosted) <br/> Syncfusion Blazor WebAssembly App |

The NuGet packages added to the project file as follows.

![NuGetPackage](images/NuGetPackage.png)

### CDN links

Added the selected version of the Syncfusion CDN link to the host.cshtml or index.html file.

| Application type  | File location  |
|---|---|
| Syncfusion Blazor Server App | {Project location}\pages\\_Host.cshtml |
| Syncfusion Blazor WebAssembly App (ASPNET Core hosted) | {Client Project location}\wwwroot\index.html  |
| Syncfusion Blazor WebAssembly App  | {Project location}\wwwroot\index.html|

![CDNLink](images/CDNLink.png)