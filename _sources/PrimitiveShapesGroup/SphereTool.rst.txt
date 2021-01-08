.. |Icon_PrimitiveShapes_Sphere| image:: /images/Icon_PrimitiveShapes_Sphere.png
   :scale: 100 %

################################################
Sphere Tool |Icon_PrimitiveShapes_Sphere|
################################################

Creates a sphere

Steps
--------
1. Enter ``Sphere Tool``
2. Drag the mouse holding ``LMB`` to define a radius. The sphere will be created from the center of the bottom.
3. You can type more precise values of ``Segment`` and ``Radius`` if necessary.
4. Press ``SPACE`` to complete or Press ``ESC`` to cancel.

Interface
--------------
``LMB Drag``
 Creates a sphere
 
``SPACE``
 Completes
 
``ESC``
 Cancels

Properties
---------------
Select Only Visible
 If on, the shape can be built on only a visible polygon. Namely backfaced or occluded polygons are excluded.
 
Floor Height
 The height of the floor where the primitive shape is built by LMB Dragging.
 
Segments
 How many the sphere will be divided

Radius
 A radius of the sphere

Angle Snap
 When you drag the mouse with this property on, the sphere’s forward direction will snap to every 90 degree time.
 
.. figure:: /images/UModeler_Sphere_OnTheFloor.jpg
   :scale: 95 %

   Sphere on the floor.
   
.. figure:: /images/UModeler_Sphere_OnPolygon.jpg
   :scale: 95 %

   Sphere on the other polygon.   