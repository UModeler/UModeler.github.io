########################
Primitive Shapes Tools
########################

.. tip::

 1. Pressing ``SPACE`` confirms the current action. On the other hand ``ESC`` cancels it.
 2. You can adjust a shape by chaning the properties before confirming.
 3. The mouse cursor will be snapped to a vertex, a center of edge, a center of polygon etc when the cursor gets close enough to them.

Box Tool
===================

You can create a box with this tool on a plane.

Steps
-------------
1. Select ``Box`` tool
2. Draw a rectangle on a plane by dragging the mouse.
3. Release ``LMB`` and move the mouse up in a normal to raise the height.
4. Click ``LMB`` to stop raising.
5. If necessary, type the precise size in ``Width``, ``Depth`` and Height fields in Properties.
6. Press ``SPACE`` to complete or Press ``ESC`` to cancel.

Interface
-----------
``LMB Drag``
 Starts and draws a bottom rectangle of a b/ox.
 
``SPACE``
 Completes creating a box.
 
``ESC``
 Cancels creating a box

Properties
---------------
Width
 Width of a box
 
Depth
 Depth of a box
 
Heigh
 Height of a box
 
Border Test
 If on, the ray cast will run and it checks if the created box is beyond the opposite polygons.
 
Glue
 The box with this property enabled will be glued to the polygon where it started to be created. It means that the hidden part of the floor polygon by the created box is removed.

------------------------------------------------------------------------------------------------------

Room Tool
===================
This is nearly same as the box tool except creating a flipped inner box.

Steps
-----------
1. Select ``Room` tool
2. Draw a rectangle on where you want like you use ``Rectangle`` tool by dragging the mouse.
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

Border Test
 If this is enabled, the ray cast will run and it checks if the created room is beyond the other polygons.
 
Glue
 The room with this property enabled will be glued to the polygon where it started to be created. It means that the hidden part of the floor polygon by the created room is removed.

------------------------------------------------------------------------------------------------------

Stair Tool
===================

Creates stairs like you creates a box. The stair created with this tool has a uniform rise no matter how high the stair is.

Steps
--------
1. Select ``Stair`` tool
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
 Distance between two treads.
 
Wide Step
 Rotates the stair by 90 degrees.
 
Reverse
 Reverses the front and back.
 
Border Test
 If this is enabled, the ray cast will run and it checks if the created stair is beyond the other polygons.
 
Glue
 The stair with this property enabled will be glued to the polygon where it started to be created. It means that the hidden part of the floor polygon by the created stair is removed.

------------------------------------------------------------------------------------------------------

Cylinder Tool
===================
Creates a cylinder

Steps
----------
1. Select ``Cylinder`` tool
2. Drag the mouse to draw a disk.
3. Release ``LMB`` and move the mouse cursor in a normal direction to raise the height.
4. Click ``LMB`` to stop rasing.
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

Border Test
 If this is enabled, the ray cast will run and it checks if the created cylinder is beyond the other polygons.
 
Glue
 The cylinder with this property enabled will be glued to the polygon where it started to be created. It means that the hidden part of the floor polygon by the created cylinder is removed.


------------------------------------------------------------------------------------------------------

Cone Tool
===================

Creates a cone

Steps
------
1. Select ``Cone`` tool
2. Drag the mouse to draw a disk.
3. Release ``LMB`` and move the mouse cursor in a normal direction to raise the height.
4. Click ``LMB`` to stop rasing.
5. Type the count of edges in ``Segment`` field, radius in ``Radius`` field and height in ``Height`` field if necessary.
6. Press ``SPACE`` to complete or Press ``ESC`` to cancel.

Interface
-------------
``LMB Drag``
 Draws a disk.
 
``SPACE``
 Completes creating a cone
 
``ESC``
Cancels creating a cone.

Properties
---------------
Segment
 The count of side faces

Radius
 A radius of a cone

Height
 A height of a cone

Angle Snap
 When you drag the mouse with this property on, the disk’s direction will snap to every 90 degree.

Border Test
 If this is enabled, the ray cast will run and it checks if the created cone is beyond the other polygons.

Glue
 The cone with this property enabled will be glued to the polygon where it started to be created. It means that the hidden part of the floor polygon by the created cone is removed.

------------------------------------------------------------------------------------------------------

Sphere Tool
===================
Creates a sphere

Steps
--------
1. Enter ``Sphere`` tool
2. Drag the mouse holding ``LMB`` to define a radius. The sphere will be created from the center of the bottom.
4. You can type more precise values of ``Segment`` and ``Radius`` if necessary.
5. Press ``SPACE`` to complete or Press ``ESC`` to cancel.

Interface
--------------
LMB Drag
 Creates a sphere
 
SPACE
 Completes
 
ESC
 Cancels

Properties
---------------
Segment
 How many the sphere will be divided

Radius
 A radius of the sphere

Angle Snap
 When you drag the mouse with this property on, the sphere’s forward direction will snap to every 90 degree time.

------------------------------------------------------------------------------------------------------

Capsule Tool
===================

Creates a capsule

Steps
------------
1. Select ``Capsule`` tool
2. Drag the mouse to draw a disk.
3. Release ``LMB`` and move the mouse in a normal direction to raise up a capsule.
4. Click ``LMB`` to stop.
5. Type the count of edges in ``Segment`` field, radius in ``Radius`` field and height in ``Height`` field if necessary.
6. Press ``SPACE`` to complete or Press ``ESC`` to cancel.

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

Border Test
 If this is enabled, the ray cast will run and it checks if the created capsule is beyond the other polygons.

Glue
 This property in Capsule tool isn’t used.