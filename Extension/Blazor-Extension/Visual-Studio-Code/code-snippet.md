---
layout: post
title: Code Snippet | Blazor | Syncfusion
description: Code snippet adding a Syncfusion Blazor component with various features in the Razor code editor file of the Blazor Application.
platform: extension
control: Syncfusion Extensions
documentation: ug
---

## Add the Syncfusion Blazor component

The Syncfusion Blazor code snippet utility for Visual Studio Code provides snippets for adding a Syncfusion Blazor component with various features in the Razor code editor file of the Blazor Application.

   > The Syncfusion Blazor code snippet is available from Essential Studio 2021 Volume 1 (`v19.1.0.54`).

The following steps help you to use the Syncfusion Blazor code snippet in your Blazor Application.

1. Open an existing Blazor Application or create a new Blazor Application in Visual Studio Code.

2. Open the required razor file.

3. You can find the Syncfusion Blazor component with the various features by typing the word in the following format.

    ```bash
    sf<Syncfusion component name>-<Syncfusion component feature>

    For Example, sfgrid-grouping
    ```
    Choose the Syncfusion component and click the **Enter or Tab** key, the Syncfusion Blazor component will be added in the razor file.

    ![Code Snippet](../images/codesnippet.gif)

    After adding the Syncfusion Blazor component in the razor file, use the tab key to fill the required values to render the component. You can find the comment section in the code snippet to find what are values need to fill.

    ![Comment](../images/Comment.png)

    Also, you can find the Syncfusion help link at the top of the added snippet to know more about the added Syncfusion Blazor component feature.

    ![Help](../images/Help.png)

## Configure Blazor application

The Syncfusion Blazor snippet only adds the code in the razor file. You need to configure the Blazor application with Syncfusion by adding the required Syncfusion Blazor NuGet, namespace, themes, and register the Syncfusion Blazor Service. Refer to the following steps to configure:

1. Open the Blazor project file and add the required Syncfusion Blazor individual NuGet package(s) for the Syncfusion Blazor components as a package reference manually. Refer to this section to know the benefits of the individual NuGet packages. This NuGet package will be automatically restored when building the application.

    ![NuGet Package](../images/NuGet-Snippet.png)

    > Starting with Volume 4, 2020 (v18.4.0.30) release, Syncfusion provides [individual NuGet packages](https://blazor.syncfusion.com/documentation/nuget-packages/) for our Syncfusion Blazor components. We highly recommend this new standard for your Blazor production applications.

2. Open the **~/_Imports.razor** file and add the required Syncfusion Blazor namespace entries to render the Syncfusion components in your application.

    ![Namespace](../images/Namespace-Snippet.png)

3. Add the Syncfusion Blazor theme in the `<head>` element of the **~/Pages/_Host.html** page for server application and **~/wwwroot/index.html** page for a client application.

    ![Themes](../images/Themes-Snippet.png)

4. Open the **~/Startup.cs** file for server application and the **~/Program.cs** file for client application then register the Syncfusion Blazor Service.

    ![Syncfusion Configuration](../images/Configuration-Snippet.png)

5. If you installed the trial setup or NuGet packages from nuget.org you have to register the Syncfusion license key to your project since Syncfusion introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio release. Navigate to the [help topic](https://help.syncfusion.com/common/essential-studio/licensing/license-key#how-to-generate-syncfusion-license-key) to generate and register the Syncfusion license key to your project. Refer to this [blog](https://blog.syncfusion.com/post/Whats-New-in-2018-Volume-2-Licensing-Changes-in-the-1620x-Version-of-Essential-Studio.aspx?_ga=2.11237684.1233358434.1587355730-230058891.1567654773) post for understanding the licensing changes introduced in Essential Studio.