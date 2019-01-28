#####################
Loop Selection Tool
#####################

.. |Icon_Selection_LoopSelectEdge| image:: /images/Icon_Selection_LoopSelectEdge.png
   :scale: 100 %

.. |Icon_Selection_LoopSelectPolygon| image:: /images/Icon_Selection_LoopSelectPolygon.png
   :scale: 100 %

Edge Loop |Icon_Selection_LoopSelectEdge|
------------------------------------------------

Selects a loop of edges that are connected in a line end to end. 

.. figure:: /images/UModeler_EdgeLoop_0.jpg
   :scale: 95 %
   
.. figure:: /images/UModeler_EdgeLoop_1.jpg
   :scale: 95 %

Hole Selection |Icon_Selection_LoopSelectEdge|
------------------------------------------------------------

If the selected edge is a part of a hole, all the edges of the holes will be selected.

.. figure:: /images/UModeler_HoleLoop_0.jpg
   :scale: 95 %
   
.. figure:: /images/UModeler_HoleLoop_1.jpg
   :scale: 95 %

Quad Loop |Icon_Selection_LoopSelectPolygon|
------------------------------------------------

Serial quad polygons across a mesh will be selected in a direction of the first two selected quad.

.. figure:: /images/UModeler_PolygonLoop_0.jpg
   :scale: 95 %
   
.. figure:: /images/UModeler_PolygonLoop_1.jpg
   :scale: 95 %

Steps
---------
1. Select an edge if you want ``Edge Loops`` or ``Hole Selection``. Select two series quad polygons if you want ``Quad Loops``.
2. Select ``Loop Tool``.