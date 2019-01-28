.. |Icon_PrimitiveShapes_Capsule| image:: /images/Icon_PrimitiveShapes_Capsule.png
   :scale: 100 %

########################################################################
Capsule Tool |Icon_PrimitiveShapes_Capsule|
########################################################################

Creates a capsule

Steps
------------
1. Select ``Capsule Tool``
2. Drag the mouse to draw a disk.
3. Release ``LMB`` and move the mouse in a normal direction to raise up a capsule.
4. Click ``LMB`` to stop.
5. Type the count of edges in ``Segment`` field, radius in ``Radius`` field and height in ``Height`` field if necessary.
6. Press ``SPACE`` to complete or Press ``ESC`` to cancel.

Interface
-------------
``LMB Drag``
 Draws a disk.
 
``SPACE``
 Completes creating a capsule.
 
``ESC``
 Cancels creating a capsule.

Properties
---------------
Segment
 The count of side faces

Radius
 A radius of a cone

Height
 A height of a cone

Angle Snap
 When you drag the mouse with this property on, the capsule’s forward direction will snap to every 90 degree.

Border Check
 If this is enabled, the ray cast will run and it checks if the created capsule is beyond the other polygons. It might cause a stop for a second at the beginning.

Glue
 This property in Capsule tool isn’t used.
 
.. figure:: /images/UModeler_Capsule_OnThefloor.jpg
   :scale: 95 %

   Capsule on the floor.
   
.. figure:: /images/UModeler_Capsule_OnPolygon.jpg
   :scale: 95 %

   Capsule on the other polygon.