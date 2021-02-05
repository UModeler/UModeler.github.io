.. |Icon_Add_LoopSlice| image:: /images/Icon_Add_LoopSlice.png
   :scale: 100 %
   
###################################################
Loop Slice Tool |Icon_Add_LoopSlice|
###################################################


``Loop Slice`` splits a loop of faces by inserting new edge loops intersecting the chosen edge.
   
Steps
-------------
1. Select ``Loop SliceTool``.
2. Move the cursor over a desired edge
3. Scroll ``Wheel`` of the mouse to increase or decrease the number of edge loops.
4. Drag the mouse to changes the offset of the edge loops.
5. Release ``LMB`` to finish.

Interface
-------------   
``LMB Drag``
 Moves the edge loops.
 
``Scroll Wheel``
 Increases  or decreases the number of edge loop.

``Ctrl + Wheel``
 Adjusts the ``Pinch``

Moving the mouse holding ``CTRL``
 Keeps the current loop. The loop shape does not change when the mouse cursor moves close to another edge.

Properties
---------------

Split Number
 The number of the edge loop. (``LMB Drag``)

Pinch
 Anchors the center of the entire loop and moves the loop in both ends. (``CTRL + Wheel``)

Offset
 Moves the entire loop in a direction perpendicular to the loop. (``LMB Drag``)

.. note::

 ``Pinch`` and ``Offset`` properties aren't available in the Lite version.
 
.. figure:: /images/UModeler_LoopSlice_0.jpg
   :scale: 95 %

   When the cursor gets close to a long edge, a preview of a edge loop across the cylinder will be displayed.
   
.. figure:: /images/UModeler_LoopSlice_1.jpg
   :scale: 95 %

   Increases the number of the edge loop by rolling up the wheel.

.. figure:: /images/UModeler_LoopSlice_2.jpg
   :scale: 95 %

   The mouse drag moves the edge loops up and down and the cylinder cuts after releasing the mouse.

.. figure:: /images/LoopSlice_Pinch.gif

   Pinch changes by ``Ctrl + Whell``.