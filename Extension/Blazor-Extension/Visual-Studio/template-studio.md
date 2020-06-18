---
layout: post
title: Template Studio | Blazor | Syncfusion
description: Syncfusion provides the Blazor Template Studio for Blazor platform to create the Syncfusion Blazor Application using Syncfusion components
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Template Studio

Syncfusion provides the Blazor Template Studio to create a Syncfusion Blazor application with Syncfusion components. The Syncfusion Blazor application is created with the required Syncfusion NuGet references, namespaces, styles, and component render code. The Template Studio provides an easy-to-use project wizard that teaches you how to create an application with Syncfusion components.

The following steps will help you create your **Syncfusion Blazor Application** through **Visual Studio 2019**:

1. Open Visual Studio 2019.

2. To create a Syncfusion Blazor project, use either of the following options:

   **Option 1**

   Choose **Extension -> Syncfusion -> Essential Studio for Blazor -> Create New Syncfusion Project...** from the **Visual Studio menu**.

    ![CreateMenu](images/CreateMenu.png)

   **Option 2**

   Select **File -> New -> Project**. This opens a new dialog to create a new project. The templates provided by Syncfusion for Blazor can be obtained by filtering the project type for Syncfusion, or by using **Syncfusion** as the keyword in the search option.

    ![CreateNewWindow](images/CreateNewWindow.png)

3. Select the **Syncfusion Blazor Template Studio** and click **Next**.

    ![CreateNewWizard](images/CreateNewWizard.png)

4. The Template Studio wizard for configuring the Syncfusion Blazor app will appear. Select the Blazor type.

   ![ProjectWizard](images/TemplateStudio.png)

   **Project type section**

   Choose one of the Syncfusion Blazor project types:
   * Syncfusion Blazor Server App
   * Syncfusion Blazor WebAssembly App

   In the Syncfusion Blazor WebAssembly App project type, we can choose **ASP.NET Core hosted**, **Progressive Web Application**, or both.

    ![ProjectTypeWizard](images/ProjectTypeWizard.png)

    N> The Progressive Web Application will be enabled if .NET Core version 3.1.200 or higher is installed.

5. Click either **Next** or the **Controls** tab. The Syncfusion Blazor components you can add to the application are listed.

   ![Controls Section](images/ControlsSection1.png)

   Choose the required controls by clicking **Add**.

   ![Controls add and remove button](images/ControlsSection2.png)

   To unselect the added control, use either of the following options:

   **Option 1:** Click **Remove** in the corresponding control box.

   **Option 2:** Click Delete in the control list from **Project Details**.

   ![Selected ControlsList](images/ControlsList.png)

    N> Choose at least one control to enable the Features and Configuration tab.

6. Click either **Next** or the **Features** tab, and you will see the features listed for the selected controls. You can choose the required features.

7. Click either **Next** or the **Configuration** tab, and the Configuration section will be loaded. You can choose the required .NET Core version, themes, https configuration, and Blazor Web Assembly project types (ASP.NET Core hosted and Progressive Web Application).

   N> ASP.NET Core hosted and Progressive Web Application options are only visible for the Blazor Web Assembly App project type.

   ![Choose required Project Configuration](images/Configuration.png)

   **Project details section**

   You can change the configuration details below in the Project Details section to change the project type, delete controls, or change the configurations.

   ![Configure required Project details](images/ProjectDetails.png)

8. Click **Create**. The Syncfusion Blazor application has been created.

**Syncfusion integration**

The latest Syncfusion Blazor NuGet packages, styles, namespaces, and component render code for Syncfusion components are added in the created application.

**NuGet Packages**

The following NuGet packages can be added as NuGet references based on application type.

| Syncfusion Blazor NuGet packages  | Application type  |
|---|---|
| `Syncfusion.Blazor`  | Syncfusion Blazor Server App <br/> Syncfusion Blazor WebAssembly App <br/> Syncfusion Blazor WebAssembly App (ASPNET Core hosted) <br/> Syncfusion Blazor WebAssembly App (Progressive Web Application) <br/> Syncfusion Blazor WebAssembly App (ASPNET Core hosted and Progressive Web Application) |
| `Syncfusion.Blazor.PdfViewerServer.Windows`  | Syncfusion Blazor Server App  |
| `Syncfusion.Blazor.WordProcessor`  | Syncfusion Blazor Server App <br/> Syncfusion Blazor WebAssembly App <br/> Syncfusion Blazor WebAssembly App (ASPNET Core hosted) <br> Syncfusion Blazor WebAssembly App (Progressive Web Application) <br/> Syncfusion Blazor WebAssembly App (ASPNET Core hosted and Progressive Web Application) |

> The installed Syncfusion extension version of a NuGet package will be added as reference entry if there is no internet connection. You have to restore the NuGet packages when internet becomes available.

![NuGetPackage](images/NuGetPackage.png)

**Style**

The selected theme is added from Syncfusion NuGet and its reference at these applications locations in Blazor.

| Application type  | File location  |
|---|---|
| Syncfusion Blazor Server App | {Project location}\Pages\\_Host.cshtml |
| Syncfusion Blazor WebAssembly App (ASPNET Core hosted) <br/> Syncfusion Blazor WebAssembly App (ASPNET Core hosted and Progressive Web Application) | {Client Project location}\wwwroot\index.html  |
| Syncfusion Blazor WebAssembly App <br/> Syncfusion Blazor WebAssembly App (Progressive Web Application) | {Project location}\wwwroot\index.html|

![StyleReference](images/CDNLink.png)

**Namespaces**

The Syncfusion.Blazor namespaces are added in the **`_imports.razor`** file.

![NameSpace](images/NameSpace.png)

**Component render code**

The selected Syncfusion Blazor components and features render code added as .razor files in the pages folder.

![Selected control pagess added in project with selected features](images/ControlPages.png)

**Run application**

You can run the application and see the Syncfusion components you selected. Select a component to see component output.
![Blazor Template output page](images/HomePage.png)

If you installed the trial setup or NuGet packages from nuget.org you have to register the Syncfusion license key to your project since Syncfusion introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio release. Navigate to the [help topic](https://help.syncfusion.com/common/essential-studio/licensing/license-key#how-to-generate-syncfusion-license-key) to generate and register the Syncfusion license key to your project. Refer to this [blog](https://blog.syncfusion.com/post/Whats-New-in-2018-Volume-2-Licensing-Changes-in-the-1620x-Version-of-Essential-Studio.aspx?_ga=2.11237684.1233358434.1587355730-230058891.1567654773) post for understanding the licensing changes introduced in Essential Studio.