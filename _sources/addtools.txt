############
Add Tools
############

.. note::

   `PushPull Tools` are :doc:`here </pushpulltools>`

Extrude Edge Tool
===================

Fills gaps between the original edges and the corresponding transformed edges with polygons. The edges are transformed using ``Translate``, ``Rotate`` or ``Scale`` gizmo.

You can also select new edges within this tool for continuous edge extrusion.
   
Steps
---------------
1. Select ``Extrude Edge Tool``.
2. Select several edges if there are no selected elements.
3. Move the translation gizmo by dragging to create polygons between the first edges and the new edges.   

Properties
---------------
Distance
 The extruded distance.
 
Snap to Polygon
 An edge is snapped to a closest polygon within a specific distance.
 
Snap to Vertex
 Unused.

Use 3D Cursor as Pivot
 Unused.

Both Sides
 Creates both sided polygons.

Invert
 Flips the last created polygons.
 
.. figure:: /images/UModeler_EdgeExtrudeTool.gif
   :scale: 95 %

   Extrude Edge Tool Demo.

.. figure:: /images/UModeler_EdgeExtrudeTool_SnapToPolygon.gif
   :scale: 95 %

   ``Snap To Polygon`` property example and shows a new edge is selected without exiting the tool. 

------------------------------------------------------------------------------------------------------

Inset Tool
===================

This tool creates a slightly smaller or bigger polygon of the selected one. 

Move the cursor over a desired polygon and start to drag a mouse. Then you'll see that the polygon outline will be bigger or smaller. Release ``LMB`` to be done. Try to change the properties in the inspector if necessary. And press ``SPACE`` to confirm.

Multiple Inset
 If several polygons are already selected when ``Inset Tool`` is activated, ``Inset`` will be applied to them at once. 
 
Repeat the previous
 ``SHIFT + LMB`` on a desired polygon repeats the previous inset. 
   
Steps - Single Inset
----------------------
1. Select ``Inset Tool`` with no selection.
2. Click on a polygon you want to apply Inset to.
3. Drag the cursor to define thickness.
4. Release ``LMB``
5. Adjust ``Thickness`` properties if necessary
6. Press ``SPACE`` or start another inset action to confirm.

Steps - Multiple Inset
----------------------
1. Select ``Inset Tool`` with some polygons selected using ``Polygon Tool``.
2. Start to drag the mouse from a polygon or adjust ``Thickness`` property directly.
3. If necessary, adjust ``Thickness`` property in ``Properties`` to give the precise value.
4. Press ``SPACE`` to complete or Press ``ESC`` to cancel.
   
Interface
---------------

``LMB Drag``
 Creates an inset of the selected polygon.

``SHIFT + LMB``
 Duplicates the previous inset.

``SPACE``
 Confirms the current inset.

``ESC``
  Cancels the current inset or exit Inset tool.

Properties
---------------
Thickness
 How smaller or bigger the polygon is. This is a distance between the starting point and the current point.

Type (for ``Multiple Inset``)
 * ``Individual`` -  Each selected face is inset on its own.
 * ``Group`` - ``Inset Tool`` operates on the region around selected faces

Bridge Edges
 Links corresponding edges between the original polygon and the inset polygon.
 
.. figure:: /images/UModeler_InsetTool.gif
   :scale: 95 %

   Inset Tool Demo.  

------------------------------------------------------------------------------------------------------

Boolean Tool
===================

This tool creates a single game object out of two game objects by applying one of the three boolean operations.
   
Steps
-----------

1. Select two game objects with UModeler component.
2. Select Boolean tool
3. Choose one of Union, Subtract and Intersection in the inspector.   

Properties
---------------
Union
 Boolean Union

Subtract
 Boolean Subtract

Intersection
 Boolean Intersection
 
.. figure:: /images/UModeler_BooleanTool.gif
   :scale: 95 %

   Boolean Tool Demo. 

------------------------------------------------------------------------------------------------------

Mirror Tool
===================

Mirrors a mesh along its local X,Y or Z Axes. When the mirror mode is enabled, every change will be reflected to the other side each time the mesh is modified.
   
