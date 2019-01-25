###############
Combine Tool
###############

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
Select Only Visible
 If on, Selects only visible vertices/edges/polygons from a camera. Occluded elements from other polygons will not be selected. This is available only when the game object has MeshCollider component.

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