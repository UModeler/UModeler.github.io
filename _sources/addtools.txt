############
Add tools
############

PushPull Tool
===================

Properties
---------------

------------------------------------------------------------------------------------------------------

Multi PushPull Tool
======================

Properties
---------------

------------------------------------------------------------------------------------------------------

Extrude Edge Tool
===================

Properties
---------------

------------------------------------------------------------------------------------------------------

Inset Tool
===================

Properties
---------------

------------------------------------------------------------------------------------------------------

Boolean Tool
===================

Properties
---------------

------------------------------------------------------------------------------------------------------

Mirror Tool
===================

Properties
---------------

------------------------------------------------------------------------------------------------------

Loop Slice Tool
===================

``Loop Slice`` splits a loop of faces by inserting a new edge loop intersecting the chosen edge. The tool is interactive and has two steps:

 1. `Pre-visualizing the Cut` : After the tool is activated, move the cursor over a desired edge. The cut to be made is marked with a orange colored lines as you move the mouse over the various edges. Rolling ``Wheel`` up or down will increase or decrease the ``Split Number``. The to-be-created edge loop stops at the poles (tris and n-gons) where the existing face loop terminates.  
 2. `Sliding the new Edge Loop` : Once an edge is chosen via ``LMB``, you can move the mouse holding ``LMB`` to determine where the new edge loop will be placed. Releasing ``LMB`` will confirms this action.

.. figure:: /images/UModeler_LoopSliceTool.gif
   :scale: 95 %
   
   LoopSlice Tool Demo.
   
Properties
---------------

Split Number
 The number of the edge loop.

------------------------------------------------------------------------------------------------------

Follow Tool
===================

Extrudes a profile polygon along a path polygon. The steps to use this tool are as follows.

 1. Draw a profile polygon.
 2. Move the profile polygon near the starting point of a path polygon. Using ``Snap tool`` will help this.
 3. Select the profile polygon.
 4. Select the path polygon.
 5. Click on ``Follow tool``.
 
.. figure:: /images/UModeler_FollowTool.gif
   :scale: 95 %
   
   Follow Tool Demo.

------------------------------------------------------------------------------------------------------

Bevel Tool
=======================

The bevel tool allows you to create chamfered or rounded corners to geometry. A bevel is an effect that smooths out edges and corners. 

V ertices, Edges or Polygons have to be selected before selecting ``Bevel`` tool and then change the properties described below in the inspector.

.. figure:: /images/UModeler_BevelTool.gif
   :scale: 95 %
   
   Bevel Tool Demo.


Properties
---------------

Width
 The width of the bevel polygon.
 
Segments
 The number of segments. The greater the number of segments, the smoother the bevel.
 
Profile
 The side view of the bevel edge. This is between 0 and 1. 0.5 is completely flat.
 Values less than 0.5 gives concave bevel and values more than 0.5 gives convex bevel.
 
Clamp Overlap
 When selected, the bevel amount isn’t allowed to go larger than an amount that causes overlapping collisions with other geometry.

------------------------------------------------------------------------------------------------------

Bridge Tool
===================

Makes space surrounded by the selected elements in following cases. Thge

 1. More than three vertices are selected.
 2. Two unconnected edges are selected.
 3. More than two connected edges are selected.
 4. More than two polygons are selected. 
 
.. figure:: /images/UModeler_BridgeTool.gif
   :scale: 95 %
	
   Bridge Tool Demo

------------------------------------------------------------------------------------------------------

Clone Tool
===================

Clones the selected polygons along the line drawn by dragging a mouse. Pressing ``SPACE`` confirms the clone action and ``ESC`` cancels it.

.. figure:: /images/UModeler_ClonePolygonTool.gif
   :scale: 95 %
	
   Clones a polygon

.. figure:: /images/UModeler_CloneObjectTool.gif
   :scale: 95 %
	
   Clones a set of polygons 

Properties
---------------

Number
 The number of clones
 
Distance
 The distance of an edge where the clones will be placed.
 
Arrangement
 * ``Divide`` - Creates clones arranged evenly between the starting point and the end point of the edge.
 * ``Multiply`` - Makes clones along the edge. The distance between the clones is the value of Distance property in Properties.

------------------------------------------------------------------------------------------------------

Copy Tool
===================

Copies the selected elements. The copied polygons' center cubes will have pink color, which means that they will move separately by a gizmo.

.. figure:: /images/UModeler_CopyTool.gif
   :scale: 95 %
	
   Copy Tool Demo