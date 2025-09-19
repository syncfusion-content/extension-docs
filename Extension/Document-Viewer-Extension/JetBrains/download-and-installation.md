---
layout: post
title: Download and Installation | DocumentViewer | Syncfusion
description: How to download the Document Viewer Plugin from the JetBrains marketplace site and from the plugins View tab.
platform: Plugin
control: Syncfusion Plugins
documentation: ug
---

# Download and Installation

Syncfusion® publishes the Document Viewer Plugin in [JetBrains marketplace](https://plugins.jetbrains.com/plugin/28456-document-viewer). You can either install it from JetBrains IDE or download and install it from the JetBrains marketplace.

## Prerequisites

Before getting started, make sure your environment meets the following requirements:

* A JetBrains IDE (e.g., IntelliJ IDEA, PyCharm, WebStorm, Android Studio, etc.)

 > The minimum version of the JetBrains IDE is 2024.2 to use the Document Viewer plugin.


## Install through the JetBrains

The following steps explain how to install the Document Viewer plugins from JetBrains IDE.

1. Open JetBrains IDE.

2. Navigate to **File > Settings > Plugins** (or Preferences > Plugins on macOS).

3. Select the **Marketplace** tab and type **Document Viewer** in the search field.

4. Click the Install button on the **"Document Viewer"** plugin.

5. After the installation completes, restart your JetBrains IDE if prompted.

## Install plugin from disk

The following steps explain how to install the Document Viewer plugins from JetBrains IDE from the disk.

1. Download the plugin archive (ZIP or JAR) of [Document Viewer](https://plugins.jetbrains.com/plugin/28456-document-viewer).

2. Press `Ctrl` + `Alt` + `S` to open settings and then select Plugins.

3. On the Plugins page, click The Settings button and then click Install Plugin from Disk.

4. Select the plugin archive file and click OK.

5. Click OK to apply the changes and restart the IDE if prompted.


## Install Document Viewer from JetBrains Command Line

To install the Document Viewer plugin in JetBrains(Note: This requires the IDE to be closed):

1. Ensure your JetBrains IDE is closed.

2. Open a terminal and navigate to the JetBrains IDE’s bin directory.

3. Run the following command,

Windows

```
idea64.exe installPlugins com.syncfusion.documentviewer
```

macOS

```
open -na "IntelliJ IDEA Ultimate.app" --args installPlugins com.syncfusion.documentviewer
```

Linux

```
idea.sh installPlugins com.syncfusion.documentviewer
```