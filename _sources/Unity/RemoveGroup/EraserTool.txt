###############
Eraser Tool
###############

There are two modes of deleting elements. One is ``Immediate Mode`` and the other is ``Edit Mode``.

 * ``Immediate Mode`` - Select elements at first and then click on ``Eraser`` button to remove them.
 * ``Edit Mode`` - Select ``Eraser Tool`` first with no selected elements and then click on an edge which you want to remove.
 
When you try to erase an edge shared by two coplanar polygons, only the edge will be removed and the two shared polygons will be merged. Otherwise, the two polygons will be removed, too.

In a case of a vertex, all the polygons sharing the vertex will be removed. If it is a polygon, only the polygon will be taken away.

.. figure:: /images/UModeler_EraserToolImmediateMode.gif
   :scale: 95 %
	
   Eraser Tool, Immediate Mode, Demo
   
.. figure:: /images/UModeler_EraserToolEditMode.gif
   :scale: 95 %
	
   Eraser Tool, Edit Mode, Demo