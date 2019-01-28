.. |Icon_Drawing_Line| image:: /images/Icon_Drawing_Line.png
   :scale: 100 %
   
################################
Line Tool |Icon_Drawing_Line|
################################

You can draw edges on a surface or on a floor in a row to sketch or cut out a polygon

Steps
-------
1. Select ``Line Tool`` under Drawing Group.
2. Click ``LMB`` on where you want to start to draw.
3. Click ``LMB`` to place another point to draw an edge.
4. You can draw successive edges by putting points until pressing ``SPACE``.
5. If you want to go back to the previous point, Press ``ESC``.

.. tip::

 When you move the cursor, you'll notice that it will be snapped and its color will change according to where it is. 
 
 * At an edge - ``green``
 * The center of an edge - ``yellow``
 * At a vertex - ``orange``
 * At the starting point - ``sky blue``
 * When aligned with one of x,y,z of a drawn vertex - ``pink``
 * Parallel with of the global axes - ``blue``

Interface
------------
``LMB``
 Places a point
 
``SPACE``
 Confirms the drawn edges.
 
``ESC``
 Cancels the previous point.
 
.. figure:: /images/UModeler_LineTool_CreatingPolygon.jpg
   :scale: 95 %

   When you  place several points and click on the first point, the new polygon will be created. If you do this on the existing polygon, it'll make a hole and generate a polygon inside the hole. If you move the cursor close to the first point, its color will change to sky blue.
   
.. figure:: /images/UModeler_LineTool_DividingPolygon.jpg
   :scale: 95 %

   If drawing a line starts on an edge in a polygon and it will end at the same edge or the other edge in the same polygon, this will split the polygon into two.