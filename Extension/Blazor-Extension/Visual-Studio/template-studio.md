---
layout: post
title: Template Studio | Blazor | Syncfusion
description: Syncfusion provides the Blazor Template Studio for Blazor platform to create the Syncfusion Blazor Application using Syncfusion components
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor Template Studio

Syncfusion<sup style="font-size:70%">&reg;</sup> provides the Blazor Template Studio, which allows you to create a Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor application with Syncfusion<sup style="font-size:70%">&reg;</sup> components. The Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor app is created with the required component Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet references, namespaces, styles, and component render code. The Template Studio provides an easy-to-use project wizard that walks you through the process of creating an application with Syncfusion<sup style="font-size:70%">&reg;</sup> components.

The steps below will assist you to create your **Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor Application** through **Visual Studio 2022**:

> **Note:** The Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor Extensions for Visual Studio 2019 are available on Essential Studio<sup style="font-size:70%">&reg;</sup> release "20.3.0.56" and below.

> Before use the Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor Project Template, check whether the Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor Template Studio Extension installed or not in Visual Studio Extension Manager by clicking on the Extensions -> Manage Extensions -> Installed. If this extension not installed, please install the extension by follow the steps from the [download and installation](https://blazor.Syncfusion.com/documentation/visual-studio-integration/visual-studio-extensions/download-and-installation/) help topic.

1. Open Visual Studio 2022.

2. To create a Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor application, use either one of the following options:

     **Option 1**

     Choose **Extension -> Syncfusion<sup style="font-size:70%">&reg;</sup> -> Essential Studio<sup style="font-size:70%">&reg;</sup> for Blazor -> Create New Syncfusion<sup style="font-size:70%">&reg;</sup> Project...** from the **Visual Studio menu**.

     ![CreateMenu](images/CreateMenu.png)

     **Option 2**

     Choose **File -> New -> Project** from the menu. This launches a new dialogue for creating a new application. Syncfusion<sup style="font-size:70%">&reg;</sup> templates for Blazor can be found by filtering the application type for **Syncfusion<sup style="font-size:70%">&reg;</sup>** or by entering **Syncfusion<sup style="font-size:70%">&reg;</sup>** as a keyword in the search option.

     ![CreateNewWindow](images/CreateNewWindow.png)

3. Select the **Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor Template Studio** and click **Next**.

     ![CreateNewWizard](images/CreateNewWizard.png)

4. The Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor Template Studio wizard will be launched to configure the Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor app.

     > **Note:** Refer to the .NET SDK support for Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor Components [here](https://blazor.Syncfusion.com/documentation/system-requirements#net-sdk).

     **Project type section**

     Choose one of the Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor application types based on the version of the .NET SDK you are using.

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

    ![WebAppTemplate](images/WebAppTemplate.png)

     In the **Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor WebAssembly App** application type, you can choose ASP.NET Core hosted, Progressive Web Application, or both.

     ![WASMTemplate](images/WASMTemplate.png)

     > **Note:** The Progressive Web Application will be enabled if .NET 6.0 version or higher is installed.

5. Click either **Next** or the **Controls** tab. The Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor components you can add to the application are listed.

     ![Controls Section](images/ControlsSection1.png)

     Choose the required control(s) by clicking **Add**.

     To unselect the added control(s), use either one of the following options:

     **Option 1:** Click **Remove** in the corresponding control box.

     **Option 2:** Click Delete in the control list from **Project Details**.

     > **Note:** Choose at least one control to enable the Features and Configuration tab.

6. Click either **Next** or the **Features** tab, and you will see the features listed for the selected controls. You can choose the required features.

7. Click **Next** or the **Configuration** tab to load the Configuration section. You can choose the required (.NET 8.0, .NET 7.0, and .NET 6.0), themes, https configuration, localization option, authentication type, Blazor Web App, and Blazor Web Assembly application types.

     Depending on your Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor Application Type, refer to the table below for supported authentication types.

     | Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor Application Type | Supported Authentication Types |
     | ------------- | ------------- |
     | Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor Web App | None and Individual Accounts |
     | Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor WebAssembly App | None, Individual Accounts and Microsoft Identity Platform |
     | Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor Server App | None, Individual Accounts, Microsoft Identity Platform, and Windows |

     If you choose the **Blazor Web App** application type, you can customize the Interactivity type and Interactivity location options.

     ![WebAppConfiguration](images/WebAppConfig.png)

     If you choose the **Blazor Web Assembly App** application type, you can customize the ASP.NET Core hosted and Progressive Web Application options.

     ![WASMConfiguration](images/WASMConfig.png)

     **Project details section**

     You can change the configuration details below in the Project Details section to change the application type, remove control(s) from the selected controls, or change the configurations.

     ![ProjectDetails](images/ProjectDetails.png)

8. Click **Create** button. The Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor application has been created. The created Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor app has the Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet packages, styles, and the render code for the Syncfusion<sup style="font-size:70%">&reg;</sup> component.

     ![Readme](images/readme.png)

9. If you installed the trial setup or NuGet packages from nuget.org you must register the Syncfusion<sup style="font-size:70%">&reg;</sup> license key to your application since Syncfusion<sup style="font-size:70%">&reg;</sup> introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio<sup style="font-size:70%">&reg;</sup> release. Navigate to the [help topic](https://help.Syncfusion.com/common/essential-studio/licensing/overview#how-to-generate-Syncfusion-license-key) to generate and register the Syncfusion<sup style="font-size:70%">&reg;</sup> license key to your application. Refer to this [blog](https://www.Syncfusion.com/blogs/post/whats-new-in-2018-volume-2.aspx) post for understanding the licensing changes introduced in Essential Studio<sup style="font-size:70%">&reg;</sup>.

## Syncfusion<sup style="font-size:70%">&reg;</sup> integration

The Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor application configures with most recent Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor NuGet packages version, styles, namespaces, and component render code for Syncfusion<sup style="font-size:70%">&reg;</sup> components.

### NuGet Packages

Based on the selected Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor controls, the individual NuGet packages can be added as NuGet references. Refer [this topic](https://blazor.Syncfusion.com/staging/documentation/nuget-packages/) to know about the individual Blazor NuGet packages.

> The latest Syncfusion<sup style="font-size:70%">&reg;</sup> Essential Studio<sup style="font-size:70%">&reg;</sup> version of a NuGet package will be added as reference entry from nuget.org if there is no internet connection. You should restore the NuGet packages when internet becomes available.

![NuGetPackage](images/NuGetPackage.png)

### Style

The selected Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor theme is added from Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet and this theme reference will be added at these applications locations in Blazor.

| Application type  | File location  |
|---|---|
| Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor Server App | {Project location}\Pages\\_Host.cshtml |
| Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor WebAssembly App (ASPNET Core hosted) <br/> Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor WebAssembly App (ASPNET Core hosted and Progressive Web Application) | {Client Project location}\wwwroot\index.html  |
| Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor WebAssembly App <br/> Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor WebAssembly App (Progressive Web Application) | {Project location}\wwwroot\index.html|

![CDNLink](images/CDNLink.png)

### Namespaces

The Syncfusion<sup style="font-size:70%">&reg;</sup>.Blazor namespaces are added in the **`_imports.razor`** file.

![NameSpace](images/NameSpace.png)

### Component render code

The selected Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor components and features render code added as .razor files in the pages folder.

![Selected control pagess added in project with selected features](images/ControlPages.png)

### Authentication Configuration

We need to register the created application in Google Platform API Console for Individual Accounts and Azure Active Directory for Microsoft Identity Platform. From Google Platform API Console registration we can get the client id for Individual Accounts. From Azure Active Directory registrations we can get the tenant id and application client id for Microsoft Identity Platform. We need to configure these id values in created applications then only application will be run correctly with authentication support.

### Individual Accounts Authentication

#### Web Application and Progressive Web Application

1. Go to below credentials page for the Google cloud platform API console.

    <https://console.cloud.google.com/apis/credentials?project=aerobic-furnace-244104>

2. Click Create Credentials and OAuth Client Id.

    ![Google API console credentials page](images/GoogelAPIConsoleCredentials.png)

    ![Google API Oauth client Id](images/OauthclientId.png)

3. Select Application type as Web Application in client Id creation.

    ![ApplicationType](images/ClientIdApplicationtype.PNG)

4. Add your publish URL link as an Authorized URI and login URL as Redirected URI.

    ![RedirectedURI](images/RedirectedURI.png)

5. Click save then OAuth client id will be created and copy that credentials.

    ![ClientIdCreation](images/ClientIdCreation.PNG)

6. Add that Client Id, and RedirectUri in appsettings.json file of your application.

    ![ClinetIdConfiguration](images/ClinetIdConfiguration.PNG)

7. Change the build configuration bind as google from Local in program.cs file.

    ![buildconfigurationbind](images/buildconfigurationbind.PNG)

### Microsoft Identity Platform Authentication

#### Server Application

1. Go to below Azure Active Directory App Registration page.

    <https://portal.azure.com/#blade/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/RegisteredApps>

2. Click New Registration in App Registration page.

    ![AppRegistration](images/AppRegistration.PNG)

3. Give name of the application and selected supported type as single tenant.

    ![Name and supported Account type](images/NameSupportedAccountType.PNG)

4. Dropdown the page, select platform as web and give your application Redirect URI and click Register.

    ![Platform and Redirect URI](images/AADRedirectedURI.png)

5. App will be registered, go to the Authentication page and tick Id token check box.

    ![Access token and Id token](images/AuthenticationCheckBox1.PNG)

6. Get client tenant id and application id form overview page.

    ![Clinet tenat id](images/ClinetTenantId.PNG)

7. Configure those client tenant id, application id, and domain in your application appsettings.json file.

    ![Project configuration](images/Configuration1.png)

#### Web Application and Progressive Web Application

1. Go to below Azure Active Directory App Registration page.

    <https://portal.azure.com/#blade/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/RegisteredApps>

2. Click New Registration in App Registration page.

    ![AppRegistration](images/AppRegistration.PNG)

3. Give name of the application and selected supported type as single tenant.

    ![Name and supported Account type](images/NameSupportedAccountType.PNG)

4. Dropdown the page, select platform as web and give your application Redirect URI and click Register.

    ![Platform and Redirect URI](images/AADRedirectedURI.png)

5. App will be registered, go to the Authentication page and tick Access token an Id token check box.

    ![Access token and Id token](images/AuthenticationCheckBox.PNG)

6. Migrate the API by clicking the highlighted arrow like in below image.

    ![API Migration](images/Migration1.PNG)

    ![Migration configuration](images/Migration2.PNG)

7. Get client tenant id and application id form overview page.

    ![Clinet tenat id](images/ClinetTenantId.PNG)

8. Configure those client tenant id and application id in your application appsettings.json file.

    ![Clinet ID and Tenant ID configuration](images/ClinetTenantIdConfiguration.PNG)

#### ASP.NET Core Hosted Web Application, and ASP.NET Core Hosted with Progressive Web Application

##### Client project Registration and Configuration

1. Go to below Azure Active Directory App Registration page.

    <https://portal.azure.com/#blade/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/RegisteredApps>

2. Click New Registration in App Registration page.

    ![AppRegistration](images/AppRegistration.PNG)

3. Give name of the application and selected supported type as single tenant.

    ![Name and supported Account type](images/NameSupportedAccountType.PNG)

4. Dropdown the page, select platform as web and give your application Redirect URI and click Register.

    ![Platform and Redirect URI](images/AADRedirectedURI.png)

5. App will be registered, go to the Authentication page and tick Access token an Id token check box.

    ![Access token and Id token](images/AuthenticationCheckBox.PNG)

6. Migrate the API by clicking the highlighted arrow like in below image.

    ![API Migration](images/Migration1.PNG)

    ![Migration configuration](images/Migration2.PNG)

7. Get client tenant id and application id form overview page.

    ![Clinet tenat id](images/ClinetTenantId.PNG)

8. Configure those client tenant id and application id in your application appsettings.json file.

    ![Clinet ID and Tenant ID configuration](images/ClinetTenantIdConfiguration.PNG)

##### Server project Registration and configuration

1. Go to below Azure Active Directory App Registration page.

    <https://portal.azure.com/#blade/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/RegisteredApps>

2. Click New Registration in App Registration page.

    ![Server App Registration](images/AppRegistration.PNG)

3. Give name of the application and selected supported type as single tenant.

    ![Name and supported Account type](images/NameSupportedAccountType.PNG)

4. Dropdown the page, select platform as web and give your application Redirect URI and click Register.

    ![Server Platform and Redirect URI](images/AADRedirectedURI.png)

5. App will be registered, go to the Authentication page and tick Access token an Id token check box.

    ![Access token and Id token](images/AuthenticationCheckBox.PNG)

6. Migrate the API by clicking the highlighted arrow like in below image.

    ![API Migration](images/Migration1.PNG)

    ![Migration configuration](images/Migration2.PNG)

7. Add a scope API in Expose an API page.

    ![Add scope API](images/AddScopeAPI.png)

8. Give scope name, admin consent display name, and admin consent description and click Add scope. Scope API will be created, copy those scope API Value.

    ![Add scope API configuration](images/AddScopeAPI1.png)

9. Get client tenant id and application id form overview page.

    ![Clinet tenat id](images/ClinetTenantId.PNG)

10. Configure those client tenant id, application id, and domain in your application appsettings.json file.

    ![Project configuration](images/Configuration1.png)

11. Configure the scope API in client application program.cs file below highlighted place.

    ![Scope API configuration](images/ScopeAPIConfiguration.PNG)

### Run application

You can run the application and see the Syncfusion<sup style="font-size:70%">&reg;</sup> components you selected. Select a component to see component output.

![Blazor Template output page](images/HomePage.png)

You can select a culture language in combobox at top right on the output page to apply the culture in the application.

![Blazor Template output page](images/Localization.png)

> **Note:** Above culture combobox will be enabled in sample output if localization option is selected in configuration window from Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor Template Studio wizard.

### Register and Login Application

### Individual Authentication

#### Blazor Web App

##### Applying Database Migrations and User Registration in the .NET 8.0 Blazor Web App

##### Applying Database Migrations:

In the Blazor Web App, it's essential<sup style="font-size:70%">&reg;</sup> to apply pending migrations to the database before proceeding with user registration. Choose one of the following options:

**Option 1: Using Visual Studio Package Manager Console**
 
Navigate to **View -> Other Windows -> Package Manager Console** in Visual Studio.
 
Run the following command in the Package Manager Console:

   ```Update-Database```

**Option 2: Using Command Prompt**
 
Open a command prompt in your project directory and execute the following command:

   ```dotnet ef database update```

##### User Registration:

1.	Launch the application and register by submitting your email address and creating a password.

    ![Register the WebApp](images/WebAppRegister.png)

2.	Confirm your registration by clicking **Click here to confirm your account.**

    ![Confirming the WebApp registration](images/WebAppRegisterConfirmation.png)

3.	Submit your registered email address and password to log in to the application.

    ![LogIn to the WebApp](images/WebApplogIn.png)

#### Server Application, ASP.NET Core hosted Web Application, and Progressive Web Application with ASP.NET Core hosted

1. For register the application, submit your email address and create a password.

    ![Register the application](images/RegisterApplication.png)

2. Confirming registration by clicking **Click here to confirm your account.**

    ![Register the confirmation](images/RegisterConfirmation.png)

3. Submit your registered email address and password to login the application.

    ![login to the application](images/Login.png)

#### Web Application and Progressive Web Application

1. Login to the application using Gmail accounts.

    ![Google login](images/GoogleLogin.PNG)

### Microsoft Identity Platform

#### Server Application, Web Application, Progressive Application, ASP.NET Core Hosted Web Application, and ASP.NET Core Hosted with Progressive Web Application

1. Login to your application using your Microsoft account.

2. Accept permission request of your application.

    ![Accept permission](images/MicrosoftAuthentication.PNG)
