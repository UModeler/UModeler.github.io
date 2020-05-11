.. |Icon_PrimitiveShapes_SpiralStair| image:: /images/Icon_PrimitiveShapes_SpiralStair.png
   :scale: 100 %  

########################################################################
Spiral Stair Tool |Icon_PrimitiveShapes_SpiralStair|
########################################################################
   
Creates a Spiral Stair.

Steps
------
1. Select ``Spiral Stair Tool``
2. Drag the mouse on a floor or an another polygon as if you make a cylinder.
3. Release ``LMB`` and move the mouse cursor in a normal direction to raise the height. You can change the direction of the stair by pressing ``SPACE``. 
4. Click ``LMB`` to stop raising.
5. Type the properties in inepector to adjust the shape of the stair.
6. Press ``SPACE`` to complete or Press ``ESC`` to cancel.

Interface
-------------
``LMB Drag``
 Starts to create a spiral stair.
 
``SPACE``
 Change the direction of the stair or Completes creating a spiral stair
 
``ESC``
 Cancels creating a spiral stair.

Properties
---------------
Select Only Visible
 If on, the shape can be built on only a visible polygon. Namely backfaced or occluded polygons are excluded.
 
Floor Height
 The height of the floor where the primitive shape is built by LMB Dragging.
 
Width
 The step width.

Height
 The height of the stair

Radius
 The inner radius of the stair. The whole radius of the stair from the center will be ``Radius`` + ``Width``.

Curvature
 How curved the stair is.

Mirror
 Reflects the stair.

Glue
 The spiral stair with this property enabled will be glued to the polygon where it started to be created. It means that the hidden part of the floor polygon by the created stair is removed.
 
Angle Snap
 When you drag the mouse with this property on, the direction of the spiral stair will snap to every 90 degree.
 
.. figure:: /images/UModeler_SpiralStair_0.jpg
   :scale: 95 %

   Spiral Stair created on the floor. Its curvature is 270 degrees.
   
.. figure:: /images/UModeler_SpiralStair_1.jpg
   :scale: 95 %

   Reduces ``Width`` property and Increases ``Radius``. Its curvature is 180 degrees.