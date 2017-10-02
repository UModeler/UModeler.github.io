################
Drawing Tools
################

.. tip::

   | 1. Pressing ``SPACE`` confirms the current action. On the other hand ``ESC`` cancels it.
   | 2. You can adjust a shape by chaning the properties before confirming.

Line Tool
==========

You can draw edges on a surface or on a floor in a row. The mouse cursor will be snapped to a vertex, a center of edge, a center of polygon etc when the cursor gets close enough to them.

Steps
-------
1. Select ``Line`` tool under Drawing
2. Click ``LMB`` on where you want to start to draw.
3. Click ``LMB`` to place another point to draw an edge.
4. You can draw successive edges by putting points until pressing ``SPACE``.
5. If you want to go back to the previous point, Press ``ESC``.

Interface
------------
LMB
 Places a point
 
SPACE
 Confirms the drawn edges.
 
ESC
 Cancels the previous point.

---------------------------------------------------------------------------------------------

Arc Tool
==========

Draws an arc by setting three points on a plane.

Steps
-------
1. Select ``Arc`` tool
2. Click on where you want to start to draw an arc
3. Drag the mouse to set the second point.
4. Release ``LMB`` and move the mouse cursor to set the third point of the arc.
5. If necessary, adjust ``Segment`` property in the inspector.
6. Press ``SPACE`` to complete drawing the arc or if you want to cancel the arc, press ``ESC``.

Interface
------------
LMB drag
 Sets the first and second points.

SPACE
 Completes drawing an arc.
 
ESC
 Cancels drawing an arc.


Properties
------------
Segment
 How many edges an arc will have.

Close
 When Close property is enabled, the first and last vertices will be connected to create a closed form.

---------------------------------------------------------------------------------------------

Rectangle Tool
===============
Draws a rectangle by dragging the mouse to set two corners.
 
Steps
--------
1. Go to ``Rectangle`` tool under Primitive Shapes.
2. Drag a mouse to set two corner points on any plane.
3. Release ``LMB``.
4. If necessary, adjust ``Width``, ``Height`` or ``Corner Length`` properties.
5. Press ``SPACE`` to confirm the rectangle. If you want to cancel the rectangle, Press ``ESC``.

Properties
------------
Width
 The width of the rectangle.

Depth
 The depth  of the rectangle.

Corner Length
 The length of the rounded corners. The rounded corners are only applied as this is more than 0.0.

Corner Segment
 The segment number of the corner.

---------------------------------------------------------------------------------------------

Disk Tool
===========
 Draws a disk by setting a center and a radius.

Steps
-----------
1. Select ``Disk`` tool
2. Drag the mouse to draw a disk by setting a center and a radius of a disk.
3. You can type more precise radius and the number of segment in ``Radius`` and ``Segment`` fields in Properties.
4. Press ``SPACE`` to complete or Press ``ESC`` to cancel.

Properties
------------
Segment 
 The number of edges/segments

Radius
 Radius of a disk

Angle Snap
 When you drag the mouse with this property on, the disk’s direction will snap to every 90 degree.

---------------------------------------------------------------------------------------------

Side Stair Tool
=================	
You can draw a stair profile on a plane with this tool.

Interface
------------
LMB Drag
 Draws a stair profile
 
SPACE
 Confirmation
 
ESC
 Cancellation

Properties
------------
Rise
 Distance between two treads.

Flip
 Flips the drawn stair profile.

---------------------------------------------------------------------------------------------

Parallel Tool
===============
The closest edge of the polygon where the mouse cursor points gets copied and the copied edge will be moved parallel to the original edge following the mouse.

Steps
--------
1. Select ``Parallel`` tool
2. Move the mouse cursor to any point nearby the edge you want to copy and move.
3. Start to drag the mouse holding ``LMB`` in a normal direction of the original edge.
4. Release ``LMB`` where you want to put the copied edge.
5. Type ``Distance`` property if you want the precise distance.
6. Press ``SPACE`` to confirm what you did or Press ``ESC`` to cancel it.

Interface
------------
LMB Drag
 Copies and moves the edge in a parallel direction.
 
SHIFT + LMB
 Duplicates the previous Parallel action.
 
SPACE
 Confirmation
 
ESC
 Cancellation

Properties
------------
Distance
 Distance from the original edge.