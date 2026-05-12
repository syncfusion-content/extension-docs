---
layout: post
title: Download and Installation | Essential® UI Kit | Syncfusion
description: How to download the Essential® UI Kit for .NET MAUI Plugin from the JetBrains marketplace site and from the plugins View tab.
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Download and Installation - Maui UI Kit Extension

Syncfusion® publishes the Essential® UI Kit for .NET MAUI Plugin in [JetBrains marketplace](https://plugins.jetbrains.com/plugin/28456-document-viewer). You can either install it from JetBrains Rider or download and install it from the JetBrains marketplace.

## Prerequisites

Before getting started, make sure your environment meets the following requirements:

* A JetBrains IDE - Rider

 > The minimum version of the JetBrains IDE is 2024.2 to use the Maui UI Kit plugin.


## Install through the JetBrains

The following steps explain how to install the Essential® UI Kit for .NET MAUI plugin from JetBrains Rider.

1. Open JetBrains Rider.

2. Navigate to **File > Settings > Plugins** (or Preferences > Plugins on macOS).

3. Select the **Marketplace** tab and type **Essential® UI Kit for .NET MAUI** in the search field, Click the Install button on the plugin.

    ![Installing Essential UI Kit for .NET MAUI Plugin](images/Installation.png)

4. After the installation completes, restart your JetBrains Rider if prompted.

## Install plugin from disk

The following steps explain how to install the Maui UI Kit plugins from JetBrains Rider from the disk.

1. Download the plugin archive (ZIP or JAR) of [Essential® UI Kit for .NET MAUI](https://plugins.jetbrains.com/plugin/28456-document-viewer).

2. Press `Ctrl` + `Alt` + `S` to open settings and then select Plugins.

3. On the Plugins page, click The Settings button and then click Install Plugin from Disk.

4. Select the plugin archive file and click OK.

5. Click OK to apply the changes and restart the IDE if prompted.


## Install Essential® UI Kit for .NET MAUI from JetBrains Command Line

To install the Essential® UI Kit for .NET MAUI plugin in JetBrains Rider(Note: This requires the IDE to be closed):

1. Ensure your JetBrains Rider is closed.

2. Open a terminal and navigate to the JetBrains IDE’s bin directory.

3. Run the following command,

Windows

```
idea64.exe installPlugins com.syncfusion.mauikit

```

macOS

```
open -na "IntelliJ IDEA Ultimate.app" --args installPlugins com.syncfusion.mauikit

```

Linux

```
idea.sh installPlugins com.syncfusion.mauikit

```