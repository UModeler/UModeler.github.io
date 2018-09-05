################
Elements Group
################

.. note::

 Since version 2.2 ``Transform Group`` name has been renamed to ``Elements Group``.

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
   | 4. If you hold ``SHIFT`` while dragging a gizmo, the selected elements are extruded.
   | 5. If you hold ``CTRL`` while dragging a translation gizmo and moving to another vertex, the selected elements' selected axis's value will be snapped to the vertex. This is called ``1D snapping``
   | 6. If you hold ``SHIFT`` + ``CTRL`` while dragging a gizmo, the selected elements are transformed separately from the adjacent polygons.   

Properties
-----------

.. _selectonlyvisibleintransform:

Select Only Visible
 If on, Selects only visible vertices/edges/polygons from a camera. Occluded elements from other polygons will not be selected. This is available only when the game object has MeshCollider component.

Distance
 How distant the selected elements move. This is only available as translation gizmo is enabled.

Snap To Polygon
 An edge is snapped to a close polygon within a specific distance. This is only available as the edge is being translated.

Snap To Vertex
 A vertex is snapped to the other close vertex within a specific distance. This is only available as the vertex is being translated.

Cursor As Pivot 
 Rotates the selected elements around the 3D cursor.

.. note::

 Since version 2.2 ``Cursor As Pivot`` property has been removed. Instead 3D cursor is used as pivot while it is enabled.

Move To Cursor
 Moves the current selected elements to the 3D cursor position.

Insert Vertex
 Inserts a vertex to an adjacent edge to avoid T-junction.

.. figure:: /images/UModeler_TransformTool_v2.gif
   :scale: 95 %

   Selecting and transforming elements.

.. _basicextrusionintransform:

.. figure:: /images/UModeler_BasicExtrusion_In_TransformTool.gif   
   :scale: 95 %

   Extruding polygons and edges by moving a gizmo holding ``SHIFT``.

.. figure:: /images/UModeler_TransformHoldingShift_v2.gif
   :scale: 95 %

   Transforming elements holding ``SHIFT`` + ``CTRL``.

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

3D Cursor Tool
=========================================

.. note::

 Since version 2.2 ``3D Cursor Tool`` has been replaced with a toggle called ``Use 3D Cursor`` in ``Settings``. 
 Click :ref:`this <Use3DCursor>` to move to the description.

----------------------------------------------------------------------------------------------------------------------

Pivot Tool
====================================

.. note::

 Since version 2.2 ``Pivot Tool`` has moved to ``Tweak`` group.  
 Click :ref:`this <PivotTool>` to move to new Pivot tool desc. 

----------------------------------------------------------------------------------------------------------------------

Snap tool
==========

.. note::

 Since version 2.2 ``Snap Tool`` has moved to ``Tweak Group`` and it has been renamed to ``Snap Move Tool``.
 Click :ref:`this <SnapMoveTool>` to move to new Snap Move Tool desc. 