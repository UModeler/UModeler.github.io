############
Clone Tool
############

.. figure:: /images/Icon_Add_Clone.png
   :scale: 100 %
   
   ``Clone Tool`` icon  

Clones the selected polygons along the line drawn by dragging a mouse. Pressing ``SPACE`` confirms the clone action and ``ESC`` cancels it.
   
Steps - Single Clone
---------------------
1. Enter Clone tool.
2. Point at a polygon you want to clone by putting the mouse over it if polygons are not selected when this tool is activated. 
3. Drag the mouse to draw a line. You can make sure that the cloned polygons will be aligned with the line.
4. Adjust ``Number``, ``Distance`` and ``Arrangement`` in ``Properties`` if necessary.
5. Press ``SPACE`` or click on ``Confirm`` button to confirm, or Press ``ESC`` or click on ``Cancel`` button to cancel.

Steps - Multi Clone
---------------------
1. Select Several polygons using ``Polygon Tool``
2. Enter Clone tool.
3. Drag the mouse to draw a line. You can make sure that the cloned polygons will be aligned with the line.
4. Adjust ``Number``, ``Distance`` and ``Arrangement`` in ``Properties`` if necessary.
5. Press ``SPACE`` or click on ``Confirm`` button to confirm, or Press ``ESC`` or click on ``Cancel`` button to cancel.

Interface
---------------
``LMB Drag``
 Draws an edge where the clones will be placed.   

Properties
---------------

Number
 The number of clones

Distance
 The distance of an edge where the clones will be placed.

Arrangement
 * ``Divide`` - Creates clones arranged evenly between the starting point and the end point of the edge.
 * ``Multiply`` - Makes clones along the edge. The distance between the clones is the value of Distance property in Properties.
 
.. |Clone_0|  image:: /images/UModeler_Clone_0.jpg
   :scale: 95 %
   
.. |Clone_1|  image:: /images/UModeler_Clone_1.jpg
   :scale: 95 %

.. |Clone_2|  image:: /images/UModeler_Clone_2.jpg
   :scale: 95 %
   
.. |Clone_3|  image:: /images/UModeler_Clone_3.jpg
   :scale: 95 %

.. |Clone_4|  image:: /images/UModeler_Clone_4.jpg
   :scale: 95 %
   
|Clone_0| ``Arrangement`` property is ``Divide``


|Clone_1| ``Arrangement`` property is ``Multiply``


|Clone_2| This is the result of the upper cases.

|Clone_3| |Clone_4|
   ``Multi Polygons Clone``
