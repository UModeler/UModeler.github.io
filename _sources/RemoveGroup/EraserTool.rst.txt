.. |Icon_Remove_Eraser| image:: /images/Icon_Remove_Eraser.png
   :scale: 100 %
   
#############################################
Eraser Tool |Icon_Remove_Eraser|
#############################################

There are two modes of deleting elements. One is ``Immediate Mode`` and the other is ``Edit Mode``.

 * ``Immediate Mode`` - Select elements at first and then click on ``Eraser`` button to remove them.
 * ``Edit Mode`` - Select ``Eraser Tool`` first with no selected elements and then click on an edge which you want to remove.
 
When you try to erase an edge shared by two coplanar polygons, only the edge will be removed and the two shared polygons will be merged. Otherwise, the two polygons will be removed, too.

In a case of a vertex, all the polygons sharing the vertex will be removed. If it is a polygon, only the polygon will be taken away.

.. |UModeler_Eraser_0| image:: /images/UModeler_Eraser_0.jpg
   :scale: 100 %

.. |UModeler_Eraser_1| image:: /images/UModeler_Eraser_1.jpg
   :scale: 100 %

.. |UModeler_Eraser_2| image:: /images/UModeler_Eraser_2.jpg
   :scale: 100 %

.. |UModeler_Eraser_3| image:: /images/UModeler_Eraser_3.jpg
   :scale: 100 %
   
|UModeler_Eraser_0| |UModeler_Eraser_1|
    ``Immediate Mode`` - Click on ``Eraser`` button after selecting several elements.

|UModeler_Eraser_2| |UModeler_Eraser_3|
    ``Edit Mode`` - At fist enter ``Eraser Tool`` and then click on an edge.


.. figure:: /images/UModeler_EdgeEraserToolImprovement.gif

 As of UModeler 2.7.25, the ability to erase shared edges of two adjacent triangles that are not on the same plane has been added. The usage is the same as how to erase the existing edge.