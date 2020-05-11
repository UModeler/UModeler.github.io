.. |Icon_PrimitiveShapes_Box| image:: /images/Icon_PrimitiveShapes_Box.png
   :scale: 100 %
   
################################################
Box Tool |Icon_PrimitiveShapes_Box|
################################################

You can create a box with this tool on a plane. This tool allows you to make a box on any polygons as well as on the floor like other tools in the primitive shapes group. Therefore, you can make a simple level only with this.

Steps
-------------
1. Select ``Box Tool``
2. Draw a rectangle on a plane by dragging the mouse.
3. Release ``LMB`` and move the mouse up in a normal to raise the height.
4. Click ``LMB`` to stop raising.
5. If necessary, type the precise size in ``Width``, ``Depth`` and ``Height`` fields in Properties.
6. Press ``SPACE`` to complete or Press ``ESC`` to cancel.

Interface
-----------
``LMB Drag``
 Starts and draws a bottom rectangle of a box.
 
``SPACE``
 Completes creating a box.
 
``ESC``
 Cancels creating a box

Properties
---------------
Select Only Visible
 If on, the shape can be built on only a visible polygon. Namely backfaced or occluded polygons are excluded.
 
Floor Height
 The height of the floor where the primitive shape is built by LMB Dragging.

Width
 Width of a box
 
Depth
 Depth of a box
 
Height
 Height of a box
 
Border Check
 If on, the ray cast will run and it checks if the created box is beyond the opposite polygons. It might cause a stop for a second at the beginning.
 
Glue
 The box with this property enabled will be glued to the polygon where it started to be created. It means that the hidden part of the floor polygon by the created box is removed.
 
.. figure:: /images/UModeler_BoxTool_OnFloor.jpg
   :scale: 95 %

   A box on a floor.
   
.. figure:: /images/UModeler_BoxTool_OnPolygon.jpg
   :scale: 95 %

   A box on the other polygon.