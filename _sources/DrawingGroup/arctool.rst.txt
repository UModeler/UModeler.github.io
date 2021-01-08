.. |Icon_Drawing_Arc| image:: /images/Icon_Drawing_Arc.png
   :scale: 100 %
   
################################
Arc Tool |Icon_Drawing_Arc|
################################

Draws an arc by clicking twice on two points and dragging the mouse. The way of the cursor snapping and the change of it is same as how the line tool works. You can split or create a polygon as the line tool, or make just a curve.

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
Select Only Visible
 If on, the shape can be built on only a visible polygon. Namely backfaced or occluded polygons are excluded.
 
Floor Height
 The height of the floor where the primitive shape is built by LMB Dragging.
 
Segments
 How many edges an arc will have.

Close
 When Close property is enabled, the first and last vertices will be connected to create a closed form.
 
.. figure:: /images/UModeler_ArcTool_dividing.jpg
   :scale: 95 %

   Dividing a polygon into two.
   
.. figure:: /images/UModelr_ArcTool_SuccessiveArc.jpg
   :scale: 95 %
   
   Drawing another an edge beginning at the end of the drawn edge.

.. figure:: /images/UModeler_ArcTool_NewPolygon.jpg
   :scale: 95 %

   Creating a new polygon (``Close`` property is on)
