################
Selection Tools
################

.. note::

   Selection tools responds immediately to clicking on a button of each tool.

All/None Tool
==============

If there are any selected elements, they will be unselected. Otherwise, all elements will be selected.

Steps
-------
1. Click on ``All/None Tool`` button.

.. figure:: /images/UModeler_AllNoneSelectionTool.gif
   :scale: 95 %

   All/None Selection Demo 

-------------------------------------------------------------------------------------------------------------------------   

Isolated Tool
==============

Selects geometry connected to already selected elements. This is often useful when a mesh has disconnected but overlapping parts

Steps
--------
1. Select ``Isloated Tool`` with any elements selected.

.. figure:: /images/UModeler_IsolatedSelection_v2.gif
   :scale: 95 %

   Isolated Selection Demo
   
-------------------------------------------------------------------------------------------------------------------------   

Loop Tool
==============

Edge Loop
------------

Selects a loop of edges that are connected in a line end to end.

Quad Loop
------------

Serial quad polygons across a mesh will be selected in a direction of the first two selected quad.

.. figure:: /images/UModeler_LoopSelectionTool.gif
   :scale: 95 %

   Edge Loops and Quad Loops

Hole Selection
---------------

If the selected edge is a part of a hole, all the edges of the holes will be selected.

Steps
---------
1. Select an edge if you want ``Edge Loops`` or ``Hole Selection``. Select two series quad polygons if you want ``Quad Loops``.
2. Select ``Loop Tool``.

.. figure:: /images/UModeler_HoleSelection_v2.gif
   :scale: 95 %

   Hole edge selection.

-------------------------------------------------------------------------------------------------------------------------   

Ring Tool
==============

Edge Ring
------------

Selects a sequence of edges that are not connected, but on opposite sides to each other continuing along a face loop

Quad Ring
------------

Lets you select several polygons across a mesh without having to select each polygon individually.

Steps
------------
1. If you want ``Edge Rings`` select an edge using Edge tool. If you want ``Quad Rings`` select two series quad polygons.
2. Select ``Ring Tool``.

.. figure:: /images/UModeler_RingSelectionTool.gif
   :scale: 95 %

   Edge Rings and Quad Rings 

-------------------------------------------------------------------------------------------------------------------------

Invert Tool
==============

The selection will be inverted. It means the selected ones will get deselected and the deselected ones will get selected.

Steps
--------
1. Select vertices, edges or a polygons.
2. Select ``Invert Tool``.

.. figure:: /images/UModeler_InvertSelection_v2.gif
   :scale: 95 %

   Edge Rings and Quad Rings


-------------------------------------------------------------------------------------------------------------------------

Increase Tool
==============

Expands the current selection outwards in all directions from the current selected elements.

Steps
--------
1. Select vertices, edges or a polygons.
2. Select ``Increase Tool``.

.. figure:: /images/UModeler_IncreaseSelection_v2.gif
   :scale: 95 %

   Edge Rings and Quad Rings