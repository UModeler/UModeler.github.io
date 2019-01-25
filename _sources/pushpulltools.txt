.. _pushpull_tool_label:

################
Push/Pull Tools
################

.. tip::

 If you want a uniform size of height in ``PushPull Tool``, enable ``Snap`` in ``Settings > Snap``

PushPull Tool
=====================

Extrudes a polygon in a normal direction of it. You can push/pull any type of polygon, including circular, rectangular, and abstract polygons.
   
Steps
-----------
1. Go to ``PushPull Tool`` with no selection
2. Move the mouse cursor to a polygon you want to extrude
3. Start to drag from the polygon in a normal direction of it.
4. Release ``LMB`` when you finish the extrusion.
5. If you need the precise height, fill ``Height`` field out in ``Properties``.
6. Press ``SPACE`` to confirm or press ``ESC`` to cancel.

Interface
-----------

``LMB Drag``
 Pushes or pulls a polygon in a normal direction of the polygon.
 
``CTRL + LMB Drag``
 Pushes or pulls a polygon at a time so that its height will be aligned to the other parallel polygon where the mouse points.
 
``SHIFT + LMB``
 Repeats the previous extrusion to double the size of the extrusion or create a separate but identical extrusion.
 
``SPACE``
 Confirms ``Push/Pull``.
 
``ESC``
 Cancels ``Push/Pull`` or exit ``Push/Pull``.
 
Properties
---------------

Height
 Precise height.

Border Check
 If this is enabled, the ray cast will run and it checks if the new created polygons while pushing or pulling will be beyond the other polygons. This can be used to cut a 3d shape, too.
 
.. note::

 Please note that ``Border Check`` property needs many pre-calculations so it may affect the performance. Therefore, if you feel any lag at the beginning of push/pull, please turn this property off and try again.
 
Continuous
 If off, the boundary edges between the existing side polygons and the new side polygons will be left. 

.. figure:: /images/UModeler_PushPullToolBasic.gif
   :scale: 95 %

   Basic PushPull Tool Demo - ``Height`` and ``Continuous`` properties
   
.. figure:: /images/UModeler_PushPullToolBoundaryCheck.gif
   :scale: 95 %

   ``Boundary Check`` property Demo   

.. figure:: /images/UModeler_PushPullToolDuplicateThePrev.gif
   :scale: 95 %

   Duplicate the previous extrusion by ``SHIFT + LMB``.
   
.. figure:: /images/UModeler_PushPullToolHeightAlignment.gif
   :scale: 95 %
   
   Height Aligntment ``CTRL + LMB Drag``
   
------------------------------------------------------------------------------------------------------

Multi PushPull Tool
======================

Multiple polygons are pushed or pulled along a helper arrow

Steps
---------------
1. Go to ``Multi PushPull Tool``.
2. If no selected polygons, select several polygons. Then you can see the ``Help arrow`` in yellow.
3. Click ``LMB`` on any point on the ``Helper arrow``.
4. Drag the mouse in a direction of the the arrow.
5. If necessary, adjust ``Distance`` property.
 
Interface
---------------
``LMB Drag``
 It should start on a helper arrow and the mouse should be dragged along it.
 
``ESC``
 Exits this tool.

Properties
---------------
Select Only Visible
 If on, Selects only visible vertices/edges/polygons from a camera. Occluded elements from other polygons will not be selected. This is available only when the game object has MeshCollider component.

Distance
 How long the selected polygons are extruded

Pushpull Type
 * ``Individual Polygon`` : The selected polygons are extruded in each normal direction of the polygons.
 * ``Vertex Normal`` : The selected polygons are extruded in each normal direction of the vertices.
 * ``Average Normal`` : The selected polygons are extruded in the average direction of them.
 * ``X`` : The selected polygons are extruded in X-axis direction.
 * ``Y`` : The selected polygons are extruded in Y-axis direction.
 * ``Z`` : The selected polygons are extruded in Z-axis direction.
 
.. note::

 Since version 2.1.1 ``Individual`` type has been renamed to ``Individual Polygon`` type and ``Vertex Normal`` type has been added.
  

Continuous
 If off, the boundary edges between the existing side polygons and the new side polygons will be left.
 
One Step Size
 The size of one step push/pull. This size are set from the grid snap size as default.

One Step Push
 Extrudes the selected polygons back by the one step size.

One Step Pull 
 Extrudes the selected polygons forward by the one step size.
 
.. figure:: /images/UModeler_MultiPushPullTool.gif
  :scale: 95 %
   
  Multi PushPull Tool Demo.
 
.. _vertexnormalpushpull:
.. figure:: /images/UModeler_MultiplePushPull_3types.gif
  :scale: 95 %
   
  3 types of Multi PushPull action - ``Individual Polygon``, ``Vertex Normal`` and ``Average Normal`` 

.. _onesteppushpull:
.. figure:: /images/UModeler_MultiPushPull_Onestepextrusion.gif
  :scale: 95 %
  
  One Step Push/Pull.