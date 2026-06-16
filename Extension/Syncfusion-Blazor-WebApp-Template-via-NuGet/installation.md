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
```
### Create a new project using Dotnet CLI

#### Create a new Syncfusion Blazor Web App

```powershell
dotnet new syncfusionblazorwebapp -n MyApp --interactivity Auto --framework net10.0 --configure-for-https true --all-interactive PerPage/component
```

#### Create a new Syncfusion Blazor Server App

```powershell
dotnet new syncfusionblazorwebapp -n MyApp --interactivity Server --framework net9.0 --configure-for-https false --all-interactive Global
```

#### Create a new Syncfusion Blazor WebAssembly App

```powershell
dotnet new syncfusionblazorwebapp -n MyApp --interactivity WebAssembly --framework net8.0 --configure-for-https true --all-interactive PerPage/component
```

### Template Options

Option | Default | Description
--- | ---: | ---
`-n`, `--name` | Required | Project name
`-f`, `--framework` | `net10.0` | Target framework (`net8.0`, `net9.0`, or `net10.0`)
`-int`, `--interactivity` | `Server` | Render mode (`Server`, `WebAssembly`, or `Auto`)
`-ai`, `--all-interactive` | `PerPage/component` |  Interactive rendering enabled (`PerPage/component`, or `Global`)
`-https`, `--configure-for-https` | `true` |  Enables an HTTPS endpoint

Then run your new project:

```powershell
cd MyApp
dotnet run
```