################
Selection Group
################

.. figure:: /images/Icon_Group_Selection.png
   :scale: 100 %
   
   ``Selection Group`` icon

.. note::

   Selection tools responds immediately to clicking on a button of each tool.

All Selection Tool
===================

.. figure:: /images/Icon_Selection_AllSelectVertex.png
   :scale: 100 %
   
   Vertex All Selection Tool

   
.. figure:: /images/Icon_Selection_AllSelectEdge.png
   :scale: 100 %

   Edge All Selection Tool
   
.. figure:: /images/Icon_Selection_AllSelectPolygon.png
   :scale: 100 %

   Polygon All Selectin Tool

If there aren't any selected elements, all elements will be selected immediately after selecting this tool. The element type depends on which tool is selected just before this tool run.

-------------------------------------------------------------------------------------------------------------------------   

None Selection Tool
===================

.. figure:: /images/Icon_Selection_NoneSelect.png
   :scale: 100 %
   
   ``None Selection Tool`` icon
   
All the selected elements will be unselected when this tool button is clicked on.

-------------------------------------------------------------------------------------------------------------------------   

Isolated Selection Tool
=========================

Selects geometry connected to already selected elements. This is often useful when a mesh has disconnected but overlapping parts

Vertex Isolated Selection
---------------------------

.. figure:: /images/Icon_Selection_IsolatedSelectVertex.png
   :scale: 100 %   
   
   ``Vertex Isolated Selection Tool`` Icon
   
.. figure:: /images/UModeler_VertexIsolated_0.jpg
   :scale: 95 %
   
   If any vertices are selected, 

   
.. figure:: /images/UModeler_VertexIsolated_1.jpg
   :scale: 95 %
   
   All the vertices in the isolated geometry which includes the first select vertices will be selected.


Edge Isolated Selection
---------------------------

.. figure:: /images/Icon_Selection_IsolatedSelectEdge.png
   :scale: 100 %
   
   ``Edge Isolated Selection Tool`` Icon
   
.. figure:: /images/UModeler_EdgeIsolated_0.jpg
   :scale: 95 %
   
   If any edges are selected, 
   
.. figure:: /images/UModeler_EdgeIsolated_1.jpg
   :scale: 95 %
   
   All the edges in the isolated geometry which includes the first select edges will be selected.
   
Polygon Isloated Selection
---------------------------

.. figure:: /images/Icon_Selection_IsolatedSelectPolygon.png
   :scale: 100 %
   
   ``Polygon Isolated Selection Tool`` Icon   
   
.. figure:: /images/UModeler_PolygonIsolated_0.jpg
   :scale: 95 %
   
   If any polygons are selected, 
   
.. figure:: /images/UModeler_PolygonIsolated_1.jpg
   :scale: 95 %
   
   All the polygons in the isolated geometry which includes the first select polygons will be selected.   

   
-------------------------------------------------------------------------------------------------------------------------   

Loop Selection Tool
====================

Edge Loop
------------

.. figure:: /images/Icon_Selection_LoopSelectEdge.png
   :scale: 100 %
   
   ``Edge Loop Tool`` and ``Hole Selection Tool`` Icon

Selects a loop of edges that are connected in a line end to end.

.. figure:: /images/UModeler_EdgeLoop_0.jpg
   :scale: 95 %
   
.. figure:: /images/UModeler_EdgeLoop_1.jpg
   :scale: 95 %

Hole Selection
---------------

If the selected edge is a part of a hole, all the edges of the holes will be selected.

.. figure:: /images/UModeler_HoleLoop_0.jpg
   :scale: 95 %
   
.. figure:: /images/UModeler_HoleLoop_1.jpg
   :scale: 95 %

Quad Loop
------------

.. figure:: /images/Icon_Selection_LoopSelectPolygon.png
   :scale: 100 %
   
   ``Quad Loop`` Selection

Serial quad polygons across a mesh will be selected in a direction of the first two selected quad.

.. figure:: /images/UModeler_PolygonLoop_0.jpg
   :scale: 95 %
   
.. figure:: /images/UModeler_PolygonLoop_1.jpg
   :scale: 95 %

Steps
---------
1. Select an edge if you want ``Edge Loops`` or ``Hole Selection``. Select two series quad polygons if you want ``Quad Loops``.
2. Select ``Loop Tool``.

-------------------------------------------------------------------------------------------------------------------------   

Ring Selection Tool
====================

Edge Ring
------------

.. figure:: /images/Icon_Selection_RingSelectEdge.png
   :scale: 100 %
   
   ``Edge Ring Tool``  Icon

Selects a sequence of edges that are not connected, but on opposite sides to each other continuing along a face loop

.. figure:: /images/UModeler_EdgeRing_0.jpg
   :scale: 95 %
   
.. figure:: /images/UModeler_EdgeRing_1.jpg
   :scale: 95 %

Quad Ring
------------

.. figure:: /images/Icon_Selection_RingSelectPolygon.png
   :scale: 100 %
   
   ``Quad Ring Tool``  Icon

Lets you select several quad polygons across a mesh.

.. figure:: /images/UModeler_PolygonRing_0.jpg
   :scale: 95 %
   
.. figure:: /images/UModeler_PolygonRing_1.jpg
   :scale: 95 %

Steps
------------
1. If you want ``Edge Rings`` select an edge using Edge tool. If you want ``Quad Rings`` select two series quad polygons.
2. Select ``Ring Tool``.

-------------------------------------------------------------------------------------------------------------------------

Invert Selection Tool
==========================

.. figure:: /images/Icon_Selection_InvertSelectVertex.png
   :scale: 100 %
   
   ``Vertex Invert Tool`` icon
   
.. figure:: /images/Icon_Selection_InvertSelectEdge.png
   :scale: 100 %
   
   ``Edge Invert Tool`` icon

.. figure:: /images/Icon_Selection_InvertSelectPolygon.png
   :scale: 100 %
   
   ``Polygon Invert Tool`` icon

The selection will be inverted. It means the selected ones will get deselected and the deselected ones will get selected.

Steps
--------
1. Select vertices, edges or a polygons.
2. Select ``Invert Tool``.

-------------------------------------------------------------------------------------------------------------------------

Increase Selection Tool
===========================

Expands the current selection outwards in all directions from the current selected elements.

Vertex Increase Selection
-------------------------------

.. figure:: /images/Icon_Selection_IncreaseSelectVertex.png
   :scale: 100 %
   
   ``Vertex Increase Tool`` icon
   
.. figure:: /images/UModeler_IncreaseTool_Vertex.gif
   :scale: 95 %   


Edge Increase Selection
-------------------------------

.. figure:: /images/Icon_Selection_IncreaseSelectEdge.png
   :scale: 100 %
   
   ``Edge Increase Tool`` icon
   
.. figure:: /images/UModeler_Increase_edge.gif
   :scale: 100 %
   
   ``Edge Increase Tool`` icon

Polygon Increase Selection
-------------------------------

.. figure:: /images/Icon_Selection_IncreaseSelectPolygon.png
   :scale: 100 %
   
   ``Polygon Increase Tool`` icon
   
.. figure:: /images/UModeler_IncreaseTool.gif
   :scale: 100 %
   
   ``Polygon Increase Tool`` icon

Steps
--------
1. Select vertices, edges or a polygons.
2. Select ``Increase Tool``.