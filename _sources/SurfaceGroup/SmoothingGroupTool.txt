.. |Icon_Surface_SmoothingGroup| image:: /images/Icon_Surface_SmoothingGroup.png
   :scale: 100 %

##################################################################
Smoothing Group Tool |Icon_Surface_SmoothingGroup|
##################################################################
Manages smoothing groups for smooth shading. 

.. figure:: /images/UModeler_SmoothingGroupTool_Properties.jpg
   :scale: 100 %

   Smoothing Group Tool Properties
   
Steps
-------
1. Select Smoothing Group tool.
2. Select polygons with which you want to make a new smoothing group.
3. Click on ``Add Slot`` Group button in Properties to add a new smoothing group.
4. Type a smoothing group name in Group Name in Properties.

Steps - Auto Smooth
-------------------------
1. Select Smoothing Group tool.
2. Select polygons you want to include for Auto Smooth.
3. Fill ``Angle`` property out with the specific angle.
4. Click on ``Auto Smooth`` button

Properties
---------------
Select Only Visible
 Selects only visible vertices/edges/polygons from a camera. Occluded elements from other polygons will not be selected. This is available only when the game object has MeshCollider component.
 
Angle
 The threshold angle for ``Auto Smooth``.
 
Auto Smooth
 Runs Auto Smooth from the selected polygons based on the value in ``Angle`` property.
 
 Auto Smooth sets the smoothing groups based on the angle between faces. Any two adjacent faces are put in the same smoothing group if the angle between their normals is less than the value in ``Angle`` property. 

Add Slot
 Adds a new smoothing group slot from the current selected polygons.
 
Slot Properties
-----------------

.. figure:: /images/UModeler_SmoothringGroupSlot.jpg
   :scale: 100 %
	
   Smoothing Group Slot
	
Number - 1
 The number of the slot. Selects this slot.
 
Group Name - 2
 The current smoothing group name
 
Polygon Count - 3
 The polygon count in the current smoothing group.
 
Remove Group - 4
 Removes the current smoothing group.

Select Polygons - 5
 Selects polygons in the current smoothing group.

Add Polygons - 6
 Adds the selected polygons to the current smoothing group.
 
Remove Polygons - 7
 Gets rid of the selected polygons from the current smoothing group.
 
--------------------------------------------------------------------------- 
 
.. figure:: /images/UModeler_SmoothingGroup_0.jpg
   :scale: 100 %
   
   A sphere mesh before applying a smoothing group
   
.. figure:: /images/UModeler_SmoothingGroup_1.jpg
   :scale: 100 %
   
   Adds a column of polygons to a smoothing group.

.. figure:: /images/UModeler_SmoothingGroup_2.jpg
   :scale: 100 %
   
   The polygons are shaded smoothly.

---------------------------------------------------------------------------
   
.. figure:: /images/UModeler_SmoothingGroup_3.jpg
   :scale: 100 %
   
   A cylinder before applying the smoothing group.

.. figure:: /images/UModeler_SmoothingGroup_4.jpg
   :scale: 100 %
   
   Applies the auto smooth after selecting all polygons of the cylinder.

.. figure:: /images/UModeler_SmoothingGroup_5.jpg
   :scale: 100 % 
   
   3 smoothing groups are created - top polygon, bottom polygon and side polygons.
