.. |Icon_Add_Bevel| image:: /images/Icon_Add_Bevel.png
   :scale: 100 %

############################
Bevel Tool |Icon_Add_Bevel|
############################

The bevel tool allows you to create chamfered or rounded corners to geometry. A bevel is an effect that smooths out edges and corners.

Vertices, Edges or Polygons have to be selected before selecting ``BevelTool`` and then change the properties described below in the inspector.
   
Steps
--------
1. Select Vertex(s), edge(s) or polygon(s) with ``VertexTool``, ``EdgeTool``, or ``PolygonTool``.
2. Adjust ``Width``, ``Segments`` or ``Profile`` value in Properties.

Properties
---------------

Width
 The width of the bevel polygon.

Segments
 The number of segments. The greater the number of segments, the smoother the bevel.

Profile
 The side view of the bevel edge. This is between 0 and 1. 0.5 is completely flat.
 Values less than 0.5 gives concave bevel and values more than 0.5 gives convex bevel.

Clamp Overlap
 When selected, the bevel amount isn’t allowed to go larger than an amount that causes overlapping collisions with other geometry.

Auto Smooth
 Applies smoothing groups to new beveled faces.
 
.. |VertexBevel_0| image:: /images/UModeler_Bevel_VertexBevel_0.jpg
   :scale: 95 %
   
.. |VertexBevel_1| image:: /images/UModeler_Bevel_VertexBevel_1.jpg
   :scale: 95 %   

|VertexBevel_0| |VertexBevel_1| 
   Vertex Beveling.
   
.. |EdgeBevel_0| image:: /images/UModeler_Bevel_EdgeBevel_0.jpg
   :scale: 95 %
   
.. |EdgeBevel_1| image:: /images/UModeler_Bevel_EdgeBevel_1.jpg
   :scale: 95 %

|EdgeBevel_0| |EdgeBevel_1|   
   Edge Beveling

   
.. |PolygonBevel_0| image:: /images/UModeler_Bevel_PolygonBevel_0.jpg
   :scale: 95 %

.. |PolygonBevel_1| image:: /images/UModeler_Bevel_PolygonBevel_1.jpg
   :scale: 95 %

|PolygonBevel_0| |PolygonBevel_1|   
   Polygon Beveling