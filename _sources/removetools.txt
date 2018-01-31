###############
Remove Tools
###############

Eraser Tool
========================

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

------------------------------------------------------------------------------------------------------

Detach Tool
===================
Detaches the selected polygons from the current game object to get them into the new game object.

Steps
---------
 1. Select polygons.
 2. Select ``Detach`` button.

.. figure:: /images/UModeler_DetachTool.gif
   :scale: 95 %
	
   Detaches the selected polygons and creates a new game object, which has the detached polygons.

------------------------------------------------------------------------------------------------------

Combine Vertices Tool
======================

Merges all the selected vertices in one unique one. The location of the surviving vertex can be chosen before executing this tool.

.. note::

 | If you select ``Combine Tool`` with no selected vertices, you will enter ``Combine Vertex`` mode. In this mode you can selected vertices and set up some options and combine them.
 | However, if you click on ``Combine`` button with some vertices selected, the combine action will happen immediately.
 
Interface
-----------

``SPACE``
 Combines the selected vertices.
   
Properties
---------------

Combine Type
 * ``First`` - Places the remaining vertex at the location of the first one selected.
 * ``Last`` - Places the remaining vertex at the location of the last one selected.
 * ``Center`` - Places the remaining vertex at the center of the selected vertices.
 
Collapse
 It may let alive more than one vertex. In fact, you will have as many remaining vertices as you had islands of selection (i.e. groups of linked selected vertices). The remaining vertices will be positioned at the center of their respective islands.
 
Combine Vertices
 Click on this button to combine the selected vertices.
 
.. figure:: /images/UModeler_CombineVertexTool.gif
   :scale: 95 %
   
   Merges the selected vertices. 

------------------------------------------------------------------------------------------------------

Combine Polygon Tool
======================

Merges adjacent and coplanar polygons into a polygon by selecting several polygons and clicking on ``Combine`` button.

.. figure:: /images/UModeler_CombinePolygonTool.gif
   :scale: 95 %
   
   Combines the selected polygons.

------------------------------------------------------------------------------------------------------

Combine Object Tool
======================

Combines the selected game objects with UModeler component to be an object by selecting several game objects and clicking on ``Combine`` button.

.. figure:: /images/UModeler_CombineObjectTool.gif
   :scale: 95 %
   
   Merges the selected objects.

------------------------------------------------------------------------------------------------------

Remove Double Tool
=====================

Lets you merge automatically all the selected vertices within the specific distance.

Steps
--------
 1. Select vertices, edges or polygons.
 2. Go to ``Remove Double Tool``
 3. Adjust ``Distance`` property.

Properties
---------------

Distance
 Minimum distance to be merged.
 
.. figure:: /images/UModeler_RemoveDoublesTool.gif
   :scale: 95 %
	
   RemoveDoubles Tool Demo 

------------------------------------------------------------------------------------------------------

Collpase Tool
===================

Merges each edge island or vertex island into one vertex. This makes as many remaining vertices as islands of selection. (i.e. groups of linked selected vertices).

Steps
-------
 1. Select vertices or edges or polygons.
 2. Click on Collapse Tool button.

.. figure:: /images/UModeler_CollapseTool.gif
   :scale: 95 %
	
   Collapse Tool Demo

------------------------------------------------------------------------------------------------------

Cut Tool
===================

Cuts a mesh into two along a line drawn by dragging a mouse. Pressing ``SPACE`` while dragging will change the direction of cutting.

Interface
----------------   

``LMB Drag``
 Rotates the custom plane.   

Properties
---------------

Type
 * ``Single`` - Removes the polygons below the custom plane.
 * ``Both`` - Simply cuts a mesh and leaves all polygons.
 
Fill Facet
 Fills facets with polygons.
 
Select Above
 After cutting a mesh, selects all polygons above the custom plane.
 
.. figure:: /images/UModeler_CutTool.gif
   :scale: 95 %
	
   Cut Tool Demo

------------------------------------------------------------------------------------------------------

Clip Tool
===================

Cuts away the parts of the selected polygons under the ``Clip polygon``, which has to be selected after pressing ``Clip`` button.

.. figure:: /images/UModeler_ClipTool.gif
   :scale: 95 %
	
   Clip Tool Demo