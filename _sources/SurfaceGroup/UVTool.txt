.. |Icon_Surface_UV| image:: /images/Icon_Surface_UV.png
   :scale: 100 %

##############################
UV Tool |Icon_Surface_UV|
##############################

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
 
.. |UModeler_UV_0| image:: /images/UModeler_UV_0.jpg
   :scale: 100 %
   
.. |UModeler_UV_1| image:: /images/UModeler_UV_1.jpg
   :scale: 100 %
   
|UModeler_UV_0| |UModeler_UV_1|
 Applied (0.5,0.5) as a scane and 30 degrees as a rotation to 1m x 1m Sqaure.