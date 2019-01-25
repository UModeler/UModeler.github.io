######################
Smoothing Group Tool
######################
Manages smoothing groups for smooth shading. 
 
Steps
-------
1. Select Smoothing Group tool.
2. Select polygons with which you want to make a new smoothing group.
3. Type a smoothing group name in Group Name in Properties.
4. Click on ``Add`` Group button in Properties to add a new smoothing group.
5. Make sure that the new smoothing group with the name in Group Name property will be created.

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

Group Name
 The current smoothing group name
 
Polygon Count
 The polygon count in the current smoothing group.
 
Angle
 The threshold angle for ``Auto Smooth``.
 
Add Group
 Adds a new smoothing group from the current selected polygons.
 
Remove Group
 Removes the current smoothing group.
 
Rename Group
 Renames the current smoothing group.
 
Remove Empty
 Removes smoothing groups which have no polygons.
 
Select Polygons
 Selects polygons in the current smoothing group.
 
Add Polygons
 Adds the selected polygons to the current smoothing group.
 
Remove Polygons
 Gets rid of the selected polygons from the current smoothing group.
 
Auto Smooth
 Runs Auto Smooth from the selected polygons based on the value in ``Angle`` property.
 
 Auto Smooth sets the smoothing groups based on the angle between faces. Any two adjacent faces are put in the same smoothing group if the angle between their normals is less than the value in ``Angle`` property.
 
.. figure:: /images/UModeler_SmoothingGroupTool_v2.gif
   :scale: 95 %
	
   Smoothing Group Tool Demo 