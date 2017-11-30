############
Misc Tools
############

Game Object Tool
====================

Creates a game object with a UModeler component.

-----------------------------------------------------------------------------------

Collider Object Tool
======================

Creates a game object with a UModeler component and Mesh Collider component.

-----------------------------------------------------------------------------------

Bake Transform Tool
======================

Bakes rotate, scale or both of them.

Properties
-----------
Bake All
 Bake both Rotation and Scale.

Bake Rotation
 Applys the object rotation to every polygon and sets it to (0,0,0)

Bake Scale
 Applys the object scale to every polygon and sets it to (1,1,1)

-----------------------------------------------------------------------------------

Export Tool
==============

Exports the UModeler mesh to .obj or .prefab.

Properties
------------
Export to .obj
 Exports the UModeler mesh to .obj

Export to .prefab
 Exports the UModeler mesh to .prefab
 
Export to .asset
 Exports the UModeler mesh to .asset

-----------------------------------------------------------------------------------

Pivot To Center Tool
=======================

Changes the pivot location to the bottom center.

-----------------------------------------------------------------------------------

Collider Tool
=================

Adds a Mesh Collider component.

-----------------------------------------------------------------------------------

Local Settings Tool
=====================

Sets up local variables.

Properties
-------------
Backface
 backfaces on/off

Generate Lightmap UVs
 If it's on, Secondary UVs for lightmap will be generated every time UModeler mesh changes. 
 
.. figure:: /images/UModeler_GenerateLightmapUVs.gif
   :scale: 95 %
	
   ``Generate Light UVs`` Demo.