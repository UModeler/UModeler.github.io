########################
Stair Tool
########################

Creates stairs like you creates a box. The stair created with this tool has a uniform rise no matter how high the stair is.

Steps
--------
1. Select ``Stair Tool``
2. Draw a rectangle by dragging the mouse.
3. Release ``LMB`` and move the mouse up in a normal direction to raise the height.
4. Click ``LMB`` to stop raising.
5. If necessary, type the precise sizes in ``Width``, ``Depth``, ``Height`` and ``Rise`` fields in Properties or turn on or off ``Wide Steps`` or ``Reverse`` to change the stair’s direction
6. Press ``SPACE`` to complete or Press ``ESC`` to cancel.

Interface
------------
``LMB Drag``
 Starts and draws a bottom rectangle of a stair
 
``SPACE``
 Completes creating a stair
 
``ESC``
 Cancels creating a stair

Properties
---------------
Width
 The entire width of a stair
 
Depth
 The entire depth of a stair
 
Height
 The entire height of a stair.
 
Rise
 Distance between two neighbor treads.
 
Wide Step
 Rotates the stair by 90 degrees.
 
Reverse
 Reverses the front and back.
 
Border Check
 If this is enabled, the ray cast will run and it checks if the created stair is beyond the other polygons. It might cause a stop for a second at the beginning.
 
Glue
 The stair with this property enabled will be glued to the polygon where it started to be created. It means that the hidden part of the floor polygon by the created stair is removed.
 
.. figure:: /images/UModeler_StairTool.gif
   :scale: 95 %

   Stair Tool Demo
   
.. figure:: /images/UModeler_StairTool2.gif
   :scale: 95 %

   Stair Tool Demo - Constructing a stair on a mesh