---
layout: post
title: FAQ Content | Extension | Syncfusion
description: The Document Viewer Plugin enables you to easily view and manage your documents within VSCode using our intuitive features.
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Frequently Asked Question

### What does the Document Viewer plugin do for JetBrains IDE?

The Document Viewer lets you open and view Word, Excel, PDF, Markdown, CSV, and TSV files directly in the JetBrains editor.

### How do I install and set up the Document Viewer in JetBrains IDEs? 

To install the Document Viewer plugin:
- Open your JetBrains IDE (e.g., IntelliJ IDEA, PyCharm, etc.).
- Go to File > Settings (or IntelliJ IDEA > Preferences on macOS).
- Navigate to Plugins in the settings menu.
- Click on Marketplace and search for "Document Viewer."
- Select the official Document Viewer plugin and click Install.
- Restart your JetBrains IDE if prompted.
- The plugin will automatically handle supported file types (.docx, .xlsx, .pdf, .csv, .tsv, .md).

### What file formats are supported by the Document Viewer plugin?

Supported formats include:
- Microsoft Word: .docx, .dotx, .dot, .doc, and .rtf files
- Microsoft Excel: .xlsx, .xls, .xltx, and .xlt files
- PDF: .pdf files
- Markdown: .md files
- Spreadsheet formats: .csv (Comma Separated Values) and . tsv (Tab Separated Values)

### How do I view Microsoft Word documents in JetBrains?

You can view Microsoft Word documents (.docx) directly in JetBrains IDE using the Document Viewer plugin. Simply install the plugin from the JetBrains marketplace, then open any .docx file in your workspace. The plugin provides a built-in viewer that renders Word documents with formatting preserved, allowing you to read and perform basic editing operations without leaving your development environment.

### Can I view PDF files in JetBrains?

Yes, you can view PDF files directly in JetBrains IDE using the Document Viewer plugin:
- Install the Document Viewer plugin from the JetBrains Marketplace.
- Open a .pdf file in your workspace.
- The plugin will render the PDF within JetBrains, allowing you to view the document with preserved formatting. You can navigate pages, zoom in/out, and search text within the PDF. 

### How to view and edit Excel files (.xlsx) in JetBrains?

The Document Viewer plugin allows you to view and edit Excel files (.xlsx) directly in JetBrains. After installing the plugin, you can:
- Open .xlsx files with preserved formatting and cell structure
- Edit cell contents and values
- View multiple worksheets within the same file
- Perform basic spreadsheet operations, such as filtering and sorting
- Configure read-only mode if you only need viewing capabilities

### How do I view Markdown files in JetBrains?

You can view Markdown (.md) files directly in JetBrains using the Document Viewer plugin. Simply install the plugin from the JetBrains marketplace and open any .md file in your workspace. The plugin provides a built-in viewer that renders markdown files with formatting, allowing you to read and perform basic editing operations without leaving your development environment.

### How do I view CSV and TSV files with proper column alignment in JetBrains?

The plugin provides enhanced viewing for CSV and TSV files with proper column alignment and formatting. Features include:
- Column-aligned display: Automatically formats CSV/TSV data into readable columns
- Sorting capabilities: Sort data by any column in ascending or descending order
- Filtering options: Filter rows based on specific criteria
- Large file handling: Efficiently handles large CSV/TSV files without performance issues
- Customizable display: Configure column widths and viewing preferences

### Can I edit files in the Document Viewer?

Yes, the Document Viewer allows basic editing of Word, Excel, Markdown, CSV, and TSV files directly within JetBrains IDE. This plugin focuses on essential<sup style="font-size:70%">&reg;</sup> editing tasks to streamline your workflow.

### Can I edit Word files in JetBrains with this plugin?

Yes, the Document Viewer plugin supports minimal editing of Microsoft Word documents. While it's primarily designed for viewing, you can perform basic text modifications and content updates. However, for advanced formatting and complex editing tasks, you may still need to use Microsoft Word for full functionality.

### Is the Document Viewer suitable for large datasets?

Yes, the plugin's sorting and filtering tools are designed to help you organize and analyze large datasets efficiently.

### Can I customize the document viewer features?

Yes, you can customize the Document Viewer’s features. Options such as sorting, and filtering can be managed directly from the status bar or through JetBrains settings. Editing is supported for all file types included except PDF, and sorting and filtering features are specifically available for spreadsheet formats like Excel, CSV, and TSV files. 

### Does the Document Viewer support Markdown files in JetBrains?

Yes, the Document Viewer plugin does support Markdown (.md) files in JetBrains IDE. In addition to Markdown, it allows viewing and light editing of Microsoft Office documents (Word, Excel), PDFs, CSV, and TSV files directly within the editor.

### Does viewing PDF files in Document Viewer requires any external dependencies?

No. The plugin uses Syncfusion's standalone PDF viewer component, ensuring seamless setup and consistent PDF rendering directly within the JetBrains IDE.

### Does the Document Viewer upload or transfer my files to a remote server before rendering them in JetBrains IDE?

No. The plugin uses Syncfusion’s pure-JavaScript Document Editor, Spreadsheet, PDF Viewer, and Markdown editor components to parse and render your files entirely on the client. Your document data never leaves your machine, and no internet connection or server-side processing is required.

### How does the Document Viewer compare to other JetBrains plugins?

The Document Viewer stands out with:
- Multi-format support: Handles both Office documents, pdf, markdown and spreadsheet files in one plugin
- Editing capabilities: Unlike pure viewers, it allows basic editing
- Professional rendering: High-quality document display with formatting preservation
- Active development: Regular updates and planned feature additions
- Enterprise-grade: Built by Syncfusion, known for professional development tools

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

### Are there any limitations I should know about? 

Current limitations include:
- Markdown Editing: Adding images currently requires a valid image URL, as support for adding file paths is not provided.
- Advanced editing: Limited to basic modifications compared to native Office applications
- File size: Very large documents may have performance considerations
- Complex formatting: Some advanced Word/Excel features may not render perfectly
- Collaboration: Real-time collaboration features are not available

### How can I provide feedback or ask questions about the plugin?

We would love to hear from you! Please contact us through our [Syncfusion® Feedback Portal](https://www.syncfusion.com/feedback/plugin).
