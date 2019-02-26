.. |Icon_Surface_Material| image:: /images/Icon_Surface_Material.png
   :scale: 100 %

#############################################
Material Tool |Icon_Surface_Material|
#############################################

Adds and assigns materials to the polygons.

 .. figure:: /images/UModeler_MaterialTool2.5.jpg

Steps
--------------------
1. Select ``Material Tool``.
2. Select polygons where you want to assign a material if no polygon is selected.
3. If ``Materials`` doesn’t have a material you want, add a new material slot by clicking ``Add Slot`` button at the end of the properties to open the material box and select one. 
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
 
Add Slot
 Adds a new material slot.
 
UIs of Material Slot 
---------------------

Texture Button
 Selects a slot.

A (Apply polygons)
 Assigns the Mat ID to the selected polygons.
 
S (Select polygons)
 Selects polygons having the Mat ID.
 
Minus - (Remove a Slot)
 Removes a slot at which the mouse cursor points.
 
Material Box
 Selects a material. 

 
.. |UModeler_Material_0| image:: /images/UModeler_Material_0.jpg
   :scale: 100 %
   
.. |UModeler_Material_1| image:: /images/UModeler_Material_1.jpg
   :scale: 100 %
   
|UModeler_Material_0| |UModeler_Material_1|
 Two polygons are selected (Left image) and a metal material is assigned there (Right image).