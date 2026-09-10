# Splitgate-MapManager

A browser-based management tool designed to browse, search, edit metadata, and package custom maps and prefabs for Splitgate.

> [!CAUTION]
> The underlying code for this project was built by AI.

## Why is this tool needed?
Managing custom maps and prefabs outside of the game can be cumbersome, especially when dealing with custom titles, author names, or organizing multiple items into clean packs for scripts like the [Splitgate-MapLoader](https://github.com/CorellanStoma/Splitgate-MapLoader). 

This tool runs entirely in your web browser, allowing you to drop map folders or `.bin` files, inspect them, edit their metadata, update preview images with automatic 16:9 cropping, and export them as neatly packaged archives ready for use.

## Features
* **View**: Maps & Prefabs
* **Edit**: Metadata & Covers (Auto 16:9)
* **Export**: Map Pack, Prefab Pack, or Mixed Pack (.zip)
* **Client-Side Processing**: Runs completely locally in your browser using JSZip – no files are uploaded to any external server.
* **Intelligent Type Detection**: Automatically recognizes whether items are maps (`World.cf1047`) or prefabs (`Prefab.cf1047_prefab`)[cite: 2].
* **Batch Selection**: Pick specific items and bundle them together into clean playlist archives.

## How to Use

**1. Load your items**
* Open the Map Manager web interface.
* Drag and drop your map/prefab folders or multiple `.bin` / `.zip` files directly into the drop zone.

**2. Manage & Edit**
* Use the search bar to quickly filter items by name or author.
* Click **Details & Edit** on any card to open the metadata editor, update the name, author, description, or swap out the preview image.

**3. Export**
* Select the maps or prefabs you want to pack using the selection checkboxes.
* Click the bottom toolbar button (**Download Selected as Map Pack / Prefab Pack / Mixed Pack**) to instantly download your structured `.zip` archive.