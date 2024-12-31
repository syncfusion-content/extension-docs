---
layout: post
title: Syncfusion NuGet Package Licensing | Extension | Syncfusion
description: Syncfusion provides the license per developer licensing model. Each license is for a single named user not for any servers.
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet Package Licensing 

Syncfusion<sup style="font-size:70%">&reg;</sup> provides the license per developer licensing model. Each license is for a single named user. Also, Syncfusion<sup style="font-size:70%">&reg;</sup> doesn’t require separate license for any servers. So, if you have license for each developer it is not necessary to do license key registration to use the Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet packages.

N> Syncfusion<sup style="font-size:70%">&reg;</sup> removed the runtime and design time license key from v13.2.0.29 to v16.2.0.41. So, no need to register the license key either in application or system if you are using the Essential Studio<sup style="font-size:70%">&reg;</sup> from v13.2.0.29 to v16.2.0.41 versions.

N> Syncfusion<sup style="font-size:70%">&reg;</sup> removed the runtime and design time license key from v13.2.0.29 to v16.2.0.41. So, no need to register the license key either in application or system if you are using the Essential Studio<sup style="font-size:70%">&reg;</sup> from v13.2.0.29 to v16.2.0.41 versions.

## How to register Syncfusion<sup style="font-size:70%">&reg;</sup> license on or after to 16.2.0.41 version

We have introduced a new licensing system starting with version 16.2.0.41 release of Essential Studio<sup style="font-size:70%">&reg;</sup>. These changes apply to all evaluators and only to paid customers who use NuGet packages from [nuget.org](https://www.nuget.org/). Starting with v16.2.0.41, if you reference Syncfusion<sup style="font-size:70%">&reg;</sup> assemblies from evaluation installer or from the NuGet feed, you also have to include a license key in your projects. Please note that this license key is different from the installer unlock key that you might have used in the past, and needs to be separately generated from Syncfusion<sup style="font-size:70%">&reg;</sup> website. The following steps guide you as to how to register the Syncfusion<sup style="font-size:70%">&reg;</sup> license.

1. Generate the Syncfusion<sup style="font-size:70%">&reg;</sup> License key by follow the steps from the [page](https://help.syncfusion.com/common/essential-studio/licensing/license-key#how-to-generate-syncfusion-license-key)
2. Register the Syncfusion<sup style="font-size:70%">&reg;</sup> license key in corresponding application by follow the steps from the [page](https://help.syncfusion.com/common/essential-studio/licensing/license-key#how-to-register-the-syncfusion-license-key)

   > Before register the Syncfusion<sup style="font-size:70%">&reg;</sup> license key, ensure that all referenced Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet packages are all on the same version as license key version, because our license keys are version and platform-specific.

## How to register Syncfusion<sup style="font-size:70%">&reg;</sup> license prior to 13.2.0.29 version

While using Syncfusion<sup style="font-size:70%">&reg;</sup> NuGet package of version that is **prior to 13.2.0.29**, you need to register for the Syncfusion<sup style="font-size:70%">&reg;</sup> license for development purpose. The following steps guide you as to how to register for the Syncfusion<sup style="font-size:70%">&reg;</sup> license.

1. Download the [Syncfusion<sup style="font-size:70%">&reg;</sup> License](http://files2.syncfusion.com/Installs/Support/KB/RegisterProductkeyinBuildMachine.zip) Register tool and extract the file. 
2. Open the Command Prompt with administrator privileges.
3. Navigate to the root location of the extracted downloaded, Syncfusion<sup style="font-size:70%">&reg;</sup> license.
4. Run the following command to register the Unlock key.

   Synckeynoui.exe “Unlock key”

   N> You should provide the unlock key which is started with "@" and ended with "=" as a parameter for this Syncfusion<sup style="font-size:70%">&reg;</sup> License tool.

   ![Command for register the Syncfusion<sup style="font-size:70%">&reg;</sup> Unlock key](Register-the-Syncfusion-License-key_images/Register-the-Syncfusion-License-key-img1.png)
