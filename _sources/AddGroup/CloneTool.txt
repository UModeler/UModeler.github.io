############
Clone Tool
############

Clones the selected polygons along the line drawn by dragging a mouse. Pressing ``SPACE`` confirms the clone action and ``ESC`` cancels it.
   
Steps
---------------
1. Enter Clone tool.
2. Point a polygon you want to clone by putting the mouse over it if polygons are not selected when this tool is activated. 
3. Drag the mouse to draw a line. You can make sure that the cloned polygons will be aligned with the line.
4. Adjust ``Number``, ``Distance`` and ``Arrangement`` in ``Properties`` if necessary.

Interface
---------------   

``LMB Drag``
 Draws an edge where the clones will be placed.   

Properties
---------------

Number
 The number of clones

Distance
 The distance of an edge where the clones will be placed.

Arrangement
 * ``Divide`` - Creates clones arranged evenly between the starting point and the end point of the edge.
 * ``Multiply`` - Makes clones along the edge. The distance between the clones is the value of Distance property in Properties.
 
.. figure:: /images/UModeler_CloneSinglePolygonTool.gif
   :scale: 95 %

   Clones a polygon

.. figure:: /images/UModeler_CloneObjectTool_v2.gif
   :scale: 95 %

   Clones a set of polygons 