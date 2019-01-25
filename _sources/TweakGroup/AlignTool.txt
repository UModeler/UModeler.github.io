############
Align Tool
############

Aligns the vertices of the selected elements within bounds.

Steps
---------------------------------
1. Select ``Align Tool`` with the selected elements, or Enter ``Align Tool`` and select vertices.
2. Choose Axis and Location in Properties.
3. Click on ``Align`` button.

Properties
---------------
Select Only Visible
 If on, Selects only visible vertices/edges/polygons from a camera. Occluded elements from other polygons will not be selected. This is available only when the game object has MeshCollider component.
 
 Axis  
  X, Y, or Z axis for alignment.
  
 Location
  * ``Min`` - Minimum location of the selected axis.
  * ``Middle`` - Middle location of the selected axis.
  * ``Max`` - Maximum location of the selected axis.
  
.. figure:: /images/UModeler_AlignTool.gif
   :scale: 95 %

   Align Tool Demo.