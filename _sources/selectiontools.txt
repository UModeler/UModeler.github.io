################
Selection Tools
################

.. note::

   Selection tools responds immediately to clicking on a button of each tool.

All/None Tool
==============

If there are any selected elements, they will be unselected. Otherwise, all elements will be selected.

.. figure:: /images/UModeler_AllNoneSelection.gif
   :scale: 45 %

   All/None Selection Demo
   
-------------------------------------------------------------------------------------------------------------------------   

Isolated Tool
==============

Selects geometry connected to already selected elements. This is often useful when a mesh has disconnected, overlapping parts

.. figure:: /images/UModeler_IsolatedSelection.gif
   :scale: 40 %

   Isolated Selection Demo
   
-------------------------------------------------------------------------------------------------------------------------   

Loop Tool
==============

Edge Loops
------------

Selects a loop of edges that are connected in a line end to end.

Quad Loops
------------

Serial quad polygons across a mesh will be selected in a direction of the first two selected quad.

.. figure:: /images/UModeler_LoopSelection.gif
   :scale: 40 %

   Edge Loops and Quad Loops

Hole Selection
---------------

If the selected edge is a part of a hole, all the edges of the holes will be selected.

.. figure:: /images/UModeler_HoleSelection.gif
   :scale: 40 %

   Hole edge selection.

-------------------------------------------------------------------------------------------------------------------------   

Ring Tool
==============

Edge Rings
------------

Selects a sequence of edges that are not connected, but on opposite sides to each other continuing along a face loop

Quad Rings
------------

Lets you select several polygons across a mesh without having to select each polygon individually.

.. figure:: /images/UModeler_RingSelection.gif
   :scale: 40 %

   Edge Rings and Quad Rings

-------------------------------------------------------------------------------------------------------------------------

Invert Tool
==============
	
The selection will be inverted. It means the selected ones will get deselected and the deselected ones will get selected.

.. figure:: /images/UModeler_InvertSelection.gif
   :scale: 40 %

   Edge Rings and Quad Rings


-------------------------------------------------------------------------------------------------------------------------

Increase Tool
==============

Expands the current selection outwards in all directions from the current selected elements.

.. figure:: /images/UModeler_IncreaseSelection.gif
   :scale: 40 %

   Edge Rings and Quad Rings