Steps - Start Mirror Mode
--------------------------------
1. Select ``Mirror Tool``.
2. Adjust ``Axis``, ``Distance`` and ``Invert`` properties to set the mirror plane.
3. Click on ``Start`` button.

Steps - Comfirm
--------------------------------
1. Select ``MirrorTool``.
2. If you want to leave a boundary between the original part and the mirrored part, check ``Leave Boundary`` property.

Properties
---------------
Axis
 Plane mirror axis

Invert
 Inverts the direction of the plane mirror.

Distance
 The distance of the plane mirror

Boundary
 How to deal with the boundary edges between the edited part and the mirrored part.
  * ``Remove`` : Removes the boundary edges.
  * ``Remain`` : Remains the boundary edges.
  * ``Ignore`` : Ignores the polygons across boundary edges as mirroring is done. 

Start
 Starts the mirror mode.

Done
 Finishes the mirror mode.
 
.. figure:: /images/UModeler_MirrorTool.gif
   :scale: 95 %

   Mirror Tool Demo. 

------------------------------------------------------------------------------------------------------

Loop Slice Tool
===================

``Loop Slice`` splits a loop of faces by inserting a new edge loop intersecting the chosen edge.
   
Steps
-------------
1. Select ``Loop SliceTool``.
2. Move the cursor over a desired edge
3. Scroll ``Wheel`` of the mouse to increase or decrease the number of edge loops.
4. Drag the mouse to changes the offset of the edge loops.
5. Release ``LMB`` to finish.

Inteface
-------------   
``LMB Drag``
 Moves the edge loops.
 
``Scroll Wheel``
 Increases  or decreases the number of edge loop.

Properties
---------------

Split Number
 The number of the edge loop.
 
.. figure:: /images/UModeler_LoopSliceTool_v2.gif
   :scale: 95 %

   LoopSlice Tool Demo. 

------------------------------------------------------------------------------------------------------

Follow Tool
===================

Extrudes a profile polygon along a path polygon. The steps to use this tool are as follows.
   
Steps
--------
 1. Draw a profile polygon.
 2. Move the profile polygon near the starting point of a path polygon. Using ``Snap Tool`` will help this.
 3. Select the profile polygon.
 4. Select the path polygon.
 5. Click on ``Follow Tool``.   
 
.. figure:: /images/UModeler_FollowTool_v2.gif
   :scale: 95 %

   Follow Tool Demo. 

------------------------------------------------------------------------------------------------------

Bevel Tool
=======================

The bevel tool allows you to create chamfered or rounded corners to geometry. A bevel is an effect that smooths out edges and corners.

Vertices, Edges or Polygons have to be selected before selecting ``BevelTool`` and then change the properties described below in the inspector.
   
Steps
--------
1. Select Vertex(s), edge(s) or polygon(s) with ``VertexTool``, ``EdgeTool``, or ``PolygonTool``.
2. Adjust ``Width``, ``Segments`` or ``Profile`` value in Properties.

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
 
.. figure:: /images/UModeler_BevelTool.gif
   :scale: 95 %

   Bevel Tool Demo. 

------------------------------------------------------------------------------------------------------

Bridge Tool
===================

Fills space surrounded by the selected elements in following cases. The steps are as follows.

 1. More than three vertices are selected.
 2. Two unconnected edges are selected.
 3. More than two connected edges are selected.
 4. More than two polygons are selected.
   
Steps
---------
1. Select vertices/edges/polygons using ``VertexTool``, ``EdgeTool`` or ``PolygonTool``.
2. Select Bridge tool.

.. figure:: /images/UModeler_BridgeTool_v2.gif
   :scale: 95 %

   Bridge Tool Demo

------------------------------------------------------------------------------------------------------

Clone Tool
===================

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

------------------------------------------------------------------------------------------------------

Duplicate Tool (Formerly called Copy Tool)
==============================================

Duplicates the selected polygons. The duplicated polygons' center cubes will have pink color, which means that they will move separately by a gizmo.
   
Steps
---------
1. Select several polygons with ``Polygon Tool``.
2. Select ``Duplicate Tool``.
   
.. figure:: /images/UModeler_CopyTool.gif
   :scale: 95 %

   Duplicate Tool Demo   