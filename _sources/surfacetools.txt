###############
Surface Tools
###############

Material Tool
===================

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

------------------------------------------------------------------------------------------------------

UV Tool
===================

Sets UV parameters such as ``Shift``, ``Scale`` and ``Rotation`` etc to each polygon.

.. note::

 UV Tool doesn't affect unwrapped polygons.
 
Steps
---------------
1. Select ``UV Tool``.
2. Select polygons like you did in Polygon tool if no polygon is selected.
3. Adjust ``Shift``, ``Scale`` and ``Rotation`` properties in Properties.

Interface
-----------

``CTRL`` + ``UP ARROW``
 Moves the UVs of the selected polygons up.
 
``CTRL`` + ``DOWN ARROW``
 Moves the UVs of the selected polygons down.

Properties
---------------
Select Only Visible
 If on, Selects only visible vertices/edges/polygons from a camera. Occluded elements from other polygons will not be selected. This is available only when the game object has MeshCollider component.
 
Mode
 * ``Absolute`` : The properties are set to the selected polygons directly
 * ``Relative`` : The properties are added to the selected polygons.
 
Shift
 Shift of UVs
 
Scale
 Scale of UVs
 
Rotation
 Rotation of UVs
 
Tiling
 * ``X`` : Changes texture tiling on selected surfaces in the X direction.
 * ``Y`` : Changes texture tiling on selected surfaces in the Y direction.
 
Fix UVs according to Tiling
 Based on Tiling properties the UVs of the selected polygons are fixed.
 The bigger Tiling properties are, the denser texture tiling is.
 
Reset UVs
 Resets UV parameters of the selected polygons.
 
.. figure:: /images/UModeler_UVTool_v2.gif
   :scale: 90 %
	
   UV Tool Demo.
   
.. figure:: /images/UModeler_UVTool_ShiftingUVByPressingKeys.gif
   :scale: 90 %

   Moving the UVs of the selected elements up and down by pressing ``UP`` or ``DOWN`` arrows.

------------------------------------------------------------------------------------------------------

Open UVEditor
===================

Opens UVEditor to unwrap polygons and edit those UVs.

.. figure:: /images/UModeler_UVEditorWnd.jpg
   :scale: 95 %
	
   UV Editor Window
   
------------------------------------------------------------------------------------------------------   

Vertex Color Tool
====================================================

Sets colors to the Vertices. Pressing or Dragging ``LMB`` holding ``SHIFT`` will paint a polygon below the mouse cursor in the selected color.

.. note::

 | A material with a shader supporting Vertex Color should be set to assign colors with Material Tool. Recommended materials for assigning colors(VC - Vertex Color) are as follows.
 |  • UModelerPro_OnlyVC
 |  • UModelerBasic_OnlyVC

Steps - 1
----------
1. Go to ``Vertex Color Tool``
2. Select Vertices like you did in ``Vertex Tool`` if no vertex is selected.
3. Click ``LMB`` on Color bar in Properties
4. Choose a color which you want. 

Steps - 2
----------
1. Go to ``Vertex Color Tool``
2. Drag a mouse holding ``SHIFT``

Interface
---------------
``LMB``
 Selects a vertex and pick a color of the color.
 
``Shift``
 Makes the sphere brush visible.
 
``SHIFT + LMB``
 Assigns the color in Color bar in Properties to vertices within the sphere brush. 
 
``SHIFT + Scroll Wheel``
 Increases the size of the brush.
 
``LMB Drag``
 Selects several vertices in a rectangle.

Properties
---------------
Select Only Visible
 If on, Selects only visible vertices/edges/polygons from a camera. Occluded elements from other polygons will not be selected. This is available only when the game object has MeshCollider component.

Color
 Color which will be assigned to the selected vertices.

Brush Radius
 The sphere brush radius
 
Select Vertices
 Selects vertices with the color in ``Color`` property.
 
.. figure:: /images/UModeler_VertexColorTool.gif
   :scale: 95 %
	
   Vertex Color Tool Demo   
   
------------------------------------------------------------------------------------------------------
 
Polygon Color Tool 
===================

(Formerly called as `Color Tool`)

Sets colors to the polygons. Pressing or Dragging ``LMB`` holding ``SHIFT`` will paint a polygon below the mouse cursor in the selected color.

.. note::

 | A material with a shader supporting Vertex Color should be set to assign colors with Material Tool. Recommended materials for assigning colors(VC - Vertex Color) are as follows.
 |  • UModelerPro_OnlyVC
 |  • UModelerBasic_OnlyVC

Steps
---------
1. Go to ``Polygon Color Tool``
2. Select polygons like you did in ``Polygon Tool`` if no polygon is selected.
3. Click ``LMB`` on Color bar in Properties
4. Choose a color which you want. 

Interface
---------------
LMB
 Selects a polygon and pick a color of the color.
 
SHIFT + LMB
 Assigns the color in Color bar in Properties to a polygon where the mouse cursor point.
 
LMB Drag
 Selects several polygons in a rectangle.

Properties
---------------
Select Only Visible
 Selects only visible vertices/edges/polygons from a camera. Occluded elements from other polygons will not be selected. This is available only when the game object has MeshCollider component.

Color
 Color which will be assigned to the selected polygons.
 
Select Polygons
 Selects polygons with the color in ``Color`` property.
 
.. figure:: /images/UModeler_ColorTool_v2.gif
   :scale: 95 %
	
   Polygon Color Tool Demo

------------------------------------------------------------------------------------------------------ 

Smoothing Group Tool
======================
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