---
layout: post
title: Convert Project - Blazor Extension for Visual Studio Code | Syncfusion
description: Learn here all about how to convert blazor application into syncfusion blazor application using Blazor Extension for Visual Studio Code.
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Converting Blazor Extension for Visual Studio Code

The Syncfusion® Blazor conversion is an add-in for Visual Studio Code that converts an existing Blazor application into a Syncfusion® Blazor Web Application by adding the required NuGet packages and themes.

N> The Syncfusion® Blazor Web Application Project Conversion utility is available from `v17.4.0.39`.

The steps below assist you to using the Syncfusion® Project conversion in your existing Blazor Web Application:

1. Open an existing Blazor Web Application or create a new Microsoft Blazor Web Application in Visual Studio Code.

2. Select **Convert to Syncfusion Blazor Application...** from the context menu when you right-click on the **Project file** from Explorer (Workspace). Refer the screenshot below.

    ![Conversion Add-in](images/Conversion.PNG)

3. **Select Blazor Version** (which published in `nuget.org`) from the palette appears.

    ![Select Blazor Version](images/VersionSelection.PNG)

4. Choose the **Theme** from the palette appears.

    ![Select Themes](images/ChooseThemes.PNG)

5. The application configured with Syncfusion® Blazor required NuGet packages and themes.

6. If you installed the trial setup or NuGet packages from nuget.org you must register the Syncfusion® license key to your application since Syncfusion® introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio® release. Navigate to the [help topic](https://help.syncfusion.com/common/essential-studio/licensing/overview#how-to-generate-syncfusion-license-key) to generate and register the Syncfusion® license key to your application. Refer to this [UG](https://blazor.syncfusion.com/documentation/getting-started/license-key/overview) topic for understanding the licensing details in Essential Studio® for Blazor.

## NuGet Packages

Based on the application type, the following NuGet packages are added as NuGet references.

| Syncfusion Blazor NuGet packages  | Application type  |
|---|---|
| `Syncfusion.Blazor`  | Syncfusion Blazor Web App <br/> Syncfusion Blazor Server App <br/> Syncfusion Blazor WebAssembly App <br/> Syncfusion Blazor WebAssembly App (ASPNET Core hosted) <br/> Syncfusion Blazor WebAssembly App (Progressive Web Application)|
| `Syncfusion.Blazor.PdfViewerServer.Windows`  | Syncfusion Blazor Server App  |
| `Syncfusion.Blazor.WordProcessor`  | Syncfusion Blazor Server App <br/> Syncfusion Blazor WebAssembly App <br/> Syncfusion Blazor WebAssembly App (ASPNET Core hosted) <br/> Syncfusion Blazor WebAssembly App (Progressive Web Application)|

The NuGet packages added to the application file as follows.

![NuGetPackage](images/NuGetPackage.png)

## Theme links

While converting the application, the selected Syncfusion® Blazor theme is added in the following location of a Blazor type application.

| Application type  | File location  |
|---|---|
| Syncfusion Blazor Web App | ~/Components/App.razor |
| Syncfusion Blazor Server App | {Project location}/Pages//_Host.cshtml |
| Syncfusion Blazor WebAssembly App (ASPNET Core hosted) <br/> Syncfusion Blazor WebAssembly App (Progressive Web Application)| {Client Project location}/wwwroot/index.html  |
| Syncfusion Blazor WebAssembly App  | {Project location}/wwwroot/index.html|

![CDNLink](images/CDNLink.png)