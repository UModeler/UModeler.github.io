########################
Box Tool
########################

You can create a box with this tool on a plane.

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
 
.. figure:: /images/UModeler_BoxTool.gif
   :scale: 95 %

   Box Tool Demo - Basic and ``Width``, ``Depth``, ``Height`` and ``Border Check`` properties
   
.. figure:: /images/UModeler_BoxTool2.gif
   :scale: 95 %

   Box Tool Demo - ``Glue`` property and enabled `Snap`