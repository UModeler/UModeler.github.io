###############
Combine Tool
###############

.. |Icon_Remove_CombineVertices| image:: /images/Icon_Remove_CombineVertices.png
   :scale: 100 %

.. |Icon_Remove_CombinePolygons| image:: /images/Icon_Remove_CombinePolygons.png
   :scale: 100 %
   
.. |Icon_Remove_CombineObjects| image:: /images/Icon_Remove_CombineObjects.png
   :scale: 100 %   
   
Combine Vertices Tool |Icon_Remove_CombineVertices|
==================================================================

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
 
.. |UModeler_CombineVertices_0| image:: /images/UModeler_CombineVertices_0.jpg
   :scale: 100 %
   
.. |UModeler_CombineVertices_1| image:: /images/UModeler_CombineVertices_1.jpg
   :scale: 100 %

.. |UModeler_CombineVertices_2| image:: /images/UModeler_CombineVertices_2.jpg
   :scale: 100 %
   
|UModeler_CombineVertices_0| 
 Two groups of vertices are selected.

|UModeler_CombineVertices_1| 
  With ``Collapse`` property off, all the selected vertices will be merged to one vertex.

|UModeler_CombineVertices_2| 
  On the other hand with ``Collapse`` property on, the vertices will be merged to two.

------------------------------------------------------------------------------------------------------

Combine Polygon Tool |Icon_Remove_CombinePolygons|
==================================================================

Merges adjacent and coplanar polygons into a polygon by selecting several polygons and clicking on ``Combine`` button.

.. |UModeler_CombinePolygons_0| image:: /images/UModeler_CombinePolygons_0.jpg
   :scale: 100 %
   
.. |UModeler_CombinePolygons_1| image:: /images/UModeler_CombinePolygons_1.jpg
   :scale: 100 %

|UModeler_CombinePolygons_0| |UModeler_CombinePolygons_1|
	All adjacent and coplanar polygons are combined.

------------------------------------------------------------------------------------------------------

Combine Object Tool |Icon_Remove_CombineObjects|
==================================================================

Combines the selected game objects with UModeler component to be an object by selecting several game objects and clicking on ``Combine`` button.

.. |UModeler_CombineObjects| image:: /images/UModeler_CombineObjects.jpg
   :scale: 100 %
   
|UModeler_CombineObjects|   
   Merges the selected objects.