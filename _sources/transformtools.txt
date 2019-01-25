################
Elements Group
################

Vertex / Edge / Polygon tool
=============================

There are 4 types of elements you can select and transform.

.. figure:: /images/Icon_Elements_Vertex.png
   :scale: 100 %

   Vertex Tool 

.. figure:: /images/Icon_Elements_Polygon.png
   :scale: 100 %
   
   Edge Tool

.. figure:: /images/Icon_Elements_Edge.png
   :scale: 100 % 
   
   Polygon Tool
   
.. figure:: /images/Icon_Elements_Object.png
   :scale: 100 % 
   
   Object Tool
   
I think these tools are used most frequently in UModeler so they are located at the top of the scene view. Firstly let me explain the Object Tool. With this tool you can select other objects, and move/rotate/scale them, which is same as Unity Object Mode.

Now let's see Vertex Tool, Edge Tool and Polygon Tool.

A mesh consists of vertices, edges and polygons. We call them elements. 

And there are gizmos which are displayed on the center of the selected elements and used for moving, rotating and scaling elements. They look like the following image roughly.

.. figure:: /images/gizmos.png
   :scale: 100 % 
   
   Source - `AutoDesk - About using 3D Gizmos <https://knowledge.autodesk.com/support/autocad/getting-started/caas/CloudHelp/cloudhelp/2016/ENU/AutoCAD-Core/files/GUID-7BD066C9-31BA-4D47-8064-2F9CF268FA15-htm.html>`_
   
You can select vertices and move/rotate/scale them with the Vertex Tool. 
The Edge Tool can make you select edges and move/rotate/scale them.
Using the Polygon tool, polygons can be selected and moved/rotated/scaled.

.. note::

  When you rotate and scale elements, the pivot position is usually the center of them. But when the 3D cursor is on, the cursor posision will be the pivot position. 
  
Basically selection of each element can be done by placing the mouse cursor there and pressing ``LMB``. And ``LMB`` dragging from an empty space will draw a rectangle and select elements inside the rectangle.

.. tip::

   | 1. You can add a new selection holding ``CTRL`` and pressing ``LMB`` on an element.
   | 2. Pressing ``W`` ``E`` or ``R`` changes the current gizmo like Unity.
   | 3. Dragging a mouse from an element causes moving the element
   | 4. If you hold ``SHIFT`` while dragging a gizmo, the selected elements are extruded.
   | 5. If you hold ``CTRL`` while dragging the move gizmo and moving to another vertex, the selected elements' selected axis's value will be snapped to the vertex. This is called ``1D snapping``
   | 6. If you hold ``SHIFT`` + ``CTRL`` while dragging a gizmo, the vertices consisting of the elements will be split.

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


Move To Cursor
 Moves the current selected elements to the 3D cursor position.

Insert Vertex
 Inserts a vertex to an adjacent edge to avoid T-junction.