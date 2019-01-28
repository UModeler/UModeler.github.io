########################
Cylinder Tool
########################

.. figure:: /images/Icon_PrimitiveShapes_Cylinder.png
   :scale: 100 %
   
   ``Cylinder Tool`` icon

Creates a cylinder

Steps
----------
1. Select ``Cylinder Tool``
2. Drag the mouse on a floor or an another polygon to draw a disk.
3. Release ``LMB`` and move the mouse cursor in a normal direction to raise the height.
4. Click ``LMB`` to stop raising.
5. Type the count of edges in ``Segment`` field, radius in ``Radius`` field and height in ``Height`` field if necessary.
6. Press ``SPACE`` to complete or Press ``ESC`` to cancel.

Interface
-------------
``LMB Drag``
 Draws a disk.
 
``SPACE``
 Completes creating a cylinder
 
``ESC``
 Cancels creating a cylinder.

Properties
---------------
Segment
 The count of side faces

Radius
 A radius of a cylinder

Height
 A height of a cylinder

Angle Snap
 When you drag the mouse with this property on, the disk’s direction will snap to every 90 degree.

Border Check
 If this is enabled, the ray cast will run and it checks if the created cylinder is beyond the other polygons. It might cause a stop for a second at the beginning.
 
Glue
 The cylinder with this property enabled will be glued to the polygon where it started to be created. It means that the hidden part of the floor polygon by the created cylinder is removed.

.. figure:: /images/UModeler_Cylinder_OnFloor.jpg
   :scale: 95 %

   Cylinder on the floor.
   
.. figure:: /images/UModeler_CylinderTool_OnPolygon.jpg
   :scale: 95 %

   Cylinder on the other polygon.