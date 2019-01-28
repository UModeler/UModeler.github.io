###############
UV Tool
###############

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
 
.. _OpenUVEditor:
Open UVEditor
 Opens UV Editor window.
 
Reset UVs
 Resets UV parameters of the selected polygons.
 
.. figure:: /images/UModeler_UVTool_v2.gif
   :scale: 90 %
	
   UV Tool Demo.
   
.. figure:: /images/UModeler_UVTool_ShiftingUVByPressingKeys.gif
   :scale: 90 %

   Moving the UVs of the selected elements up and down by pressing ``UP`` or ``DOWN`` arrows.