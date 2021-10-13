.. |Icon_Surface_Material| image:: /images/Icon_Surface_Material.png
   :scale: 100 %

#############################################
Material Tool |Icon_Surface_Material|
#############################################

Adds and assigns materials to the polygons.

 .. figure:: /images/UModeler_Material_Slots.jpg

Steps
--------------------
1. Select ``Material Tool``.
2. Select polygons where you want to assign a material if no polygon is selected.
3. If ``Materials`` doesn’t have a material you want, add a new material slot by clicking ``Add Slot`` button at the end of the properties to open the material box and select one. 
4. Press ``Alt + n`` shorcut or Click on ``Alt + n`` or ``A`` button in the slot. It'll assign the material in the slot to the selected polygons.
5. Click ``LMB`` holding ``SHIFT`` over a polygon to which you want to assign the current material.

.. tip::

 ``Alt + 0`` ~ ``Alt + 9`` shortcuts work in other tools as well so you don't need to enter Material tool if you use ``Alt + n`` shortcuts to assign a material.

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

Copy Materials
 Stores materials in the current Object in order to paste them to another object.

Paste Materials
 Pastes the stored materials in the clipboard.
 
UIs of Material Slot 
---------------------

Texture Button
 Selects a slot.

``Alt + n`` or A (Assign)
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