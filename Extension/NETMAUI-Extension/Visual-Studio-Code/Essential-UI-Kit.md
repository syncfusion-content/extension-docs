---
layout: post
title: Essential® UI Kit for .NET MAUI | MAUI | Syncfusion®
description: The Syncfusion® Essential® UI Kit for the .NET MAUI extension provides predefined design screens for .NET MAUI apps.
platform: extension
control: Syncfusion<sup>®</sup> Extensions
documentation: ug
---

# Essential<sup>®</sup> UI Kit for .NET MAUI

The Essential<sup>®</sup> UI Kit for .NET MAUI provides pre-built XAML templates, making it easy to create user interfaces for cross-platform applications. It follows a well-structured separation of View, ViewModel, and Model classes, simplifying the integration of business logic and the modification of existing views.

N> Before using the **Essential<sup>®</sup> UI Kit for .NET MAUI - Syncfusion<sup>®</sup>**, ensure that the extension is installed in Visual Studio Code. To check, go to **View > Extensions** in the Extension Manager. If the extension is not installed, follow the steps in the [download and installation](https://help.syncfusion.com/maui/visual-studio-code-integration/download-and-installation#essential-ui-kit) help guide to install it.

## Include XAML templates in MAUI apps

1. Open a new or existing MAUI application.

2. In **Solution Explorer**, right-click on your MAUI project file and select **Essential<sup>®</sup> UI Kit for .NET MAUI - Syncfusion<sup>®</sup>** from the context menu. Ensure that the project is fully loaded, as this option will only be available if the project is fully loaded.

3. Choose the pages you want to add, enter a name for the page, and then click **Add**.

4. The selected pages will be added, including **View**, **ViewModel**, and **Model** classes, resource files, and the **Syncfusion® NuGet package** reference.

    ![MAUI UI Kit Visual Studio Code](Essential_UI_Kit_images/visual-studio-code-maui-ui-kit.gif)

5. Then, a Syncfusion<sup>®</sup> licensing registration required message box will be shown if you installed the trial setup or NuGet packages, since Syncfusion<sup>®</sup> introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio<sup>®</sup> release. Navigate to the [help topic](https://help.syncfusion.com/common/essential-studio/licensing/overview#how-to-generate-syncfusion-license-key) shown in the licensing message box to generate and register the Syncfusion<sup>®</sup> license key to your project. Refer to this [blog](https://www.syncfusion.com/blogs/post/whats-new-in-2018-volume-2.aspx) post for understanding the licensing changes introduced in Essential Studio<sup>®</sup>.

## Run the UI template item

To set your desired UI template as the startup page of your application, open the **App.xaml.cs** file in your .NET MAUI project and update the `CreateWindow` method to return the new page.

Example: If you added a Login page, make the following changes.

{% tabs %}
{% highlight C# hl_lines="3 9" %}

// For .NET 9 and .NET 10, use this code snippet:

protected override Window CreateWindow(IActivationState? activationState)
{
    return new Window(new Login());
}

{% endhighlight %}
{% endtabs %}

