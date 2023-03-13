---
layout: post
title: Code Snippet | Blazor | Syncfusion
description: Code snippet adding a Syncfusion Blazor component with various features in the Razor code editor file of the Blazor Application.
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Add Syncfusion Blazor component in the Blazor application

The Syncfusion Blazor code snippet utility for Visual Studio Code includes snippets for inserting a Syncfusion Blazor component with various features into the Blazor Application's Razor code editor.

   > The Syncfusion Blazor code snippet is available from Essential Studio 2021 Volume 1 (`v19.1.0.54`).

## Add a Syncfusion Blazor component

The instructions below guide you the process of using the Syncfusion Blazor code snippet in your Blazor application.

1. In Visual Studio Code, open an existing Blazor Application or create a new Blazor Application.

2. Open the razor file that you need and place the cursor in required place where you want to add Syncfusion component.

3. You can find the Syncfusion Blazor component with the various features by typing the **sf** word in the format shown below.

    ```bash
    sf<Syncfusion component name>-<Syncfusion component feature>

    For Example, sfgrid-grouping
    ```
4. Choose the Syncfusion component and click the **Enter** or **Tab** key, the Syncfusion Blazor component will be added in the razor file.

    ![Code Snippet](images/codesnippet.gif)

5. After adding the Syncfusion Blazor component to the razor file, use the tab key to fill in the required values to render the component with data. You can find the comment section in the code snippet to see what values are required.

    ![Comment](images/Comment.png)

6. You can also find the Syncfusion help link at the top of the added snippet to learn more about the new Syncfusion Blazor component feature.

    ![Help](images/Help.png)

## Configure Blazor application with Syncfusion

The Syncfusion Blazor snippet simply inserts the code into the razor file. You must configure the Blazor application with Syncfusion by installing the Syncfusion Blazor NuGet package, namespace, themes, and registering the Syncfusion Blazor Service. To configure, follow the steps below:

1. Open the Blazor application file and manually add the required Syncfusion Blazor individual NuGet package(s) for the Syncfusion Blazor components as a package reference. Refer to [this section](https://blazor.syncfusion.com/documentation/nuget-packages/#benefits-of-using-individual-nuget-packages) to learn about the advantages of the individual NuGet packages. This NuGet package will be automatically restored when building the application.

    ![NuGet Package](images/NuGet-Snippet.png)

    > Starting with Volume 4, 2020 (v18.4.0.30) release, Syncfusion provides [individual NuGet packages](https://blazor.syncfusion.com/documentation/nuget-packages/) for our Syncfusion Blazor components. We highly recommend this new standard for your Blazor production applications.

2. To render the Syncfusion components in your application, open the **~/_Imports.razor** file and add the required Syncfusion Blazor namespace entries.

    ![Namespace](images/Namespace-Snippet.png)

3. Add the Syncfusion Blazor [theme](https://blazor.syncfusion.com/documentation/appearance/themes/) in the `<head>` element of the **~/Pages/_Host.html** page for server application and **~/wwwroot/index.html** page for a client application.

    ![Themes](images/Themes-Snippet.png)

4. Open the **~/Startup.cs** file for server application and the **~/Program.cs** file for client application then register the Syncfusion Blazor Service.

    ![Syncfusion Configuration](images/Configuration-Snippet.png)

5. If you installed the trial setup or NuGet packages from nuget.org you must register the Syncfusion license key to your application since Syncfusion introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio release. Navigate to the [help topic](https://help.syncfusion.com/common/essential-studio/licensing/overview#how-to-generate-syncfusion-license-key) to generate and register the Syncfusion license key to your application. Refer to this [blog](https://www.syncfusion.com/blogs/post/whats-new-in-2018-volume-2.aspx) post for understanding the licensing changes introduced in Essential Studio.