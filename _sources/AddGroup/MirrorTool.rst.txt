.. |Icon_Add_Mirror| image:: /images/Icon_Add_Mirror.png
   :scale: 100 %
   
####################################
Mirror Tool |Icon_Add_Mirror|
####################################
   
Mirrors a mesh along its local X,Y or Z Axes. When the mirror mode is enabled, every change will be reflected to the other side each time the mesh is modified.
   
Steps - Start Mirror Mode
--------------------------------
1. Select ``Mirror Tool``.
2. Adjust ``Axis``, ``Distance`` and ``Invert`` properties to set the mirror plane.
3. Click on ``Start`` button.

.. note::

 You can move the mirror plane by dragging the arrow or clicking a vertex.

Steps - Confirm
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
 
.. figure:: /images/UModeler_Mirror_0.jpg
   :scale: 95 %

   Sets the Mirror Plane
   
.. figure:: /images/UModeler_Mirror_1.jpg
   :scale: 95 %

   Starts the mirror mode.  

.. figure:: /images/UModeler_Mirror_2.jpg
   :scale: 95 %

   Fininsh the mirro mode.