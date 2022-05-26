---
layout: post
title: Project Templates | ASP.NET Core (Essential JS 2) | Syncfusion
description: Syncfusion provides Visual Studio Project Templates for ASP.NET Core platform to create the Syncfusion ASP.NET Core Application using Essential JS 2 components
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Syncfusion Project Templates of ASP.NET Core (Essential JS 2)

Syncfusion provides the **Visual Studio Project Templates** for the Syncfusion ASP.NET Core platform to create the Syncfusion ASP.NET Core Web Application using Essential JS 2 components.

> The Syncfusion ASP.NET Core (Essential JS 2) project templates are available from v16.2.0.41.

The following steps is used to create the **Syncfusion ASP.NET Core (Essential JS 2) Web Application** through the **Visual Studio Project Template**.

> Before use the Syncfusion ASP.NET Core Project Template, check whether the **ASP.NET Core Extensions - Syncfusion** installed or not in Visual Studio Extension Manager by clicking on the Tools -> Extensions and Updates -> Installed for Visual Studio 2017 or lower and for Visual Studio 2019 by clicking on the Extensions -> Manage Extensions -> Installed. If this extension not installed, please install the extension by follow the steps from the [download and installation](https://ej2.syncfusion.com/aspnetcore/documentation/visual-studio-integration/download-and-installation) help topic.

1. To create the Syncfusion ASP.NET Core (Essential JS 2) project, follow either one of the options below:

    **Option 1**

    Click **Syncfusion Menu** and choose **Essential Studio for ASP.NET Core (EJ2) > Create New Syncfusion Project…** in **Visual Studio**.

    ![new project](images/new-project.png)

    > From Visual Studio 2019, Syncfusion menu is available under Extension in Visual Studio menu.

    ![new project](images/SyncfusionMenu.png)

    **Option 2**

    Choose **File > New > Project** and navigate to **Syncfusion > .NET Core > Syncfusion ASP.NET Core (Essential JS 2) Web Application** in **Visual Studio**.

    ![syncfusion template](images/syncfusion-template.png)

2. Name the **Project**, choose the destination location, and then click **OK**. The Project Configuration Wizard appears.

3. Choose the options to configure the Syncfusion ASP.NET Core (Essential JS 2) Application in the following Project Configuration dialog.

    ![project configuration](images/project-configuration.png)

    > .NET 6.0 is available from v19.4.0.38 and support from Visual Studio 2022.

    **Project configurations**

    | <b>Project Type</b> | <b>.NET Core Version</b> | <b>Themes</b> | <b>Assets From</b> |
    |---------------------|--------------------------|---------------|--------------------|
    | ASP.NET Core Web App | .NET Core 3.1 and .NET 6.0 | Material, Fabric, Fluent, Bootstrap, Bootstrap 4, Bootstrap 5, High Contrast, Tailwind CSS | CDN, NPM, Installed Location |
    | ASP.NET Core Web App (Model-View-Controller) | 2.0, 2.1, 2.2, 3.0, 3.1, .NET 5.0, and .NET 6.0 | Material, Fabric, Fluent, Bootstrap, Bootstrap 4, Bootstrap 5, High Contrast, Tailwind CSS | CDN, NPM, Installed Location |
    | Angular | 2.0, 2.1, 2.2, 3.0, 3.1, .NET 5.0, and .NET 6.0 | Material, Fabric, Fluent, Bootstrap, Bootstrap 4, Bootstrap 5, High Contrast, Tailwind CSS | CDN, NPM |
    | React | 2.0, 2.1, 2.2, 3.0, 3.1, .NET 5.0, and .NET 6.0 | Material, Fabric, Fluent, Bootstrap, Bootstrap 4, Bootstrap 5, High Contrast, Tailwind CSS | CDN, NPM |

    > The Syncfusion ASP.NET Core (Essential JS 2) Project Template provides ASP.NET Core, Angular, and React project templates support from v17.1.0.47.

    **.NET Core Version**: Select the version of ASP.NET Core Project.

    ![.net core version](images/net-core-version.png)

    **Assets From**: Load the Syncfusion Essential JS 2 assets to ASP.NET Core Project, either NPM, CDN, or Installed Location.

    > Installed location option will be available only when the Syncfusion Essential JavaScript 2 setup has been installed.

    **Theme Selection**: Themes will be listed out based on the selected project type and choose the required theme from the available list.

    ![theme selection](images/themes.png)

    **Authentication Type**: Authentication will be listed out based on the selected project type and choose the required authentication from the available list.

    > For **Angular** and **React** Project **None** and **Individual Authentication** only supported.

    ![authentication type](images/authentication.png)

4. Click Create, the Syncfusion ASP.NET Core (Essential JS 2) Application has been created.

    ![css refernce](images/readme-file.PNG)

5. The required Syncfusion NuGet/NPM packages, Scripts, and CSS have been added to the Project.

    **Web App and Web App (Model-View-Controller):**

    **NuGet**: Syncfusion.EJ2.AspNet.Core NuGet package will be installed.

    **Scripts/Styles**: Scripts and CSS entries will be added in _Layout.cshtml.

    **Angular:**

    **NPM**: All the Syncfusion Angular NPM packages entries will be added in   package.json, it will automatically restore while build the application or save the  package.json file before compile the project.

    **Styles**: CSS entries will be added in index.html based on the selected .NET Core version.

    **React:**

    **NPM**: All the Syncfusion React NPM packages entries will be added in package.json, it will automatically restore while build the application or save the package.json file before compile the project.

    **Styles**: CSS entries will be added in or index.html based on the selected project .Net Core version.

    ![nuget package](images/nuget-packges.png)

    ![css refernce](images/project-structure.png)

6. Then, Syncfusion licensing registration required message box will be shown, if you installed the trial setup or NuGet packages since Syncfusion introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio release. Navigate to the [help topic](https://help.syncfusion.com/common/essential-studio/licensing/license-key#how-to-generate-syncfusion-license-key), which is shown in the licensing message box to generate and register the Syncfusion license key to your project. Refer to this [blog](https://blog.syncfusion.com/post/whats-new-in-2018-volume-2-licensing-changes-in-the-1620x-version-of-essential-studio.aspx) post for understanding the licensing changes introduced in Essential Studio.

    ![syncfusion license](images/syncfusion-license.png)


## Authentication Configuration

We need to register the created application in Azure Active Directory for **Microsoft Identity Platform**. From Azure Active Directory registration, we can get the tenant id and application client id for Microsoft Identity Platform. We need to configure these id values in created applications then only application will be run correctly with authentication support.

### Microsoft Identity Platform Authentication

**Step:1** Go to below Azure Active Directory App Registration page.
           https://portal.azure.com/#blade/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/RegisteredApps

**Step:2** Click New Registration in App Registration page.

![AppRegistration](images/AppRegistration.PNG)
             
**Step:3** Give name of the application and selected supported type as single tenant.

![SingleTenant](images/SingleTenant.png)

**Step:4** Dropdown the page, select platform as web and give your application Redirect URI like {Redirect URI}/signin-oidc and click Register.

![SelectPlatform](images/SelectPlatform.png)

**Step:5** App will be registered, go to the Authentication page and tick Id token check box.

![IdToken](images/IdToken.png)

**Step:6** Get client tenant id and application id form overview page.

![ClinetTenantId](images/ClientTenantId.png)


**Step:7** Configure those client tenant id, application id, and domain in your application appsettings.json file.

![AppSettings](images/appsettings.png)

## Register and Login Application

### Individual Authentication

1. For register the application, submit your email address and create a password.

![Register](images/Register.png)

2. Confirming registration by clicking Click here to confirm your account.

![Confirm](images/Confirm.png)

3. Submit your registered email address and password to login the application.

![Login](images/Login.png)

### Microsoft Identity Platform

1. Login to your application using your Microsoft account.
2. Accept permission request of your application.

![Permission](images/Permission.png)