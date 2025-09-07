---
layout: post
title: FAQ Content | Plugin | Syncfusion
description: The Document Viewer Plugin enables you to easily view and manage your documents within VSCode using our intuitive features.
platform: Plugin
control: Syncfusion Plugins
documentation: ug
---

# Frequently Asked Question

### How do I install and set up the Document Viewer in JetBrains IDEs? 

To install the Document Viewer plugin:
- Open your JetBrains IDE (e.g., IntelliJ IDEA, PyCharm, etc.).
- Go to File > Settings (or IntelliJ IDEA > Preferences on macOS).
- Navigate to Plugins in the settings menu.
- Click on Marketplace and search for "Document Viewer."
- Select the official Document Viewer plugin and click Install.
- Restart your JetBrains IDE if prompted.
- The plugin will automatically handle supported file types (.docx, .xlsx, .pdf, .csv, .tsv, .md).


### How do I troubleshoot common issues with the Document Viewer plugin in JetBrains IDEs?  

Common solutions include:
- Restart your JetBrains IDE: Resolves most loading issues.
- Update the plugin: Ensure you have the latest version installed from the Marketplace.
- Check file permissions: Verify you have read/write access to the document.
- Clear cache: Invalidate caches and restart (File > Invalidate Caches / Restart).
- Compatibility: Ensure your JetBrains IDE version is compatible with the plugin.


### Which JetBrains IDEs are supported by the Document Viewer plugin?

The Document Viewer plugin is compatible with popular JetBrains IDEs, including IntelliJ IDEA, PyCharm, WebStorm, Rider, PhpStorm, RubyMine, GoLand, and CLion ensuring seamless document viewing across various development environments.

### Does Document Viewer plugin support Android studio?

Yes, The Document Viewer plugin is compatible with Android studio but Android Studio ships with a JetBrains Runtime that lacks the Java Chromium Embedded Framework (JCEF), which is required for optimal rendering of document previews so switch to a JCEF-enabled JetBrains Runtime.
 To try this, follow these steps:
- Open Android Studio and go to Help > Find Action (or press Ctrl + Shift + A on Windows/Linux, Cmd + Shift + A on macOS).
- Search for Choose Boot Java Runtime for the IDE.
- Select a JBR version with JCEF support (e.g., version 21.0.8+1-895.146-jcef, as used in later Android Studio versions like Koala).
- Restart Android Studio.


### What file formats are supported by the Document Viewer plugin?

Supported formats include:
- Microsoft Word: .docx, .dotx, .dot, .doc, and .rtf files
- Microsoft Excel: .xlsx, .xls, .xltx, and .xlt files
- PDF: .pdf files
- Markdown: .md files
- Spreadsheet formats: .csv (Comma Separated Values) and . tsv (Tab Separated Values)

### How can I provide feedback or ask questions about the plugin?

We would love to hear from you! Please contact us through our [Syncfusion® Feedback Portal](https://www.syncfusion.com/feedback/plugin).
