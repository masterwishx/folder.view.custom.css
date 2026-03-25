# Folder.View3 Custom CSS Files

------------

_The original FolderView and forked FolderView2 projects was abandoned._

_A new fork has taken its place and is under development here: **[Folder.View3](https://github.com/chodeus/folder.view3)**_

_Requires FolderView3 version 2026.03.23.3 or later._

------------

## Info

_This is my personal fork of the awesome CSS by **[Mattaton](https://github.com/Tyree/folder.view.custom.css)**, tweaked and updated for my own use._

_All themes currently include styling for VM panel on Dashboard and VM Page._

Custom CSS styles for use with the **[Folder.View](https://github.com/scolcipitato/folder.view/tree/main)** plugin for **unRAID** by **scolcipitato.**

Folder.View3 plugin **[Support Page](https://forums.unraid.net/topic/197223-plugin-folderview3/)** on the unRAID forum.

## Credits & Thanks

- **[scolcipitato](https://github.com/scolcipitato/folder.view)** — creator of the original Folder.View plugin  
- **[chodeus](https://github.com/chodeus/folder.view3)** — developer and maintainer of Folder.View3  
- **[Mattaton](https://github.com/Tyree/folder.view.custom.css)** — author of the original custom CSS  
- **[hernandito](https://github.com/hernandito/unRAID-Docker-Folder-Animated-Icons---Alternate-Colors)** — visual style and creator of the Animated “Docker‑Folder” Icons for unRAID  

If you have issues or customization suggestions, contact me on the unRAID forum. **[@masterwishx](https://forums.unraid.net/profile/107418-masterwishx/)**

## Installation Instructions

- CSS rules in this repo are organized by theme folder. Download the entire repo or the specific folder for the theme you wish to use. Copy the folder or folders in the Folder.View plugin folder here: **/boot/config/plugins/folder.view3/styles**
- More than one theme can be copied to the plugin's styles folder, but only one should be enabled. To disable unused themes, append _.disabled_ to the folder name.
- To disable individual files, append _.disabled_ to the file name.
- See individual theme README for explanation of the files included in the theme.

## Autostart Icon Customization

Among other basic theme styling, all themes customize the autostart icons on the Dashboard and Docker page. Special icons for autostart containers and the folders that hold autostart containers make it easy to see, at a glance, if all of your autostart containers are running as they should.
Icons are fully customizable (design, color, and size) via custom properties (variables) in the 06-icons.dashboard.css and 06-icons.docker-vm.css files.

_See the individual theme README files for more information on that theme._

### Dashboard

![Dashboard](Dashboard.png?raw=true "Title")

### Docker Page

![Docker Page](Docker.png?raw=true "Title")

### VM Page

![VM Page](VM.png?raw=true "Title")
