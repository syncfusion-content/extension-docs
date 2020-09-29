---
layout: post
title: Project Templates | Angular | Syncfusion
description: Syncfusion provides Visual Studio Code Project Templates for Angular platform to create the Syncfusion Angular Application using Syncfusion components
platform: extension
control: Syncfusion Extensions
documentation: ug
---

## Create project

Syncfusion provides **project templates** for **VisualStudio Code** to create Syncfusion Angular applications. Syncfusion Angular creates applications with the required Syncfusion NPM packages, and component render code for the Grid, Chart, and Scheduler components, and the style for making development easier with Syncfusion components.

   > The Syncfusion Visual Studio Code project template provides support for Angular project templates from v18.3.0.*.

The following steps help you create **Syncfusion Angular Applications** through the **Visual Studio Code:**

1. In Visual Studio Code, open the command palette by pressing **Ctrl+Shift+P**. The Visual Studio Code palette opens, search the word **Syncfusion** so you can get the templates provided.

    ![CreateProjectPalette](../images/CreateProjectPalette.png)

2. Select **Create Syncfusion Angular Project** and then press **Enter**. The **Project Location** palette appears to store the application.

    ![ProjectLocation](../images/ProjectLocation.png)

3. Provide the destination location and then press **Enter**. The **Project Name** palette appears. Provide the name of the application and enter.  

    ![ProjectName](../images/ProjectName.png)

4. The palette of theme selection appears. Choose the preferred theme and then click Enter. The project will be created.

    ![Themes](../images/Themes.png)

5. The created Syncfusion Angular app is configured with the Syncfusion NPM packages, styles, and the component render code for the Syncfusion component added.

    ![NPM Packages](../images/npm-install.png)

    ![Styles](../images/styles.png)

    ![Components](../images/components.png)

## Run the application

To run the application,follow the below steps.

1. Open the terminal window by go to **Terminal -> New Terminal**

2. Then run the **npm install** command to restore the NPM packages.

    ![NPM Command](../images/npm-command.png)

3. Now, run the **ng serve** command to compile the Syncfusion Angular application.

    ![NG Command](../images/ng-command.png)

    > To run the ng serve command, you should be installed the Angular CLI by using the command **npm install -g @angular/cli**

4. After compilation process completed, open the local host link in browser to see the output.

    ![Output](../images/output.png)
