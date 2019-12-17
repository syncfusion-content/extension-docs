---
layout: post
title: Project Templates | Blazor | Syncfusion
description: Syncfusion provides Visual Studio Code Project Templates for Blazor platform to create the Syncfusion Blazor Application using Syncfusion components
platform: extension
control: Syncfusion Extensions
documentation: ug
---

## Create project

Syncfusion provides **Visual Studio Code Project Templates** to create the Syncfusion Blazor applications. The
Syncfusion Blazor creates applications with the required Syncfusion NuGet packages, namespaces, component code
snippets, and CDN links for making the development earlier with the Syncfusion components.

The following steps help you to create **Syncfusion Blazor Applications** through the **Visual Studio Code:**

1. To create a Syncfusion Blazor project, Click **Ctrl+Shift+P** in Visual Studio Code. The Visual Studio Code palette opens, you can get the Syncfusion provided templates using the **Search** option with the word of **Syncfusion**.

    ![CreateProjectPalette](images/CreateProjectPalette.png)

2. Select Create Syncfusion Blazor Project, and then click Enter. The **Project Location** palette appears to store the application.

    ![ProjectLocation](images/ProjectLocation.png)

3. Provide the destination location, and then click Enter. The **Project Name** palette appears.

    ![ProjectName](images/ProjectName.png)

    > The Syncfusion Visual Studio Code Project Template provides Blazor project templates support from `v17.4.0.39`.

4. Provide the Project name, and then click Enter. The Syncfusion Blazor Project types palette appears. The Syncfusion Blazor has the following three types of projects:

    1. Syncfusion Blazor Server App
    2. Syncfusion Blazor WebAssembly App
    3. Syncfusion Blazor WebAssembly App (ASP.NET Core hosted)

    ![ProjectTypes](images/ProjectTypes.png)  

    Choose the preferred Syncfusion Blazor application, and then click Enter. The Theme selection palette appears.

5. Choose the preferred theme, and then click Enter. The project will be created.

    ![Themes](images/Themes.png)

6. The created Syncfusion Blazor application is configured with Syncfusion NuGet packages, CDN links, and the Syncfusion component code snippets added in the Index, Counter, and FetchData pages.

7. You can run the application by clicking **F5** or navigating to **Debug>Start Debugging** and see the Syncfusion components.

    ![Debug](images/Debug.png)

## Syncfusion integration

Syncfusion adds the required latest version of Syncfusion Blazor NuGet packages, CDN Scripts, namespace, and the
Syncfusion component code snippets.

### NuGet Packages

The following NuGet packages are added as NuGet references based on applications.

| Syncfusion Blazor NuGet packages  | Application type  |
|---|---|
| `Syncfusion.EJ2.Blazor`  | Syncfusion Blazor Server App <br/> Syncfusion Blazor WebAssembly App (ASPNET Core hosted) <br/> Syncfusion Blazor WebAssembly App |
| `Syncfusion.EJ2.Blazor.PdfViewerServer.Windows`  | Syncfusion Blazor Server App  |
| `Syncfusion.EJ2.WordEditor.Blazor`  | Syncfusion Blazor Server App <br/> Syncfusion Blazor WebAssembly App (ASPNET Core hosted) <br/> Syncfusion Blazor WebAssembly App |

![NuGetPackage](images/NuGetPackage.png)

### CDN links

The Syncfusion Blazor scripts and the selected themes (while creating the project) are added as CDN link in the
following locations of Blazor type application.

| Application type  | File location  |
|---|---|
| Syncfusion Blazor Server App | {Project location}\pages\\_Host.cshtml |
| Syncfusion Blazor WebAssembly App (ASPNET Core hosted) | {Client Project location}\wwwroot\index.html  |
| Syncfusion Blazor WebAssembly App  | {Project location}\wwwroot\index.html|

![CDNLink](images/CDNLink.png)

### Namespaces

The Syncfusion Blazor component Grids, Calendars, and Buttons namespace are added to the **`_imports.razor`** file in the application. You can add the required other component namespace for development.

![NameSpace](images/NameSpace.png)

### Code snippet

The Syncfusion Blazor components code snippets are added in the created application. The code changes are,

| File name  | Code snippet added |
|---|---|
| `Index.razor`  | ![IndexFileChange](images/IndexFileChange.png) |
| `Counter.razor` | ![CounterPageChange](images/CounterPageChange.png) |
| `FetchData.razor`  | ![FetchDataPageChange](images/FetchDataPageChange.png) |