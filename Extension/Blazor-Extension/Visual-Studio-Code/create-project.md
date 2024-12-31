---
layout: post
title: Project Templates | Blazor | Syncfusion
description: Syncfusion provides Visual Studio Code Project Templates for Blazor platform to create the Syncfusion Blazor Application using Syncfusion components
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Create Project with Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor Template Studio

Syncfusion<sup style="font-size:70%">&reg;</sup> provides **Visual Studio Code project templates** for creating Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor application. Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor generates application that include the necessary Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet packages, namespaces, and component render code for the Calendar, Button, and DataGrid components, as well as the style for making Syncfusion<sup style="font-size:70%">&reg;</sup> component development easier.

> Blazor project templates from `v17.4.0.39` are supported by the Syncfusion<sup style="font-size:70%">&reg;</sup> Visual Studio Code project template.

The instructions below assist you in creating **Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor Applications** using **Visual Studio Code**:

1. To create a Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor application in Visual Studio Code, open the command palette by pressing **Ctrl+Shift+P**. Search for the word **Syncfusion<sup style="font-size:70%">&reg;</sup>** in the Visual Studio Code palette to get the templates provided by Syncfusion<sup style="font-size:70%">&reg;</sup>.

    ![CreateProjectPalette](images/CreateBlazorProjectPalette.png)

2. Select **Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor Template Studio: Launch**, then press **Enter** key. The Template Studio wizard for configuring the Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor app will be launched. Provide the Project Name and Project Path.

    ![TemplateStudioWizard](images/ProjectLocationName.png)

N> Refer to the .NET SDK support for Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor Components [here](https://blazor.Syncfusion.com/documentation/system-requirements#net-sdk).

3. Select either **Next** or the **Project Type** tab. Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor project types will be displayed. Choose one of the following Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor project types based on the version of the .NET SDK you are using.

    | .NET SDK version | Supported Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor Application Type |
    | ------------- | ------------- |
    | [.NET 8.0](https://dotnet.microsoft.com/en-us/download/dotnet/8.0) | Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor Web App |
    | [.NET 8.0](https://dotnet.microsoft.com/en-us/download/dotnet/8.0), [.NET 7.0](https://dotnet.microsoft.com/en-us/download/dotnet/7.0), [.NET 6.0](https://dotnet.microsoft.com/en-us/download/dotnet/6.0) | Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor WebAssembly App |
    | [.NET 7.0](https://dotnet.microsoft.com/en-us/download/dotnet/7.0), [.NET 6.0](https://dotnet.microsoft.com/en-us/download/dotnet/6.0) | Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor Server App |

    In the **Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor Web App** application type, you can configure the following options:

    <table>
    <tbody>
    <tr>
    <td>
    <a href="https://learn.microsoft.com/en-us/aspnet/core/blazor/components/render-modes?view=aspnetcore-8.0#render-modes" rel="nofollow">Interactivity type</a>
    </td>
    <td>
    Server, WebAssembly, Auto (Server and WebAssembly)
    </td>
    </tr>
    <tr>
    <td>
    <a href="https://learn.microsoft.com/en-us/aspnet/core/blazor/tooling?view=aspnetcore-8.0&pivots=windows" rel="nofollow">Interactivity location</a>
    </td>
    <td>
    Global, Per page/component
    </td>
    </tr>
    </tbody>
    </table>

    ![WebAppTemplate](images/WebAppType.png)

     In the **Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor WebAssembly App** application type, you can choose ASP.NET Core hosted, Progressive Web Application, or both.

     ![ProjectType](images/ProjectTypeDetails.png)

4. The Configuration section will be displayed when you click either **Next** or the **Configuration** tab. Here, you have the option for selecting the required .NET Core version, themes, https configuration, and Blazor Web Assembly project types (ASP.NET Core hosted and Progressive Web Application).

    ![Configuration](images/Configuration.png)

    > ASP.NET Core hosted and Progressive Web Application options are only visible if Blazor Web Assembly App project type is selected.

5. Click the **Create** button. The Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor application has been created. The created Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor app has the Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet packages, styles, and the component render code for the Syncfusion<sup style="font-size:70%">&reg;</sup> component added to the Index, Counter, and FetchData pages.

6. You can run the application to see the Syncfusion<sup style="font-size:70%">&reg;</sup> components. Click **F5** or go to **Run>Start Debugging**.

    ![Debug](images/Debug.png)

7. If you installed the trial setup or NuGet packages from nuget.org you must register the Syncfusion<sup style="font-size:70%">&reg;</sup> license key to your application since Syncfusion<sup style="font-size:70%">&reg;</sup> introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio<sup style="font-size:70%">&reg;</sup> release. Navigate to the [help topic](https://help.Syncfusion.com/common/essential-studio/licensing/overview#how-to-generate-Syncfusion-license-key) to generate and register the Syncfusion<sup style="font-size:70%">&reg;</sup> license key to your application. Refer to this [blog](https://www.Syncfusion.com/blogs/post/whats-new-in-2018-volume-2.aspx) post for understanding the licensing changes introduced in Essential Studio<sup style="font-size:70%">&reg;</sup>.

## Syncfusion<sup style="font-size:70%">&reg;</sup> integration

The Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor application configures with latest Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor NuGet packages, styles, namespaces, and component render code for Syncfusion<sup style="font-size:70%">&reg;</sup> components are added in the created application.

### NuGet Packages

The `Syncfusion.Blazor` NuGet package will be added as NuGet references for all application types.

![NuGetPackage](images/NuGetPackage.png)

### Style

The selected theme is added from Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet and its reference at these applications locations in Blazor.

| Application type  | File location  |
|---|---|
| Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor Server App | {Project location}\Pages\\_Host.cshtml |
| Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor WebAssembly App (ASPNET Core hosted) <br/> Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor WebAssembly App (Progressive Web Application) | {Client Project location}\wwwroot\index.html  |
| Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor WebAssembly App  | {Project location}\wwwroot\index.html|

![CDNLink](images/CDNLink.png)

### Namespaces

The Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor namespaces are added in the **`_imports.razor`** file.

![NameSpace](images/NameSpace.png)

### Component render code

The Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor Calendar, Button, and DataGrid component render code is in the Razor files in the pages folder. The render code is updated in these Razor files.

| File name  | Code snippet added |
|---|---|
| `~/Pages/Index.razor`  | ![IndexFileChange](images/IndexFileChange.png) |
| `~/Pages/Counter.razor` | ![CounterPageChange](images/CounterPageChange.png) |
| `~/Pages/FetchData.razor`  | ![FetchDataPageChange](images/FetchDataPageChange.png) |