###############
Material Tool
###############

Adds and assigns materials to the polygons.

Steps
--------------------
1. Select ``Material Tool``.
2. Select polygons where you want to assign a material if no polygon is selected.
3. If ``Materials`` doesn’t have a material you want, add a new material by clicking ``Add Material`` button to open the material box and select one. 
4. Click ``LMB`` holding ``SHIFT`` over a polygon to which you want to assign the current material.

Interface
------------------
LMB
 Selects a polygon.
 
SHIFT + LMB
 Assigns Mat ID to a polygon where the mouse cursor points.
 
LMB Drag
 Selects polygons in a rectangle drawn by dragging.

Properties
---------------
Select Only Visible
 If on, Selects only visible vertices/edges/polygons from a camera. Occluded elements from other polygons will not be selected. This is available only when the game object has MeshCollider component.
 
Apply
 Assigns the Mat ID to the selected polygons.
 
Select
 Selects polygons having the Mat ID.
 
Add Material
 Adds a new material to the Material array below.
 
Remove Material
 Removes a material.
 
Materials
 Material array
 
.. figure:: /images/UModeler_MaterialTool.gif
   :scale: 90 %
	
   Material Tool Demo