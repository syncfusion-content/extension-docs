---
layout: post
title: Download and Installation | DocumentViewer | Syncfusion
description: How to download the Document Viewer Plugin from the JetBrains marketplace site and from the plugins View tab.
platform: Plugin
control: Syncfusion Plugins
documentation: ug
---

# Download and Installation

Syncfusion® publishes the Document Viewer Plugin in [JetBrains marketplace](https://marketplace.visualstudio.com/items?itemName=SyncfusionInc.Document-Viewer-VSCode-plugins). You can either install it from JetBrains IDE or download and install it from the JetBrains marketplace.

## Prerequisites

Before getting started, make sure your environment meets the following requirements:

* A JetBrains IDE (e.g., IntelliJ IDEA, PyCharm, WebStorm, Android Studio, etc.)

 > The minimum version of the JetBrains IDE is 2024.1 to use the Document Viewer plugin.


## Install through the JetBrains

The following steps explain how to install the Document Viewer plugins from JetBrains IDE.

1. Open JetBrains IDE.

2. Navigate to **File > Settings > Plugins** (or Preferences > Plugins on macOS).

3. Select the **Marketplace** tab and type **Document Viewer** in the search box.

     ![plugin](images/pluginsView.png)

4. Click the Install button on the **"Document Viewer"** plugin.

5. After the installation completes, restart your JetBrains IDE if prompted.


## Install from the JetBrains Marketplace

The following steps explain how to download Document Viewer plugin from the JetBrains Marketplace and install them.

1. Visit the [Document Viewer plugin MarketPlace page](https://mark..).

2. Click the **Get** button. If your JetBrains IDE is running, the button may change to **Install to IDE**, then [Document Viewer plugin](https://marketplace..) will open in your IDE.

3. In your IDE, Click the Install button for the **"Document Viewer"** plugin.

4. After the installation, restart JetBrains IDE when suggested.

## Install Document Viewer from JetBrains Command Line

To install the Document Viewer plugin in JetBrains(Note: This requires the IDE to be closed):

1. Ensure your JetBrains IDE is closed.

2. Open a terminal and navigate to the JetBrains IDE’s bin directory.

3. Run the following command, replacing path/to/ide with the path to your IDE installation and using the plugin ID for Document Viewer:

```
path/to/ide/bin/idea.sh plugin install com.syncfusion.document-viewer
```