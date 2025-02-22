---
layout: post
title: Code Snippet | Angular | Syncfusion
description: Code snippet adding a Syncfusion Angular component with various features in the HTML code editor file of the Angular Application.
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Add Syncfusion<sup style="font-size:70%">&reg;</sup> Angular component in the Angular application

The Syncfusion<sup style="font-size:70%">&reg;</sup> Angular code snippet utility for Visual Studio Code provides snippets for adding a Syncfusion<sup style="font-size:70%">&reg;</sup> Angular component with various features in the html code editor file of the Angular Application.

   > The Syncfusion<sup style="font-size:70%">&reg;</sup> Angular code snippet is available from Essential Studio<sup style="font-size:70%">&reg;</sup> 2021 Vol 3 (`v19.3.0.43`).

## Add a Syncfusion<sup style="font-size:70%">&reg;</sup> Angular component

The following steps help you to use the Syncfusion<sup style="font-size:70%">&reg;</sup> Angular code snippet in your Angular Application.

1. In Visual Studio Code, open an existing Angular Application or create a new Angular Application.

2. Open the html file that you need and place the cursor in required place where you want to add Syncfusion<sup style="font-size:70%">&reg;</sup> component.

3. You can find the Syncfusion<sup style="font-size:70%">&reg;</sup> Angular component with the various features by typing the **ejs** word in the format shown below.

    ```bash
    ejs-<Syncfusion<sup style="font-size:70%">&reg;</sup> component name>-<Syncfusion<sup style="font-size:70%">&reg;</sup> component feature>

    For Example, ejs-grid-grouping
    ```
4. Choose the Syncfusion<sup style="font-size:70%">&reg;</sup> component and click the **Enter** or **Tab** key, the Syncfusion<sup style="font-size:70%">&reg;</sup> Angular component will be added in the html file.

    ![Code Snippet](images/codesnippet.gif)

5. After adding the Syncfusion<sup style="font-size:70%">&reg;</sup> Angular component to the html file, use the tab key to fill in the required values to render the component with data. You can also find the Syncfusion<sup style="font-size:70%">&reg;</sup> help link at the top of the added snippet to learn more about the new Syncfusion<sup style="font-size:70%">&reg;</sup> Angular component feature.

    ![Help](images/Help.png)

## Configure Angular application with Syncfusion<sup style="font-size:70%">&reg;</sup>

The Syncfusion<sup style="font-size:70%">&reg;</sup> Angular snippet only add the code snippet alone in the html file. You need to configure the Angular application with Syncfusion<sup style="font-size:70%">&reg;</sup> by adding the required Syncfusion<sup style="font-size:70%">&reg;</sup> Angular NPM, component modules, and themes by manually. To configure, refer the steps below:

1. Open the Angular package.json file and add the required Syncfusion<sup style="font-size:70%">&reg;</sup> Angular individual NPM package(s) for the Syncfusion<sup style="font-size:70%">&reg;</sup> Angular components manually. Then navigate to the packages.json file location in the command prompt and run the ***npm install*** command to restore all the Syncfusion<sup style="font-size:70%">&reg;</sup> Angular NPM packages.

    ![NPM Package](images/NPM.png)

2. Open your module file and add the required Syncfusion<sup style="font-size:70%">&reg;</sup> Angular component(s) module entries to render the Syncfusion<sup style="font-size:70%">&reg;</sup> components in your application. 

    ![Module](images/Module.png)

3. Add the Syncfusion<sup style="font-size:70%">&reg;</sup> Angular [theme](https://ej2.Syncfusion.com/documentation/appearance/theme/) entry in the **style.css** file.

    ![Themes](images/Themes-Snippet.png)