---
layout: post
title: Syncfusion WebAssembly App Template Installation | Syncfusion
description: Learn here more about how to How to install and create a Syncfusion Blazor application using Syncfusion WebAssembly App Template.
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Syncfusion WebAssembly App Template Installation

## Overview

How to install and create a Syncfusion Blazor application using Syncfusion WebAssembly App Template

> **Note:** Refer to the .NET SDK support for Syncfusion Blazor Components [here](https://blazor.syncfusion.com/documentation/system-requirements#net-sdk).

The fastest way to get started is with the official Syncfusion WebAssembly App Template. It creates a fully configured Blazor app with all dependencies, theming, and syncfusion blazor components.

### Install the template

```powershell
dotnet new install Syncfusion.Blazor.WebAssemblyApp.Templates
```
### Create a new project using Dotnet CLI

#### Create a new Blazor WebAssembly (Standalone) App

```powershell
dotnet new syncfusionblazorwasmapp -n MyApp --pwa true --framework net10.0 --configure-for-https true
```

### Template Options

Option | Default | Description
--- | ---: | ---
`-n`, `--name` | Required | Project name
`-f`, `--framework` | `net10.0` | Target framework (`net8.0`, `net9.0`, or `net10.0`)
`-p`, `--pwa` | `true` | Supports Progressive Web Application 
`-https`, `--configure-for-https` | `true` |  Enables an HTTPS endpoint

Then run your new project:

```powershell
cd MyApp
dotnet run
```