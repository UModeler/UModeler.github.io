################
Arc Tool
################

Draws an arc by placing three points on a plane.

Steps
-------
1. Select ``Arc Tool``
2. Click on where you want to start to draw an arc
3. Drag the mouse to set the second point.
4. Release ``LMB`` and move the mouse cursor to set the third point of the arc.
5. If necessary, adjust ``Segment`` property in the inspector.
6. Press ``SPACE`` to complete drawing the arc or if you want to cancel the arc, press ``ESC``.

Interface
------------
``LMB Drag``
 Sets the first and second points.

``SPACE``
 Completes drawing an arc.
 
``ESC``
 Cancels drawing an arc.


Properties
------------
Segment
 How many edges an arc will have.

Close
 When Close property is enabled, the first and last vertices will be connected to create a closed form.
 
.. figure:: /images/UModeler_ArcTool.gif
   :scale: 95 %

   Arc Tool Demo