####################
Multi PushPull Tool
####################

.. tip::

 If you want a uniform size of height in ``PushPull Tool``, enable ``Snap`` in ``Settings > Snap``

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