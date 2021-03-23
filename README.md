# Terrain-To-Object-Exporter
Exports a Unity terrain object as an .obj file that can be loaded into various 3D apps. Requires Unity 2.5 or later.

Usage
You must place the script in a folder named Editor in your project's Assets folder for it to work properly. Also it must be called "ExportTerrain" or it won't run.

1. To export, first select a terrain object in your scene. If none is selected, it will use the active terrain (if any). 

2. Select Export To Obj... from the Terrain menu, and in the resulting window, select whether you want the object to use triangles or quads when exported, and also select the resolution to use for the exported mesh (full, half, quarter, eighth or sixteenth). 

3. Then click Export, choose a file name and location, and the file will be exported. 

Note: High-res terrains exported at full resolution will result in very large .obj files and may take a while to process.


Authors: Eric Haines (Eric5h5): original & Yun Kyu Choi: C# conversion & Bit Barrel media: progress bar fix.
Reference: http://wiki.unity3d.com/index.php?title=TerrainObjExporter
