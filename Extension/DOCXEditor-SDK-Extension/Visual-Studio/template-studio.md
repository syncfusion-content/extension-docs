---
layout: post
title: Template Studio in DOCX Editor SDK - Syncfusion
description: Learn to create Blazor and WPF applications using the Syncfusion® DOCX Editor SDK with Template Studio support.
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Syncfusion® DOCX Editor SDK Template Studio

Syncfusion® provides the DOCX Editor SDK Template Studio, which allows you to create a Syncfusion application based on the platform selection, such as Blazor and WPF, using the Syncfusion® DOCX Editor SDK component. The Syncfusion® application is created with the required Syncfusion® NuGet references, namespaces, styles, and component render code. The Template Studio includes an easy-to-use project wizard that guides you through the process of creating an application with the Syncfusion® DOCX Editor SDK component.

The steps below will assist you in creating your **Syncfusion® Application** through **Visual Studio**:

N> Before using the Syncfusion® Project Template, check whether the Syncfusion® DOCX Editor SDK Template Studio Extension is installed in the Visual Studio Extension Manager by clicking on Extensions -> Manage Extensions -> Installed. If this extension is not installed, install the extension by following the steps in the [download and installation](https://help.Syncfusion.com/extension/docxeditor-sdk-extension/visual-studio/download-and-installation) help topic.

1. Open Visual Studio 2022 or later.

2. To create a Syncfusion® application, use either one of the following options:

     **Option 1**

     Choose **Extension -> Syncfusion -> Essential Studio® for DOCX Editor SDK -> Create New Syncfusion Project...** from the **Visual Studio menu**.

     ![CreateMenu](images/createmenu.png)

     **Option 2**

     Choose **File -> New -> Project** from the menu. This launches a new dialog for creating a new application. Syncfusion® templates can be found by filtering the application type for **Syncfusion** or by entering **Syncfusion** as a keyword in the search option.

     ![CreateNewWindow](images/CreateNewWindow.png)

3. Select the **Syncfusion® DOCX Editor SDK Template Studio** and click **Next**.

     ![CreateNewWizard](images/CreateNewWizard.png)

4. The Syncfusion® DOCX Editor SDK Template Studio wizard will be launched. Select the platform to add the Syncfusion® DOCX Editor SDK component.

    ![PlatformSelection](images/Platform.png)

5. Based on the platform selection, choose the configurations and create the respective application to add the Syncfusion® DOCX Editor SDK component.

    - Blazor Platform:
        
        -  **Project type section**
        
            Choose one of the Syncfusion® Blazor application types based on the version of the .NET SDK you are using.

            | .NET SDK version | Supported Syncfusion Blazor Application Type |
            | ---------------- | -------------------------------------------- |
            | [.NET 10.0](https://dotnet.microsoft.com/en-us/download/dotnet/10.0), [.NET 9.0](https://dotnet.microsoft.com/en-us/download/dotnet/9.0), [.NET 8.0](https://dotnet.microsoft.com/en-us/download/dotnet/8.0) | Syncfusion Blazor Web App |
            | [.NET 10.0](https://dotnet.microsoft.com/en-us/download/dotnet/10.0), [.NET 9.0](https://dotnet.microsoft.com/en-us/download/dotnet/9.0), [.NET 8.0](https://dotnet.microsoft.com/en-us/download/dotnet/8.0) | Syncfusion Blazor WebAssembly App |

            > **Note:** Refer to the .NET SDK support for Syncfusion Blazor component [here](https://blazor.syncfusion.com/documentation/system-requirements#net-sdk).

            In the **Syncfusion Blazor Web App** application type, you can configure the following options:

            <table>
            <tbody>
            <tr>
            <td>
            <a href="https://learn.microsoft.com/en-us/aspnet/core/blazor/component/render-modes?view=aspnetcore-8.0#render-modes" rel="nofollow">Interactivity type</a>
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

            In the **Syncfusion Blazor WebAssembly App** application type, you can choose the Progressive Web Application.

            ![WASMTemplate](images/wasmtemplate.png)

            > **Note:** The Progressive Web Application will be enabled if the .NET 8.0 version or higher is installed.
            
            You can choose the required .NET version (.NET 10.0, .NET 9.0, and .NET 8.0), themes, HTTPS configuration, authentication type, Blazor Web App, and Blazor WebAssembly application types.

            Depending on your Syncfusion Blazor Application Type, refer to the table below for supported authentication types.

            | Syncfusion Blazor Application Type | Supported Authentication Types |
            | ------------- | ------------- |
            | Syncfusion Blazor Web App | None and Individual Accounts |
            | Syncfusion Blazor WebAssembly App | None, Individual Accounts, and Microsoft Identity Platform |
            
            Click the **Create** button. The Syncfusion® Blazor application has been created. The created Syncfusion® Blazor app has the Syncfusion NuGet packages, styles, and the render code for the Syncfusion® DOCX Editor SDK component.

     - WPF Platform

         - **Configuration Section**

            You will have the option to specify your preferred .NET Framework version, select the desired language (C# or Visual Basic), and choose the reference type according to your requirements.

            ![Configuration](images/Config.png)

            > **Note:** The installed location and GAC options will be available only after the Syncfusion® Essential® DOCX Editor SDK setup has been installed. Use the NuGet option instead of installing the Syncfusion® Essential® DOCX Editor SDK setup. Also, the GAC option will not be available when you choose .NET 6.0, .NET 7.0, or .NET 8.0 from the project type option in Visual Studio.

            Click the **Create** button. The Syncfusion® WPF application has been created. The created application has the Syncfusion NuGet packages, styles, and the render code for the Syncfusion® DOCX Editor SDK component.

9. The Syncfusion® application based on the platform selection is configured with the most recent Syncfusion® NuGet package version, selected style, namespaces, selected authentication, and component render code for the Syncfusion® DOCX Editor SDK component.

10. If you have installed the trial setup or NuGet packages from nuget.org, you must register the Syncfusion® license key to your application since Syncfusion® introduced the licensing system from the 2018 Volume 2 (v16.2.0.41) Essential Studio® release. Navigate to the [help topic](https://help.syncfusion.com/common/essential-studio/licensing/overview#how-to-generate-syncfusion-license-key) to generate and register the Syncfusion® license key to your application. Refer to this [blog](https://www.syncfusion.com/blogs/post/whats-new-in-2018-volume-2.aspx) post to understand the licensing changes introduced in Essential Studio®.

## Authentication Configuration for the Blazor Platform

You need to register the created application in the Google API Console for Individual Accounts and in Azure Active Directory for the Microsoft Identity Platform. From the Google API Console registration, you can obtain the client ID for Individual Accounts. From the Azure Active Directory registration, you can obtain the tenant ID and application client ID for the Microsoft Identity Platform. You need to configure these ID values in the created applications; only then will the application run correctly with authentication support.

### Individual Accounts Authentication

#### Web Application and Progressive Web Application

1. Go to the credentials page below for the Google Cloud Platform API Console.

    <https://console.cloud.google.com/apis/credentials?project=aerobic-furnace-244104&pli=1>

2. Click Create Credentials and OAuth Client ID.

    ![Google API console credentials page](images/GoogelAPIConsoleCredentials.png)

    ![Google API Oauth client Id](images/OauthclientId.png)

3. Select the application type as Web Application in the client ID creation.

    ![ApplicationType](images/ClientIdApplicationtype.png)

4. Add your publish URL link as an Authorized URI and the login URL as the Redirect URI.

    ![RedirectedURI](images/RedirectedURI.png)

5. Click Save, then the OAuth client ID will be created, and copy that credential.

    ![ClientIdCreation](images/ClientIdCreation.png)

6. Add that Client ID and Redirect URI in the appsettings.json file of your application.

    ![ClinetIdConfiguration](images/ClinetIdConfiguration.png)

7. Change the build configuration bind to Google from Local in the Program.cs file.

    ![buildconfigurationbind](images/buildconfigurationbind.png)

### Microsoft Identity Platform Authentication

#### Server Application

1. Go to the Azure Active Directory App Registration page below.

    <https://portal.azure.com/#view/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/~/RegisteredApps>

2. Click New Registration in the App Registration page.

    ![AppRegistration](images/AppRegistration.png)

3. Give the name of the application and select the supported type as single tenant.

    ![Name and supported Account type](images/NameSupportedAccountType.png)

4. Scroll down the page, select the platform as Web, and give your application Redirect URI like {Redirect URI}/signin-oidc, and click Register.

    ![Platform and Redirect URI](images/aadredirecteduri.png)

5. The app will be registered. Go to the Authentication page and tick the Id token check box.

    ![Access token and Id token](images/AuthenticationCheckBox.png)

6. Get the client tenant ID and application ID from the overview page.

    ![Clinet tenat id](images/ClinetTenantId.png)

7. Configure the client tenant ID, application ID, and domain in your application's appsettings.json file.

    ![Project configuration](images/Configuration1.png)

#### Web Application and Progressive Web Application

1. Go to the Azure Active Directory App Registration page below.

    <https://portal.azure.com/#view/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/~/RegisteredApps>

2. Click New Registration in the App Registration page.

    ![AppRegistration](images/AppRegistration.png)

3. Give the name of the application and select the supported type as single tenant.

    ![Name and supported Account type](images/NameSupportedAccountType.png)

4. Scroll down the page, select the platform as Web, and give your application Redirect URI, and click Register.

    ![Platform and Redirect URI](images/aadredirecteduri.png)

5. The app will be registered. Go to the Authentication page and tick the Access token and Id token check boxes.

    ![Access token and Id token](images/AuthenticationCheckBox.png)

6. Migrate the API by clicking the highlighted arrow as shown in the image below.

    ![API Migration](images/Migration1.png)

    ![Migration configuration](images/Migration2.png)

7. Get the client tenant ID and application ID from the overview page.

    ![Clinet tenat id](images/ClinetTenantId.png)

8. Configure the client tenant ID and application ID in your application's appsettings.json file.

    ![Clinet ID and Tenant ID configuration](images/ClinetTenantIdConfiguration.png)

#### ASP.NET Core Hosted Web Application, and ASP.NET Core Hosted with Progressive Web Application

##### Client Project Registration and Configuration

1. Go to the Azure Active Directory App Registration page below.

    <https://portal.azure.com/#view/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/~/RegisteredApps>

2. Click New Registration in the App Registration page.

    ![AppRegistration](images/AppRegistration.png)

3. Give the name of the application and select the supported type as single tenant.

    ![Name and supported Account type](images/NameSupportedAccountType.png)

4. Scroll down the page, select the platform as Web, and give your application Redirect URI, and click Register.

    ![Platform and Redirect URI](images/aadredirecteduri.png)

5. The app will be registered. Go to the Authentication page and tick the Access token and Id token check boxes.

    ![Access token and Id token](images/AuthenticationCheckBox.png)

6. Migrate the API by clicking the highlighted arrow as shown in the image below.

    ![API Migration](images/Migration1.png)

    ![Migration configuration](images/Migration2.png)

7. Get the client tenant ID and application ID from the overview page.

    ![Clinet tenat id](images/ClinetTenantId.png)

8. Configure the client tenant ID and application ID in your application's appsettings.json file.

    ![Clinet ID and Tenant ID configuration](images/ClinetTenantIdConfiguration.png)

##### Server Project Registration and Configuration

1. Go to the Azure Active Directory App Registration page below.

    <https://portal.azure.com/#view/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/~/RegisteredApps>

2. Click New Registration in the App Registration page.

    ![Server App Registration](images/AppRegistration.png)

3. Give the name of the application and select the supported type as single tenant.

    ![Name and supported Account type](images/NameSupportedAccountType.png)

4. Scroll down the page, select the platform as Web, and give your application Redirect URI, and click Register.

    ![Server Platform and Redirect URI](images/aadredirecteduri.png)

5. The app will be registered. Go to the Authentication page and tick the Access token and Id token check boxes.

    ![Access token and Id token](images/AuthenticationCheckBox.png)

6. Migrate the API by clicking the highlighted arrow as shown in the image below.

    ![API Migration](images/Migration1.png)

    ![Migration configuration](images/Migration2.png)

7. Add a scope API in the Expose an API page.

    ![Add scope API](images/AddScopeAPI.png)

8. Give the scope name, admin consent display name, and admin consent description, and click Add scope. The scope API will be created; copy the scope API value.

    ![Add scope API configuration](images/AddScopeAPI1.png)

9. Get the client tenant ID and application ID from the overview page.

    ![Clinet tenat id](images/ClinetTenantId.png)

10. Configure the client tenant ID, application ID, added scope API ID, and domain in your application's appsettings.json file.

    ![Project configuration](images/Configuration1.png)

11. Configure the scope API in the client application's Program.cs file at the highlighted place below.

    ![Scope API configuration](images/ScopeAPIConfiguration.PNG)

### Run the Application

You can run the application and see the Syncfusion® DOCX Editor SDK component you selected.

![Blazor Template output page](images/HomePage.png)

## Register and Login Application

### Individual Authentication

#### Blazor Web App

##### Apply Database Migrations and User Registration in the .NET 8.0, .NET 9.0, and .NET 10.0 Blazor Web App

##### Applying Database Migrations:

In the Blazor Web App, it is essential to apply pending migrations to the database before proceeding with user registration. Choose one of the following options:

**Option 1: Using the Visual Studio Package Manager Console**
 
Navigate to **View -> Other Windows -> Package Manager Console** in Visual Studio.
 
Run the following command in the Package Manager Console:

   ```Update-Database```

**Option 2: Using the Command Prompt**
 
Open a command prompt in your project directory and execute the following command:

   ```dotnet ef database update```

##### User Registration:

1.	Launch the application and register by submitting your email address and creating a password.

    ![Register the WebApp](images/WebAppRegister.png)

2.	Confirm your registration by clicking **Click here to confirm your account.**

    ![Confirming the WebApp registration](images/WebAppRegisterConfirmation.png)

3.	Submit your registered email address and password to log in to the application.

    ![LogIn to the WebApp](images/WebApplogIn.png)

#### Server Application, ASP.NET Core Hosted Web Application, and Progressive Web Application with ASP.NET Core Hosted

1. To register the application, submit your email address and create a password.

    ![Register the application](images/RegisterApplication.png)

2. Confirm your registration by clicking **Click here to confirm your account.**

    ![Register the confirmation](images/RegisterConfirmation.png)

3. Submit your registered email address and password to log in to the application.

    ![login to the application](images/Login.png)

#### Web Application and Progressive Web Application

1. Log in to the application using Gmail accounts.

    ![Google login](images/GoogleLogin.png)

### Microsoft Identity Platform

#### Server Application, Web Application, Progressive Application, ASP.NET Core Hosted Web Application, and ASP.NET Core Hosted with Progressive Web Application

1. Log in to your application using your Microsoft account.

2. Accept the permission request of your application.

    ![Accept permission](images/MicrosoftAuthentication.png)
