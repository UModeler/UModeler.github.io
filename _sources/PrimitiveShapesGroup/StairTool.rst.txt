.. |Icon_PrimitiveShapes_Stair| image:: /images/Icon_PrimitiveShapes_Stair.png
   :scale: 100 %

################################################
Stair Tool |Icon_PrimitiveShapes_Stair|
################################################

Creates stairs like you create a box. The stair created with this tool has a uniform rise no matter how high the stair is.

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
Select Only Visible
 If on, the shape can be built on only a visible polygon. Namely backfaced or occluded polygons are excluded.
 
Floor Height
 The height of the floor where the primitive shape is built by LMB Dragging.
 
Width
 The entire width of a stair
 
Depth
 The entire depth of a stair
 
Height
 The entire height of a stair.
 
Rise
 Distance between two neighbor treads.

Rotate by 90°
 Rotates the stair preview. This property replaced ``Wide Step`` and ``Reverse`` properties with.

.. note::

 ``Wide Step`` and ``Reverse`` properties are replaced with ``Rotate by 90° property`` since UModeler 2.9.1. 
 
Glue
 The stair with this property enabled will be glued to the polygon where it started to be created. It means that the hidden part of the floor polygon by the created stair is removed.
 
.. figure:: /images/UModeler_StairTool.jpg
   :scale: 95 %

   A Stair created on the floor.