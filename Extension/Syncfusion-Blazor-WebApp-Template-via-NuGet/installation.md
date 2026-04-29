---
layout: post
title: Syncfusion Web App Template Installation | Syncfusion
description: Learn here more about how to How to install and create a Syncfusion Blazor application using Syncfusion Web App Template.
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Syncfusion Web App Template Installation

## Overview

How to install and create a Syncfusion Blazor application using Syncfusion Web App Template

> **Note:** Refer to the .NET SDK support for Syncfusion Blazor Components [here](https://blazor.syncfusion.com/documentation/system-requirements#net-sdk).

The fastest way to get started is with the official Syncfusion Web App Template. It creates a fully configured Blazor app with all dependencies, theming, and syncfusion blazor components.

### Install the template

```powershell
dotnet new install Syncfusion.Blazor.WebApp.Templates
dotnet new syncfusionblazorwebapp -n MyApp
```

Then run your new project:

```powershell
cd MyApp
dotnet run
```

### Template Options

Option | Default | Description
--- | ---: | ---
`-n`, `--name` | Required | Project name
`-f`, `--framework` | `net10.0` | Target framework (`net8.0`, `net9.0`, or `net10.0`)
`-int`, `--interactivity` | `Server` | Render mode (`Server`, `WebAssembly`, or `Auto`)
`-ai`, `--all-interactive` | `PerPage/component` |  Interactive rendering enabled (`PerPage/component`, or `Global`)
`-https`, `--configure-for-https` | `true` |  Enables an HTTPS endpoint

### Create a new project using Dotnet CLI

```powershell
# WebAssembly mode
dotnet new syncfusionblazorwebapp -n MyApp -int WebAssembly

# Auto mode with interactive rendering enabled
dotnet new syncfusionblazorwebapp -n MyApp -int Auto -ai PerPage/component

# Enables an HTTPS endpoint
dotnet new syncfusionblazorwebapp -n MyApp -https true

# Target .NET 10
dotnet new syncfusionblazorwebapp -n MyApp -f net10.0
```

