---
layout: post
title: Scaffolding | Blazor | Syncfusion
description: Code-generation Framework for Syncfusion Blazor platform to quickly create the Controller and Razor in a short time.
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Syncfusion Blazor Scaffolding

Syncfusion provides **Visual Studio Scaffolding** for Syncfusion Blazor platform to quickly add code that interacts with data models and reduce the amount of time to develop with data operation in your project. Scaffolding provides an easier way to create Razor and Controller action methods for Syncfusion Blazor DataGrid, Charts, Scheduler, Diagram, Tree Grid, Rich Text Editor, Document Editor, and PDF Viewer controls.

N>Check that at least one Entity Framework model exists, and the application has been compiled once. If no Entity Framework model exist in your application, refer to this [documentation](https://www.freecodecamp.org/news/how-to-create-an-application-using-blazor-and-entity-framework-core-1c1679d87c7e/) to generate the Entity Framework model. After the model file has been added, check that the required DBContext and properties are added. Now, build the application, and try scaffolding. If any changes made in the model properties, rebuild the application once before perform scaffolding.

I>The Syncfusion Blazor Scaffolder is available from v17.4.0.39 for Blazor server-side application and provided the Scaffolding support to Blazor client-side application from v18.4.0.39.

## Add a scaffolded item

The following steps explains how to add a scaffolded item to your Blazor application.

> Before use the Syncfusion Blazor Scaffolding, check whether the Syncfusion Blazor Template Studio Extension installed or not in Visual Studio Extension Manager by clicking on the Extensions -> Manage Extensions -> Installed.

1. If the project type is **Blazor ServerSide**, right-click the **Pages** folder in the Solution Explorer, click **Add**, and then select **New Scaffolded Item..** 

   ![Scaffolded add-in from server project](images/Add_scaffold_Serverside.png)

   If the project type is **Blazor Hosted**, right-click the **Controllers** folder from **{Project Name}.Server** project in the Solution Explorer, click **Add**, and then select **New Scaffolded Item**.
   
   ![Scaffolded add-in from hosted project](images/Add_scaffold_hosted.png)
   
2. In the **Add Scaffold** dialog, select **Syncfusion Blazor Scaffolder** and then click **‘Add’**.   

   ![Choose Syncfusion Scaffolding from Visual Studio Add scaffold dialog](images/Syncfusion_scaffolder.png)

3. In the Syncfusion UI Scaffolder dialog, select the desired control to perform scaffolding, and then click **Next**.

   ![Choose required control](images/Control_Window.png)

N>Scheduler control is not applicable for Blazor Hosted application.

4. Syncfusion UI Scaffolder dialog will be opened for the selected control. Enter the **Controller/Service** Name and **Razor** Name as application requirements, and then select the required **Model Class** of the active project and its relevant **Data Context Class**, and then click **Next**.

   ![Choose required Model](images/Model_Window.png)

5. Syncfusion UI Scaffolder for the selected control feature dialog will open. Select the required features, update the required data field, and then click **Add**.

	For **ServerSide Application**, both Local data and Remote data types will be available.
	
	![Choose required selected control features for serverside project](images/Feature_Window_serverside.png)
	
	For **Hosted Application**, Remote data type only available.
	
	![Choose required selected control features for hosted project](images/Fetaure_window_hosted.png)
	
6. The **Controller/Service** file and the corresponding **Razor** files are generated with the selected features of Syncfusion control code snippet.	
	
	If you select **Local Data**, service file and razor file will be added to the project.
	
	![Required Controller and Razor files added in the project for the selected control](images/Files_for_local_data.png)
	
	If you select **Remote Data**, controller file and razor file will be added to the project.
	![Required Controller and Razor files added in the project for the selected control](images/Files_for_remote_data.png)
	
7. Then, add navigation to the created razor file based on your requirement to open in the webpage.

8. If you installed the trial setup or NuGet packages from nuget.org you have to register the Syncfusion license key to your project since Syncfusion introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio release. Navigate to the [help topic](https://help.syncfusion.com/common/essential-studio/licensing/license-key#how-to-generate-syncfusion-license-key) to generate and register the Syncfusion license key to your project. Refer to this [blog](https://blog.syncfusion.com/post/Whats-New-in-2018-Volume-2-Licensing-Changes-in-the-1620x-Version-of-Essential-Studio.aspx?_ga=2.11237684.1233358434.1587355730-230058891.1567654773) post for understanding the licensing changes introduced in Essential Studio.

## Syncfusion Blazor Command-line Scaffolding

Syncfusion provides **Scaffolding command-line** for Syncfusion ASP.NET Core to quickly add code that interacts with data models and reduce the amount of time to develop with data operation in your project. Scaffolding provides an easier way to create view file and Controller action methods for Syncfusion Blazor DataGrid, Charts, Scheduler, Diagram, Tree Grid, Rich Text Editor, Document Editor, and PDF Viewer controls.

N> Check that at least one Entity Framework model exists. If no Entity Framework model exist in your application, refer to this [documentation](https://www.freecodecamp.org/news/how-to-create-an-application-using-blazor-and-entity-framework-core-1c1679d87c7e/) to generate the Entity Framework model. After the model file has been added, check that the required DBContext and properties are added. Now, build the application, and try scaffolding. If any changes made in the model properties, rebuild the application once before perform scaffolding.

## Install Command-line Scaffolding

Install **syncfusion.scaffolding** tool globally by using below command.

**dotnet tool install -g syncfusion.scaffolding** 

## Update Command-line scaffolding

Update **syncfusion.scaffolding** tool globally by using below command. 

**dotnet tool update -g syncfusion.scaffolding** 

## Add a scaffolded item from command-line

The following steps explains how to add a scaffolded item from command-line to your Blazor application.

1. After installed syncfusion.scaffolding tool, we can invoke syncfusion_scaffold command it shows the available controls

	**syncfusion_scaffold**
	
	![CommandLine Scaffold Available Controls](images/AvailableControl.png)
	
2. To add a scaffolded item from command-line you have to invoke syncfusion_scaffold application like below syntax	
	
	**syncfusion_scaffold [control][arguments]**

	
	| Parameter                         | Description                                                                   | Control           |
	|-----------------------------------|-------------------------------------------------------------------------------|-------------------|
	| -p&#124;--project                 |  Path to .csproj file in the project.                                         |  All Controls     | 
	| -cname&#124;--controller-filename | Name of controller file to be added in project.                               | All controls      |
	| -vname&#124;--view-filename       | Name of view file to be added in project.                                     | All Controls      |
	| -m&#124;--model                   | Database model name with namespace (example: WebApplication1.Models.Tasks).   | All Controls      |
	| -dc&#124;--db-context             | DbContext name with namespace (example: WebApplication1.Models.TasksContext). | All Controls      |
	| -pkey&#124;--primary-key          | Set Feature name/column name as primarykey.                                   | DataGrid/TreeGrid |
	| -tid&#124;--treegrid-id           | Id of Tasks.                                                                  | TreeGrid          |
	| -pid&#124;--parent-id             | ParentId value                                                                | TreeGrid/Diagram  |
	| -x&#124;--x-axis                  | Xaxis of Chart                                                                | Charts            |
	| -Y&#124;--Y-axis                  | Y-axis of Chart                                                               | Charts            |
	| -sid&#124;--scheduler-id          | Id of Scheduler Event.                                                        | Scheduler         |
	| -stime&#124;--start-time          | StartTime of Scheduler Event.                                                 | Scheduler         |
	| -etime&#124;--end-time            | EndTime of Scheduler Event.                                                   | Scheduler         |
	| --is-all-day                  	| Set IsALLDay for Scheduler Event.                                             | Scheduler         |
	| -did&#124;--diagram-id            | Id of Diagram layout.                                                         | Diagram           |	

2. If you run the syncfusion_scaffold [control] command, the parameters of control shown like below image.
	
	![control parameter details](images/controlparameter.png)
	
3. Run the following command to generate controller and view files through command-line by passing required arguments of the given control.
	
	**syncfusion_scaffold {controlName} --project "{projectFileNamewithPath}" --model {model} -dc {dbContext} -cname {controllerName} -vname {viewName} [controlMantoryParameter] [controlMantatoryParameterValue]**
	
	![CommandLine Scaffold](images/commandline.png)
	
4.  As we can see controller and view files generated successfully and also added the Syncfusion NuGet packages and styles which is required to render Syncfusion control.
		
	![Blazor added Files](images/blazorfile.png)
	![Blazor Service Changes](images/blazorstyle.png)
	
## How to render Syncfusion control?	
	
Refer to the following UG links to render Syncfusion control after performing scaffolding:

WebAssembly App: [Configure Blazor controls using Syncfusion.EJ2.Blazor NuGet Package](https://ej2.syncfusion.com/blazor/documentation/getting-started/vs-blazor/)

Blazor Server App: [Configure Blazor controls using Syncfusion.EJ2.Blazor NuGet Package](https://ej2.syncfusion.com/blazor/documentation/getting-started/vs-blazor-server/)
	