############
Bevel Tool
############

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
 
.. figure:: /images/UModeler_BevelTool.gif
   :scale: 95 %

   Bevel Tool Demo. 