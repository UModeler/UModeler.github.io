#########################
Grow Selection Tool
#########################

.. _Grow Selection Tool:

Expands the current selection outwards in all directions from the current selected elements.

.. |Icon_Selection_IncreaseSelectVertex| image:: /images/Icon_Selection_IncreaseSelectVertex.png
   :scale: 100 %

.. |Icon_Selection_IncreaseSelectEdge| image:: /images/Icon_Selection_IncreaseSelectEdge.png
   :scale: 100 %
   
.. |Icon_Selection_IncreaseSelectPolygon| image:: /images/Icon_Selection_IncreaseSelectPolygon.png
   :scale: 100 %
   
Vertex Grow Selection |Icon_Selection_IncreaseSelectVertex|
---------------------------------------------------------------------------------------------
   
.. figure:: /images/UModeler_IncreaseTool_Vertex.gif
   :scale: 95 %   


Edge Grow Selection |Icon_Selection_IncreaseSelectEdge|
---------------------------------------------------------------------------------------------
   
.. figure:: /images/UModeler_Increase_edge.gif
   :scale: 100 %
   
   ``Edge Grow Tool`` icon

Polygon Grow Selection |Icon_Selection_IncreaseSelectPolygon|
---------------------------------------------------------------------------------------------
   
.. figure:: /images/UModeler_IncreaseTool.gif
   :scale: 100 %
   
   ``Polygon Grow Tool`` icon

Steps
--------
1. Select vertices, edges or polygons.
2. Select ``Grow Tool``.

Properties in Settings
-------------------------
.. figure:: /images/GrowSelectSettings.png
   :scale: 80 %
   
   Grow Selection properties in Settings window.

Restrict To Angle
 Enables this property to grow the selection only to those faces within a specified angle.
   
Max Angle
 Sets the maximum angle allowed when growing the selection. UModeler ignores this property unless the Restrict to Angle property is enabled.
   
Iterative
 Enables this property to iterative the selection one adjacent element at a time, each time you press the Grow Selection button.

 .. figure:: /images/GrowSelection_RestrictToAngle.gif
    :scale: 30 %
 
    Grow Selection where ``Restrict To Angle`` is applied

 .. figure:: /images/GrowSelection_NoIterative.gif
     :scale: 30 %
 
     Grow Selection where ``Iterative`` is off