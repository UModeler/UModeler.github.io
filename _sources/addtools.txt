############
Add Tools
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

Fills gaps between the original edges and the corresponding transformed edges with polygons. The edges are transformed using ``Translate``, ``Rotate`` or ``Scale`` gizmo.

You can also select new edges in this tool for continuous edge extrusion.

.. figure:: /images/UModeler_EdgeExtrudeTool.gif
   :scale: 95 %

   Extrude Edge Tool Demo.

.. figure:: /images/UModeler_EdgeExtrudeTool_SnapToPolygon.gif
   :scale: 95 %

   ``Snap To Polygon`` property example and shows a new edge is selected without exiting the tool.

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

------------------------------------------------------------------------------------------------------

Inset Tool
===================

This tool creates a slightly smaller or bigger polygon of the selected one. 

Move the cursor over a desired polygon and start to drag a mouse. Then you'll see that the polygon outline will be bigger or smaller. Release ``LMB`` to be done. Try to change the properties in the inspector if necessary. And press ``SPACE`` to confirm.

Multiple Inset
 If several polygons are already selected when ``Inset Tool`` is activated, ``Inset`` will be applied to them at once. 
 
Repeat the previous
 ``SHIFT + LMB`` on a desired polygon repeats the previous inset.
 
.. figure:: /images/UModeler_InsetTool.gif
   :scale: 95 %

   Inset Tool Demo. 

Properties
---------------
Thickness
 How smaller or bigger the polygon is. This is a distance between the starting point and the current point.

Type (for ``Multiple Inset``)
 * ``Individual`` -  Each selected face is inset on its own.
 * ``Group`` - ``Inset Tool`` operates on the region around selected faces

Bridge Edges
 Links corresponding edges between the original polygon and the inset polygon.

------------------------------------------------------------------------------------------------------

Boolean Tool
===================

This tool creates a single game object out of two game objects by applying one of the three boolean operations. The steps is as follows.

1. Select two game objects with UModeler component.
2. Select Boolean tool
3. Choose one of Union, Subtract and Intersection in the inspector.

.. figure:: /images/UModeler_BooleanTool.gif
   :scale: 95 %

   Boolean Tool Demo.

Properties
---------------
Union
 Boolean Union

Subtract
 Boolean Subtract

Intersection
 Boolean Intersection

------------------------------------------------------------------------------------------------------

Mirror Tool
===================

Mirrors a mesh along its local X,Y or Z Axes. When the mirror mode is enabled, every change will be reflected to the other side each time the mesh is modified.

.. figure:: /images/UModeler_MirrorTool.gif
   :scale: 95 %

   Mirror Tool Demo.

Properties
---------------

Axis
 Plane mirror axis

Invert
 Inverts the direction of the plane mirror.

Distance
 The distance of the plane mirror

Leave Boundary
 Leaves a boundary after finishing the mirror mode.

Start
 Starts the mirror mode.

Done
 Finishes the mirror mode.

------------------------------------------------------------------------------------------------------

Loop Slice Tool
===================

``Loop Slice`` splits a loop of faces by inserting a new edge loop intersecting the chosen edge. The tool is interactive and has two steps:

 1. ``Pre-visualizing the Cut`` - After the tool is activated, move the cursor over a desired edge. The cut to be made is marked with a orange colored lines as you move the mouse over the various edges. Rolling ``Wheel`` up or down will increase or decrease the ``Split Number``. The to-be-created edge loop stops at the poles (tris and n-gons) where the existing face loop terminates.
 2. ``Sliding the new Edge Loop`` - Once an edge is chosen via ``LMB``, you can move the mouse holding ``LMB`` to determine where the new edge loop will be placed. Releasing ``LMB`` will confirms this action.

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

Fills space surrounded by the selected elements in following cases. The steps are as follows.

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

.. figure:: /images/UModeler_CloneSinglePolygonTool.gif
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