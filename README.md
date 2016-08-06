Godot Terrain Plugin
======================

This is a heightmap-based terrain node for Godot Engine 2.1, written in GDScript.

![Editor screenshot](http://zylannprods.fr/lab/godot/terrain_plugin/TerrainEditor_screen4.png)

Features
----------

- Custom Terrain node
- Resizeable square between 1 and 1024 units of space
- Paint and smooth the terrain in the editor
- Brush with customizable shape, size and opacity
- Takes advantage of frustum culling by chunking the terrain in multiple meshes
- Smooth or hard-edges rendering
- Save to image and normal map
- Terrain data saved inside the scene like Tilemap and Gridmap
- Edition behaviour works both in editor and game


TODO/ideas
-----------

- Undo/redo
- Level of detail (LOD)
- Baked mode for faster terrain loading (it is currently rebuilt from data both in editor and game)
- Meshing is very slow (will this plugin remain pure GDScript?)
- Save terrain data as a separate resource to unbloat the scene file
- Decorrelate resolution and size
- Make Terrain inherit Spatial so it can be moved around
- Paint meshes on top of the terrain (grass, trees, rocks...) <-- I want to make a vegetation generator plugin too :p
- Improve normals (data "pixels" produce lighting artefacts)
- Texture painting
- Physics (low-poly mesh collider? Or heightfield collider like PhysX does?)
- Infinite terrain mode

- Extras: importer for terrains made in DCCs (Blender/3DS etc)

