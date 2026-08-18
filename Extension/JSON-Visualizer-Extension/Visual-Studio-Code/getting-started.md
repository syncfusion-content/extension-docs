---
layout: post
title: Getting Started | JSONVisualizer | Syncfusion
description: The Syncfusion JSON Visualizer extension provides structured and interactive graphical representation of JSON data within VS Code.
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Getting Started with the Syncfusion® JSON Visualizer

The **Syncfusion® JSON Visualizer** for Visual Studio Code turns raw JSON data into an interactive, diagrammatic view directly inside the editor.

## Key Features

- **Interactive JSON Visualization:** Renders any JSON document as a structured, graphical diagram inside Visual Studio Code, making complex hierarchies easy to follow.

- **Node Selector:** Click a node to see its details and full JSON path.

- **Expand and Collapse:** Focus on relevant sections with expandable nodes.

- **Bi-directional Scrolling:** Smooth horizontal and vertical scrolling for large JSON files.

- **Lightweight and Fast:** Quick rendering with minimal impact on performance.

For complete download and installation instructions, see [Download and Installation](./download-and-installation.md).


## Step 1: Open a JSON File

After installation, open any JSON document you want to visualize:

1. Open the folder that contains your JSON file using **File ▸ Open Folder…**.
2. Select a `.json` file from the Explorer to open it in the editor.

## Step 2: Enable the JSON Visualizer

With the JSON file open in the editor:

1. Locate the **Enable JSON Visualizer** icon in the editor's menu bar (top-right of the editor area).

   ![Enable JSON Visualizer](images/EnableJSON.png)

2. Click the icon to launch the visualizer.

   ![JSON Visualizer](images/JSONVisualizer.png)

The extension reads the active JSON document and renders it as an interactive diagram in place of (or alongside) the raw text.

## Step 3: Explore the Features

Once the visualizer renders your JSON, use the following interactions to explore the structure:

| Action | Result |
|---|---|
| **Click a node** | Opens a pop-up showing the node's details and its full JSON path. |
| **Expand a node** | Reveals the child objects and arrays nested under that node. |
| **Collapse a node** | Hides nested children to keep the diagram focused. |
| **Scroll horizontally** | Follows wide structures across the diagram. |
| **Scroll vertically** | Navigates long or deeply nested documents. |

![JSON Visualizer](images/JsonFunctions.gif)

Use a combination of expand, collapse, and node selection to walk through even large JSON documents without losing orientation.

