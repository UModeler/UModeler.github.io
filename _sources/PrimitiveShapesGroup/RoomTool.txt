########################
Room Tool
########################
This is nearly same as the box tool except creating a flipped inner box.

Steps
-----------
1. Select ``Room`` tool
2. Draw a rectangle on where you want like you use ``Rectangle Tool`` by dragging the mouse.
3. Release ``LMB`` and move the mouse up in a normal direction to raise the height.
4. Click ``LMB`` to stop raising.
5. If necessary, type the precise size in ``Width``, ``Depth``, ``Height`` or ``Thickness`` fields in Properties.
6. Press ``SPACE`` to complete or Press ``ESC`` to cancel.

Interface
-----------
``LMB Drag``
 Starts and draws a bottom rectangle of a room.
 
``SPACE``
 Completes creating a room.
 
``ESC``
 Cancels creating a room.

Properties
---------------
Width
 Width of a room

Depth
 Depth of a room

Heigh
 Height of a room

Thickness
 The distance between outer box and inner flipped box.

Border Check
 If this is enabled, the ray cast will run and it checks if the created room is beyond the other polygons. It might cause a stop for a second at the beginning.
 
Glue
 The room with this property enabled will be glued to the polygon where it started to be created. It means that the hidden part of the floor polygon by the created room is removed.
 
.. figure:: /images/UModeler_RoomTool.gif
   :scale: 95 %

   Room Tool Demo