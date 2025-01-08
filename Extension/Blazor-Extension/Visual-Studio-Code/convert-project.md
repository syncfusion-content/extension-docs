---
layout: post
title: Project Conversion | Blazor | Syncfusion
description: Project Conversion is a add-in that converts Blazor application into a Syncfusion  Blazor application by adding required Syncfusion  components
platform: extension
control: Syncfusion  Extensions
documentation: ug
---

# Syncfusion<sup style="font-size:70%">&reg;</sup>  Blazor Conversion

The Syncfusion<sup style="font-size:70%">&reg;</sup>  Blazor conversion is an add-in for Visual Studio Code that converts an existing Blazor application into a Syncfusion<sup style="font-size:70%">&reg;</sup>  Blazor Web Application by adding the required NuGet packages and themes.

   > The Syncfusion<sup style="font-size:70%">&reg;</sup>  Blazor Web Application Project Conversion utility is available from `v17.4.0.39`.

The steps below assist you to using the Syncfusion<sup style="font-size:70%">&reg;</sup>  Project conversion in your existing Blazor Web Application:

1. Open an existing Blazor Web Application or create a new Microsoft Blazor Web Application in Visual Studio Code.

2. Select **Convert to Syncfusion<sup style="font-size:70%">&reg;</sup>  Blazor Application...** from the context menu when you right-click on the **Project file** from Explorer (Workspace). Refer the screenshot below.

    ![Conversion Add-in](images/Conversion.PNG)

3. **Select Blazor Version** (which published in `nuget.org`) from the palette appears.

    ![Select Blazor Version](images/VersionSelection.PNG)

4. Choose the **Theme** from the palette appears.

    ![Select Themes](images/ChooseThemes.PNG)

5. The application configured with Syncfusion<sup style="font-size:70%">&reg;</sup>  Blazor required NuGet packages and themes.

6. If you installed the trial setup or NuGet packages from nuget.org you must register the Syncfusion<sup style="font-size:70%">&reg;</sup>  license key to your application since Syncfusion<sup style="font-size:70%">&reg;</sup>  introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio<sup style="font-size:70%">&reg;</sup>  release. Navigate to the [help topic](https://help.syncfusion.com/common/essential-studio/licensing/overview#how-to-generate-syncfusion-license-key) to generate and register the Syncfusion<sup style="font-size:70%">&reg;</sup>  license key to your application. Refer to this [blog](https://www.syncfusion.com/blogs/post/whats-new-in-2018-volume-2.aspx) post for understanding the licensing changes introduced in Essential Studio.

## NuGet Packages

Based on the application type, the following NuGet packages are added as NuGet references.

| Syncfusion<sup style="font-size:70%">&reg;</sup>  Blazor NuGet packages  | Application type  |
|---|---|
| `Syncfusion.Blazor`  | Syncfusion<sup style="font-size:70%">&reg;</sup>  Blazor Server App <br/> Syncfusion<sup style="font-size:70%">&reg;</sup>  Blazor WebAssembly App <br/> Syncfusion<sup style="font-size:70%">&reg;</sup>  Blazor WebAssembly App (ASPNET Core hosted) <br/> Syncfusion<sup style="font-size:70%">&reg;</sup>  Blazor WebAssembly App (Progressive Web Application)|
| `Syncfusion.Blazor.PdfViewerServer.Windows`  | Syncfusion<sup style="font-size:70%">&reg;</sup>  Blazor Server App  |
| `Syncfusion.Blazor.WordProcessor`  | Syncfusion<sup style="font-size:70%">&reg;</sup>  Blazor Server App <br/> Syncfusion<sup style="font-size:70%">&reg;</sup>  Blazor WebAssembly App <br/> Syncfusion<sup style="font-size:70%">&reg;</sup>  Blazor WebAssembly App (ASPNET Core hosted) <br/> Syncfusion<sup style="font-size:70%">&reg;</sup>  Blazor WebAssembly App (Progressive Web Application)|

The NuGet packages added to the application file as follows.

![NuGetPackage](images/NuGetPackage.png)

## Theme links

While converting the application, the selected Syncfusion<sup style="font-size:70%">&reg;</sup>  Blazor theme is added in the following location of a Blazor type application.

| Application type  | File location  |
|---|---|
| Syncfusion<sup style="font-size:70%">&reg;</sup>  Blazor Server App | {Project location}\Pages\\_Host.cshtml |
| Syncfusion<sup style="font-size:70%">&reg;</sup>  Blazor WebAssembly App (ASPNET Core hosted) <br/> Syncfusion<sup style="font-size:70%">&reg;</sup>  Blazor WebAssembly App (Progressive Web Application)| {Client Project location}\wwwroot\index.html  |
| Syncfusion<sup style="font-size:70%">&reg;</sup>  Blazor WebAssembly App  | {Project location}\wwwroot\index.html|

![CDNLink](images/CDNLink.png)