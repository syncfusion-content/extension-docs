---
layout: post
title: Template Studio in Document SDK - Syncfusion
description: Learn here about how to create the Blazor application using Syncusion® Document SDK Components with the help of template studio.
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Syncfusion® Document SDK Template Studio

Syncfusion® provides the Document SDK Template Studio, which allows you to create a Syncfusion Blazor application using Syncfusion® Document SDK components. The Syncfusion® Blazor app is created with the required Syncfusion® NuGet references, namespaces, styles, and component render code. The Template Studio includes an easy-to-use project wizard that guides you through the process of creating an application with Syncfusion® Document SDK components.

The steps below will assist you to create your **Syncfusion® Blazor Application** through **Visual Studio 2022**:

N> Before use the Syncfusion® Project Template, check whether the Syncfusion® Document SDK Template Studio Extension installed or not in Visual Studio Extension Manager by clicking on the Extensions -> Manage Extensions -> Installed. If this extension not installed, install the extension by follow the steps from the [download and installation](https://blazor.syncfusion.com/documentation/visual-studio-integration/download-and-installation) help topic.

1. Open Visual Studio 2022.

2. To create a Syncfusion® Blazor application, use either one of the following options:

     **Option 1**

     Choose **Extension -> Syncfusion -> Essential Studio® for Document SDK -> Create New Syncfusion Project...** from the **Visual Studio menu**.

     ![CreateMenu](images/createmenu.png)

     **Option 2**

     Choose **File -> New -> Project** from the menu. This launches a new dialogue for creating a new application. Syncfusion® templates can be found by filtering the application type for **Syncfusion** or by entering **Syncfusion** as a keyword in the search option.

     ![CreateNewWindow](images/createnewwindow.png)

3. Select the **Syncfusion® Document SDK Template Studio** and click **Next**.

     ![CreateNewWizard](images/CreateNewWindow.png)

4. The Syncfusion® Document SDK Template Studio wizard will be launched to configure the Syncfusion Blazor app.

     > **Note:** Refer to the .NET SDK support for Syncfusion Blazor Components [here](https://blazor.syncfusion.com/documentation/system-requirements#net-sdk).

     **Project type section**

     Choose one of the Syncfusion® Blazor application types based on the version of the .NET SDK you are using.

    | .NET SDK version | Supported Syncfusion Blazor Application Type |
    | ---------------- | -------------------------------------------- |
    | [.NET 9.0](https://dotnet.microsoft.com/en-us/download/dotnet/9.0), [.NET 8.0](https://dotnet.microsoft.com/en-us/download/dotnet/8.0) | Syncfusion Blazor Web App |
    | [.NET 9.0](https://dotnet.microsoft.com/en-us/download/dotnet/9.0), [.NET 8.0](https://dotnet.microsoft.com/en-us/download/dotnet/8.0) | Syncfusion Blazor WebAssembly App |


    In the **Syncfusion Blazor Web App** application type, you can configure the following options:

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

    ![WebAppTemplate](images/webapptemplate.png)

     In the **Syncfusion Blazor WebAssembly App** application type, you can choose Progressive Web Application.

     ![WASMTemplate](images/wasmtemplate.png)

     > **Note:** The Progressive Web Application will be enabled if .NET 8.0 version or higher is installed.

5. Click either **Next** or the **Controls** tab. The Syncfusion® Document SDK components you can add to the application are listed.

     ![Controls Section](images/controlssection.png)

     Choose the required control(s) by clicking the corresponding control box.

     To unselect the added control(s), use either one of the following options:

     **Option 1:** Click the corresponding selected control box.

     **Option 2:** Click ‘x’ button for corresponding control in the control list from **Project Details**.

     N> **Note:** Choose at least one control to enable the Features and Configuration tab.

6. Click either **Next** or the **Features** tab, and you will see the features listed for the selected controls. You can choose the required features.

7. Click **Next** or the **Configuration** tab to load the Configuration section. You can choose the required (.NET 9.0 and .NET 8.0), themes, https configuration, localization option, authentication type, Blazor Web App, and Blazor Web Assembly application types.

     Depending on your Syncfusion Blazor Application Type, refer to the table below for supported authentication types.

     | Syncfusion Blazor Application Type | Supported Authentication Types |
     | ------------- | ------------- |
     | Syncfusion Blazor Web App | None and Individual Accounts |
     | Syncfusion Blazor WebAssembly App | None, Individual Accounts and Microsoft Identity Platform |

     If you choose the **Blazor Web App** application type, you can customize the Interactivity type and Interactivity location options.

     ![WebAppConfiguration](images/webappconfig.png)

     If you choose the **Blazor Web Assembly App** application type, you can customize the Progressive Web Application option.

     ![WASMConfiguration](images/wasmconfig.png)

     **Project details section**

     You can change the configuration details below in the Project Details section to change the application type, remove control(s) from the selected controls, or change the configurations.

     ![ProjectDetails](images/rightsideprojectdetails.png)

8. Click **Create** button. The Syncfusion® Blazor application has been created. The created Syncfusion® Blazor app has the Syncfusion NuGet packages, styles, and the render code for the selected Syncfusion® Document SDK component.

     ![Readme](images/readme.png)

9. The Syncfusion® Blazor application configures with most recent Syncfusion® NuGet packages version, selected style, namespaces, selected authentication, and component render code for Syncfusion® Document SDK components.

10. If you installed the trial setup or NuGet packages from nuget.org you must register the Syncfusion® license key to your application since Syncfusion® introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio® release. Navigate to the [help topic](https://help.syncfusion.com/common/essential-studio/licensing/overview#how-to-generate-syncfusion-license-key) to generate and register the Syncfusion® license key to your application. Refer to this [blog](https://www.syncfusion.com/blogs/post/whats-new-in-2018-volume-2.aspx) post for understanding the licensing changes introduced in Essential Studio®.

## Authentication Configuration

We need to register the created application in the Google API Console for Individual Accounts and in Azure Active Directory for the Microsoft Identity Platform. From the Google API Console registration, we can obtain the client ID for Individual Accounts. From the Azure Active Directory registration, we can obtain the tenant ID and application client ID for the Microsoft Identity Platform. We need to configure these ID values in the created applications; only then will the application run correctly with authentication support.

### Individual Accounts Authentication

#### Web Application and Progressive Web Application

1. Go to below credentials page for the Google cloud platform API console.

    <https://console.cloud.google.com/apis/credentials?project=aerobic-furnace-244104&pli=1>

2. Click Create Credentials and OAuth Client Id.

    ![Google API console credentials page](images/googelapiconsolecredentials.png)

    ![Google API Oauth client Id](images/oauthclientid.png)

3. Select Application type as Web Application in client Id creation.

    ![ApplicationType](images/clientidapplicationtype.png)

4. Add your publish URL link as an Authorized URI and login URL as Redirected URI.

    ![RedirectedURI](images/redirecteduri.png)

5. Click save then OAuth client id will be created and copy that credential.

    ![ClientIdCreation](images/clientidcreation.png)

6. Add that Client Id, and RedirectUri in appsettings.json file of your application.

    ![ClinetIdConfiguration](images/clinetidconfiguration.png)

7. Change the build configuration bind as google from Local in program.cs file.

    ![buildconfigurationbind](images/buildconfigurationbind.png)

### Microsoft Identity Platform Authentication

#### Server Application

1. Go to below Azure Active Directory App Registration page.

    <https://portal.azure.com/#view/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/~/RegisteredApps>

2. Click New Registration in App Registration page.

    ![AppRegistration](images/appregistration.png)

3. Give name of the application and selected supported type as single tenant.

    ![Name and supported Account type](images/namesupportedaccounttype.png)

4. Dropdown the page, select platform as web and give your application Redirect URI like {Redirect URI}/signin-oidc and click Register.

    ![Platform and Redirect URI](images/aadredirecteduri.png)

5. App will be registered, go to the Authentication page and tick Id token check box.

    ![Access token and Id token](images/authenticationcheckbox.png)

6. Get client tenant id and application id form overview page.

    ![Clinet tenat id](images/clinettenantid.png)

7. Configure those client tenant id, application id, and domain in your application appsettings.json file.

    ![Project configuration](images/configuration1.png)

#### Web Application and Progressive Web Application

1. Go to below Azure Active Directory App Registration page.

    <https://portal.azure.com/#view/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/~/RegisteredApps>

2. Click New Registration in App Registration page.

    ![AppRegistration](images/appregistration.png)

3. Give name of the application and selected supported type as single tenant.

    ![Name and supported Account type](images/namesupportedaccounttype.png)

4. Dropdown the page, select platform as web and give your application Redirect URI and click Register.

    ![Platform and Redirect URI](images/aadredirecteduri.png)

5. App will be registered, go to the Authentication page and tick Access token an Id token check box.

    ![Access token and Id token](images/authenticationcheckbox.png)

6. Migrate the API by clicking the highlighted arrow like in below image.

    ![API Migration](images/migration1.png)

    ![Migration configuration](images/migration2.png)

7. Get client tenant id and application id form overview page.

    ![Clinet tenat id](images/clinettenantid.png)

8. Configure those client tenant id and application id in your application appsettings.json file.

    ![Clinet ID and Tenant ID configuration](images/clinettenantidconfiguration.png)

#### ASP.NET Core Hosted Web Application, and ASP.NET Core Hosted with Progressive Web Application

##### Client project Registration and Configuration

1. Go to below Azure Active Directory App Registration page.

    <https://portal.azure.com/#view/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/~/RegisteredApps>

2. Click New Registration in App Registration page.

    ![AppRegistration](images/appregistration.png)

3. Give name of the application and selected supported type as single tenant.

    ![Name and supported Account type](images/namesupportedaccounttype.png)

4. Dropdown the page, select platform as web and give your application Redirect URI and click Register.

    ![Platform and Redirect URI](images/aadredirecteduri.png)

5. App will be registered, go to the Authentication page and tick Access token an Id token check box.

    ![Access token and Id token](images/authenticationcheckbox.png)

6. Migrate the API by clicking the highlighted arrow like in below image.

    ![API Migration](images/migration1.png)

    ![Migration configuration](images/migration2.png)

7. Get client tenant id and application id form overview page.

    ![Clinet tenat id](images/clinettenantid.png)

8. Configure those client tenant id and application id in your application appsettings.json file.

    ![Clinet ID and Tenant ID configuration](images/clinettenantidconfiguration.png)

##### Server project Registration and configuration

1. Go to below Azure Active Directory App Registration page.

    <https://portal.azure.com/#view/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/~/RegisteredApps>

2. Click New Registration in App Registration page.

    ![Server App Registration](images/appregistration.png)

3. Give name of the application and selected supported type as single tenant.

    ![Name and supported Account type](images/namesupportedaccounttype.png)

4. Dropdown the page, select platform as web and give your application Redirect URI and click Register.

    ![Server Platform and Redirect URI](images/aadredirecteduri.png)

5. App will be registered, go to the Authentication page and tick Access token an Id token check box.

    ![Access token and Id token](images/authenticationcheckbox.png)

6. Migrate the API by clicking the highlighted arrow like in below image.

    ![API Migration](images/migration1.png)

    ![Migration configuration](images/migration2.png)

7. Add a scope API in Expose an API page.

    ![Add scope API](images/addscopeapi.png)

8. Give scope name, admin consent display name, and admin consent description and click Add scope. Scope API will be created, copy those scope API Value.

    ![Add scope API configuration](images/addscopeapi1.png)

9. Get client tenant id and application id form overview page.

    ![Clinet tenat id](images/clinettenantid.png)

10. Configure those client tenant id, application id, added scope api id, and domain in your application appsettings.json file.

    ![Project configuration](images/configuration1.png)

11. Configure the scope API in client application program.cs file below highlighted place.

    ![Scope API configuration](images/scopeapiconfiguration.png)

### Run application

You can run the application and see the Syncfusion® components you selected. Select a component to see component output.

![Blazor Template output page](images/homepage.png)

You can select a culture language in combo box at top right on the output page to apply the culture in the application.

![Blazor Template output page](images/localization.png)

N> **Note:** Above culture combo box will be enabled in sample output if localization option is selected in configuration window from Syncfusion Blazor Template Studio wizard.

## Register and Login Application

### Individual Authentication

#### Blazor Web App

##### Applying Database Migrations and User Registration in the .NET 8.0 and .NET 9.0 Blazor Web App

##### Applying Database Migrations:

In the Blazor Web App, it's essential to apply pending migrations to the database before proceeding with user registration. Choose one of the following options:

**Option 1: Using Visual Studio Package Manager Console**
 
Navigate to **View -> Other Windows -> Package Manager Console** in Visual Studio.
 
Run the following command in the Package Manager Console:

   ```Update-Database```

**Option 2: Using Command Prompt**
 
Open a command prompt in your project directory and execute the following command:

   ```dotnet ef database update```

##### User Registration:

1.	Launch the application and register by submitting your email address and creating a password.

    ![Register the WebApp](images/webappregister.png)

2.	Confirm your registration by clicking **Click here to confirm your account.**

    ![Confirming the WebApp registration](images/webappregisterconfirmation.png)

3.	Submit your registered email address and password to log in to the application.

    ![LogIn to the WebApp](images/webapplogin.png)

#### Server Application, ASP.NET Core hosted Web Application, and Progressive Web Application with ASP.NET Core hosted

1. For register the application, submit your email address and create a password.

    ![Register the application](images/registerapplication.png)

2. Confirming registration by clicking **Click here to confirm your account.**

    ![Register the confirmation](images/registerconfirmation.png)

3. Submit your registered email address and password to login the application.

    ![login to the application](images/login.png)

#### Web Application and Progressive Web Application

1. Login to the application using Gmail accounts.

    ![Google login](images/googlelogin.png)

### Microsoft Identity Platform

#### Server Application, Web Application, Progressive Application, ASP.NET Core Hosted Web Application, and ASP.NET Core Hosted with Progressive Web Application

1. Login to your application using your Microsoft account.

2. Accept permission request of your application.

    ![Accept permission](images/microsoftauthentication.png)
