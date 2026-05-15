---
layout: post
title: Getting Started | Essential® UI Kit for .NET MAUI Plugin | Syncfusion
description: How to add and use the Essential® UI Kit for .NET MAUI Syncfusion templates in your .NET MAUI project (JetBrains Rider guidance).
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Essential® UI Kit for .NET MAUI

This guide explains how to integrate Syncfusion® MAUI UI Kit templates into a .NET MAUI project using JetBrains Rider, providing ready-to-use XAML pages along with corresponding View and ViewModel classes, resource files, and all necessary Syncfusion® NuGet package references.

N> Before using the **Essential® UI Kit for .NET MAUI - Syncfusion<sup>®</sup>**, ensure that the plugin is installed in JetBrains Rider. To check, go to **Settings > Plugin >Installed** . If the plugin is not installed, follow the steps in the [download and installation](download-and-installation) help guide to install it.

**Add UI Kit templates to a .NET MAUI project**

1. Open your .NET MAUI project in Rider and right‑click the project and choose `Tools` → `Essential UI Kit for .NET MAUI`.

	![Syncfusion Essential UI Kit for .NET MAUI Context menu in MAUI](images/Menu.png)

2. The category dialogue wizard will open with pre-defined templates.

	![Add new item dialog box](images/Maui-Wizard.png)

3. Choose one or more page templates (for example, `About Us Page With Cards`), then click `Next`.

4. Enter a name for the new page and click `Add` to scaffold the XAML page, View, ViewModel, model classes, and resources.

	![Edit page Name in MAUI UI Kit Plugin](images/Edit-Wizard.png)

5. The selected pages will be added along with View, View Model, Model classes, resource files and Syncfusion® NuGet package reference.

	![Added files in MAUI Project](images/ViewFiles.png)

	![Added Resources in MAUI Project](images/Resources.png)

	![Added NuGet in MAUI Project](images/Packages.png)

6. Syncfusion® licensing registration required message box will be shown if you installed the trial setup or NuGet packages since Syncfusion® introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio® release. Navigate to the [help topic](https://help.syncfusion.com/common/essential-studio/licensing/overview#how-to-generate-syncfusion-license-key), which is shown in the licensing message box to generate and register the Syncfusion® license key to your project. Refer to this [blog](https://www.syncfusion.com/blogs/post/whats-new-in-2018-volume-2.aspx) post for understanding the licensing changes introduced in Essential Studio®.

**Set the new page as the app start page**

Open `App.xaml.cs` and update `CreateWindow` to return your new page. Example — if you added `LoginWithSocialIcon`:

```csharp
protected override Window CreateWindow(IActivationState? activationState)
{
	return new Window(new LoginWithSocialIcon());
}
```

**Troubleshooting**

- Templates don’t appear: restart Rider after installing the extension or verify the plugin is enabled.

- NuGet packages failing to restore: ensure your NuGet sources are available and that the project targets a supported MAUI framework.

- License prompts persist: confirm the license key is registered early in app startup and matches your Syncfusion account.


