# recLayerAdd-QGIS-plugin

## Purpose

This extension is adding files recursively from a selected directory folowing folders structure by creation subgroups in QGIS.
You can use regex to select only the files names or extensions you want to add during the scan.

## Installation

Go in QGIS (>3.22) into ``Settings`` > ``User Profiles`` > ``Open Active Profile Folder``
Then run here the command:

    git clone https://github.com/vincentBenet/recLayerAdd-QGIS-plugin recLayerAdd
    
Then in your extension manager, enable experimental extensions.
Go to installed extensions tab and check the ``recLayerAdd`` plugin.

## TODO

- Adding style files by regex
- Store and load regex files validation
- Store and load style regex application
