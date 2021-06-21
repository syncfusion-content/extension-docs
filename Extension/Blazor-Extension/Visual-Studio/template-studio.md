---
layout: post
title: Template Studio | Blazor | Syncfusion
description: Syncfusion provides the Blazor Template Studio for Blazor platform to create the Syncfusion Blazor Application using Syncfusion components
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Template Studio in Blazor Extension

Syncfusion provides the Blazor Template Studio to create a Syncfusion Blazor application with Syncfusion components. The Syncfusion Blazor application is created with the required Syncfusion NuGet references, namespaces, styles, and component render code. The Template Studio provides an easy-to-use project wizard that teaches you how to create an application with Syncfusion components.

The following steps will help you create your **Syncfusion Blazor Application** through **Visual Studio 2019**:

> Before use the Syncfusion Blazor Project Template, check whether the Syncfusion Blazor Template Studio Extension installed or not in Visual Studio Extension Manager by clicking on the Extensions -> Manage Extensions -> Installed.

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

7. Click either **Next** or the **Configuration** tab, and the Configuration section will be loaded. You can choose the required (.NET 5.0 and ASP NET Core 3.1), themes, https configuration, authentication type (None, Individual Accounts, Microsoft Identity Platform, and Windows), and Blazor Web Assembly project types (ASP.NET Core hosted and Progressive Web Application).

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

**Authentication Configuration**

**Individual Accounts Authentication**

**Web Application and Progressive Web Application**

1. Go to below credentials page for the Google cloud platform API console.

    https://console.cloud.google.com/apis/credentials?project=aerobic-furnace-244104

2. Click Create Credentials and OAuth Client Id.

    ![Google API console credentials page](images/GoogelAPIConsoleCredentials.png)

    ![Google API Oauth client Id](images/OauthclientId.png)

3. Select Application type as Web Application in client Id creation.

    ![ApplicationType](images/ClientIdApplicationtype.PNG)

4. Add your publish URL link as an Authorized URI and login URL as Redirected URI.

    ![RedirectedURI](images/RedirectedURI.png)

5. Click save then OAuth client id will be created and copy that credentials.

    ![ClientIdCreation](images/ClientIdCreation.PNG)

6. Add that Client Id, and RedirectUri in appsettings.json file of your project.

    ![ClinetIdConfiguration](images/ClinetIdConfiguration.PNG)

7. Change the build configuration bind as google from Local in program.cs file.

    ![buildconfigurationbind](images/buildconfigurationbind.PNG)

**Microsoft Identity Platform Authentication**

**Server Application**

1. Go to below Azure Active Directory App Registration page.

    https://portal.azure.com/#blade/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/RegisteredApps

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

7. Configure those client tenant id, application id, and domain in your project appsettings.json file.

    ![Project configuration](images/Configuration1.png)

**Web Application and Progressive Web Application**

1. Go to below Azure Active Directory App Registration page.

    https://portal.azure.com/#blade/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/RegisteredApps

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

8. Configure those client tenant id and application id in your project appsettings.json file.

    ![Clinet ID and Tenant ID configuration](images/ClinetTenantIdConfiguration.PNG)

**ASP.NET Core Hosted Web Application, and ASP.NET Core Hosted with Progressive Web Application**

**Client project Registration and Configuration**

1. Go to below Azure Active Directory App Registration page.

    https://portal.azure.com/#blade/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/RegisteredApps

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

8. Configure those client tenant id and application id in your project appsettings.json file.

    ![Clinet ID and Tenant ID configuration](images/ClinetTenantIdConfiguration.PNG)

**Server project Registration and configuration**

1. Go to below Azure Active Directory App Registration page.

    https://portal.azure.com/#blade/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/RegisteredApps

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

8. Give scope name, admin consent display name, and admin consent description and click Add scope.Scope API will be created, copy those scope API Value.

    ![Add scope API configuration](images/AddScopeAPI1.png)

9. Get client tenant id and application id form overview page.

    ![Clinet tenat id](images/ClinetTenantId.PNG)

10. Configure those client tenant id, application id, and domain in your project appsettings.json file.

    ![Project configuration](images/Configuration1.png)

11. Configure the scope API in client project program.cs file below highlighted place.

    ![Scope API configuration](images/ScopeAPIConfiguration.PNG)

**Run application**

You can run the application and see the Syncfusion components you selected. Select a component to see component output.
![Blazor Template output page](images/HomePage.png)

You can select a culture language in combobox at top right on the page to apply the culture in the application. 

![Blazor Template output page](images/Localization.png)

**Register and Login Application**

**Individual Authentication**

**Server Application, ASP.NET Core hosted Web Application, and Progressive Web Application with ASP.NET Core hosted**

1. For register the application, submit your email address and create a password.

    ![Register the application](images/RegisterApplication.png)

2. Confirming registration by clicking **Click here to confirm your account.**

    ![Register the confirmation](images/RegisterConfirmation.png)

3. Submit your registered email address and password to login the application.

    ![login to the application](images/Login.png)

**Web Application and Progressive Web Application**

1. Login to the application using Gmail accounts.

    ![Google login](images/GoogleLogin.PNG)

**Microsoft Identity Platform**

**Server Application, Web Application, Progressive Application, ASP.NET Core Hosted Web Application, and ASP.NET Core Hosted with Progressive Web Application**

1. Login to your application using your Microsoft account.

2. Accept permission request of your Application.

    ![Accept permission](images/MicrosoftAuthentication.PNG)

> **Note:** Above combobox will be enabled in sample output only if localization option is selected in configuration window from Blazor Template Studio wizard. 

If you installed the trial setup or NuGet packages from nuget.org you have to register the Syncfusion license key to your project since Syncfusion introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio release. Navigate to the [help topic](https://help.syncfusion.com/common/essential-studio/licensing/license-key#how-to-generate-syncfusion-license-key) to generate and register the Syncfusion license key to your project. Refer to this [blog](https://blog.syncfusion.com/post/Whats-New-in-2018-Volume-2-Licensing-Changes-in-the-1620x-Version-of-Essential-Studio.aspx?_ga=2.11237684.1233358434.1587355730-230058891.1567654773) post for understanding the licensing changes introduced in Essential Studio.