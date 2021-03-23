# Terrain-To-Object-Exporter
Exports a Unity terrain object as an .obj file that can be loaded into various 3D apps. Requires Unity 2.5 or later.

Screenshots:

![alt text](https://github.com/burakdaskin/Terrain-To-Object-Exporter/blob/main/exporter1.png?raw=true)

![alt text](https://github.com/burakdaskin/Terrain-To-Object-Exporter/blob/main/exporter2.png?raw=true)

![alt text](https://github.com/burakdaskin/Terrain-To-Object-Exporter/blob/main/exporter3.png?raw=true)

How to use:

1. Create a C# Script with name "ExportTerrain" where in folder .../Assets/Editor/.

2. Open script, delete all and copy-paste the code, save.

3. Select a terrain object in your scene. (If none is selected, it will use the active terrain (if any)) 

4. Select Export To Obj... from the "Terrain" menu, and in the resulting window, select whether you want the object to use triangles or quads when exported, and also select the resolution to use for the exported mesh (full, half, quarter, eighth or sixteenth). 

5. Then click Export, choose a file name and location, and the file will be exported. 

Note: High-res terrains exported at full resolution will result in very large .obj files and may take a while to process.


Authors: Eric Haines (Eric5h5): original & Yun Kyu Choi: C# conversion & Bit Barrel media: progress bar fix.

Reference: http://wiki.unity3d.com/index.php?title=TerrainObjExporter
