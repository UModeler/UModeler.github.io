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

.. _polygongrouptool:

Polygon Group Tool
=======================
Groups the selected polygons into a single group. ``Active Group`` in the UModeler Status on the scene view displays the current polygon group. The newly created polygons will belong into the activated group.
You can choose a group via either ``Active Group`` in the UModeler status or ``Polygon Group Tool`` in the inspector.

Properties
------------
Group Name
 The current polygon group name
 
Polygon Count
 The polygon count in the current polygon group.
  
Add Group
 Adds a new polygon group from the current selected polygons.
 
Remove Group
 Removes the current polygon group.
 
Rename Group
 Renames the current polygon group.
 
Remove Empty
 Removes polygon groups which have no polygons.
 
Select Polygons
 Selects polygons in the current polygon group.
 
Add Polygons
 Adds the selected polygons to the current polygon group.
 
Remove Polygons
 Gets rid of the selected polygons from the current polygon group.
 
.. figure:: /images/UModeler_PolygonGroupTool.gif
   :scale: 95 %
	
   ``Polygon Group Tool`` Demo. 

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
 If this is on, Secondary UVs for lightmap will be generated every time UModeler mesh changes. 

.. _recalculate-tangents:
 
Recalculate Tangents
 If this is on, tangent vectors will be calculated every time UModeler mesh changes. If the materials in UModeler have normal textures, this should be on.
 
.. figure:: /images/UModeler_GenerateLightmapUVs.gif
   :scale: 95 %
	
   ``Generate Light UVs`` Demo.
   
.. figure:: /images/UModeler_RecalculatingTangents.gif
   :scale: 95 %
	
   ``Tangent Recalculataion`` Demo.