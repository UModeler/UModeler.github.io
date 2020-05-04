.. |Icon_Surface_UV| image:: /images/Icon_Surface_UV.png
   :scale: 100 %

##############################
UV Tool |Icon_Surface_UV|
##############################

Sets UV parameters such as ``Shift``, ``Scale`` and ``Rotation`` etc to each polygon.

.. note::

 UV Tool doesn't affect unwrapped polygons.
  
.. figure:: /images/UModeler_UVTool.jpg
   :scale: 100 % 
 
Steps
---------------
1. Select ``UV Tool``.
2. Select polygons like you did in Polygon tool if no polygon is selected.
3. Adjust ``Shift``, ``Scale`` and ``Rotation`` properties in Properties.
4. Or transform UVs of polygons using ``Move``, ``Rotate``, ``Scale`` Tools

.. |UModeler_UV_MoveTool| image:: /images/UModeler_UVTool_MoveGizmo.gif
   :scale: 90 %
   
.. |UModeler_UV_RotateTool| image:: /images/UModeler_UVTool_RotateGizmo.gif
   :scale: 90 %

.. |UModeler_UV_ScaleTool| image:: /images/UModeler_UVTool_ScaleGizmo.gif
   :scale: 90 %
 
|UModeler_UV_MoveTool| |UModeler_UV_RotateTool| |UModeler_UV_ScaleTool|
 Direct Move, Rotate and Scale of UVs using ``Move``, ``Rotate`` and ``Scale`` tools. They are switched among them by clicking on the tool bar buttons in the properties or pressing ``W``, ``E``, ``R`` on keyboard.

Properties
---------------
Move
 Enables ``Move tool``. The shortcut is ``W`` 

Rotate
 Enables ``Rotate tool``. The shortcut is ``E``

Scale
 Enables ``Scale tool``. The shortcut is ``R``

Hide Overlay
 Hides polygon selection overlays to see the selected polygons' textures more clearly.

Select Only Visible
 If on, Selects only visible vertices/edges/polygons from a camera. Occluded elements from other polygons will not be selected. This is available only when the game object has MeshCollider component.  
 
Shift
 Shift of UVs
 
Rotation
 Rotation of UVs

Scale
 Scale of UVs 
 
Tiling
 Runs the tiling according ``X`` and ``Y`` properties next to this.
 
X
 Changes texture tiling on selected surfaces in the X direction.
 
Y
 Changes texture tiling on selected surfaces in the Y direction.
 
Fit UVs
 Fits the UVs into (0,1) in each of the selected polygons.
 
Reset UVs
 Resets the UVs of the selected polygons to make them initial UVs.
 
.. _OpenUVEditor:
Open UVEditor
 Opens UV Editor window.
 
.. |UModeler_UV_0| image:: /images/UModeler_UV_0.jpg
   :scale: 100 %
   
.. |UModeler_UV_1| image:: /images/UModeler_UV_1.jpg
   :scale: 100 %
   
|UModeler_UV_0| |UModeler_UV_1|
 Applied (0.5,0.5) as a scane and 30 degrees as a rotation to 1m x 1m Sqaure.
