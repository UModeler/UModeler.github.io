.. |Icon_Surface_Material| image:: /images/Icon_Surface_Material.png
   :scale: 100 %

#############################################
Material Tool |Icon_Surface_Material|
#############################################

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
 
Add Slot
 Adds a new material to the Material array below.
 
Remove Slot
 Removes a material.
 
Materials
 Material array
 
.. |UModeler_Material_0| image:: /images/UModeler_Material_0.jpg
   :scale: 100 %
   
.. |UModeler_Material_1| image:: /images/UModeler_Material_1.jpg
   :scale: 100 %
   
|UModeler_Material_0| |UModeler_Material_1|
 A different material is assigned to two polygons shown as above.