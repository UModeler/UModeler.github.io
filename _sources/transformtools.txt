################
Transform Tools
################

Vertex / Edge / Polygon tool
=============================

There are 4 types of elements you can select and transform.

 • Vertex - A point containing position, uv and color. 
 • Edge - Two connected vertices.
 • Polygon - A simple polygon that can have holes.
 
To begin to transform elements, you have to select them at first. Which type of elements is transformed depends on what tool is selected in the inspector. 

.. tip::

   | 1. You can add a new selection holding ``CTRL`` and pressing ``LMB`` on an element.   
   | 2. Pressing ``W`` ``E`` or ``R`` changes the current gizmo like Unity. 
   | 3. Dragging a mouse from an element causes moving the element   
   | 4. If you hold ``SHIFT`` while dragging a gizmo, the selected elements are transformed separately from the adjacent polygons.
   | 5. If you hold ``CTRL`` while dragging a translation gizmo and moving to another vertex, the selected elements' selected axis's value will be snapped to the vertex. This is called ``1D snapping``
   
Properties
-----------

Distance
 How distant the selected elements move. This is only available as translation gizmo is enabled.
 
Snap To Polygon
 An edge is snapped to a close polygon within a specific distance. This is only available as the edge is being translated.
 
Snap To Vertex
 A vertex is snapped to the other close vertex within a specific distance. This is only available as the vertex is being translated.
 
Cursor As Pivot
 Rotates the selected elements around the 3D cursor.
 
Move To Cursor
 Moves the current selected elements to the 3D cursor position.
 
Insert Vertex
 Inserts a vertex to an adjacent edge to avoid T-junction.
 
.. figure:: /images/UModeler_TransformTool_v2.gif
   :scale: 95 %
	
   Selecting and transforming elements. 
   
.. figure:: /images/UModeler_TransformHoldingShift_v2.gif
   :scale: 95 %
	
   Transforming elements holding ``SHIFT``.   
   
.. figure:: /images/UModeler_TransformTool_SnapEdgeToPolygon.gif
   :scale: 95 %

   ``Snap To Polygon`` property Demo.
   
.. figure:: /images/UModeler_VertexTool_1dSnapping.gif
   :scale: 95 %

   1D Snapping holding ``CTRL``  
   
.. figure:: /images/UModeler_TransformTool_InsertVertexProperty.gif
   :scale: 95 %

   ``Insert Vertex`` property demo.

----------------------------------------------------------------------------------------------------------------------

Object tool
============
 Object mode. You can select and transform an object.
 
----------------------------------------------------------------------------------------------------------------------

.. _3DCursorTool:
 
3D Cursor tool
===============
 Sets a position of 3D cursor, which is used as a pivot of transfoming or target position or anything, by clicking on a blue box or dragging a translation gizmo.
 
.. note::

   | The 3D Cursor can be enabled via ``Settings`` / ``Display`` / ``Cursor`` in the inspector.
 
.. figure:: /images/UModeler_3DCursorTool.gif
   :scale: 95 %
   
   ``3D Cursor Tool`` Demo

----------------------------------------------------------------------------------------------------------------------

.. _PivotTool:

Pivot tool
============
 Sets a position of a pivot of the current object by clicking on a blue box or dragging a translation gizmo.
 
.. figure:: /images/UModeler_pivottool.gif
   :scale: 95 %
   
   ``Pivot Tool`` Demo
 
Properties
-----------

Candidate Set
 * ``Bound Box`` - Position set coming from the bound box.
 * ``Polygon`` - Position set coming from the vertices from the polygons.

----------------------------------------------------------------------------------------------------------------------

.. _SnapTool:
 
Snap tool
==========

Moves a polygon to the specific position. This tool can be used to set a profile polygon for ``Follow Tool``. 

Interface
----------- 
``SPACE``
 Flips the selected polygon horizontally.
 
``LMB Down``
 Selects a position.
 
``ESC``
 Goes back to the previous step or exits the Snap tool.

Properties
-----------

Flip
 Flips the polygon horizontally. 
 
 .. figure:: /images/UModeler_snaptool.gif
   :scale: 95 %
   
   ``Snap Tool`` Demo