.. |Icon_Add_Bridge| image:: /images/Icon_Add_Bridge.png
   :scale: 100 %

.. |Icon_Add_BridgeVertices| image:: /images/Icon_Add_BridgeVertices.png
   :scale: 100 %

.. |Icon_Add_BridgeEdges| image:: /images/Icon_Add_BridgeEdges.png
   :scale: 100 %

.. |Icon_Add_BridgePolygons| image:: /images/Icon_Add_BridgePolygons.png
   :scale: 100 %   
   
########################################################################################
Bridge Tool |Icon_Add_BridgeVertices| |Icon_Add_BridgeEdges| |Icon_Add_BridgePolygons|
########################################################################################

Fills space surrounded by the selected elements. The selection conditions to apply Bridge are as follows.

 - More than three vertices are selected.
 - Two unconnected edges are selected.
 - More than two connected edges are selected.
 - More than two polygons are selected.
   
Steps
---------
1. Select vertices/edges/polygons using ``VertexTool``, ``EdgeTool`` or ``PolygonTool``.
2. Select Bridge tool.
   
.. |Vertices_0| image:: /images/UModeler_Bridge_Vertices_0.jpg
   :scale: 95 %
   
.. |Vertices_1| image:: /images/UModeler_Bridge_Vertices_1.jpg
   :scale: 95 %   

|Vertices_0| |Vertices_1|   
   Select vertices. The order of selecting them is important. Click on the ``Bridge Vertices Tool`` (|Icon_Add_BridgeVertices|) button to create a polygon from the vertices.   
   
.. |Edges_0| image:: /images/UModeler_Bridge_Edges_0.jpg
   :scale: 95 %
   
.. |Edges_1| image:: /images/UModeler_Bridge_Edges_1.jpg
   :scale: 95 %   

|Edges_0| |Edges_1|
   Select two edges which are apart from each other and go to ``Bridge Edges Tool`` (|Icon_Add_BridgeEdges|).
   
.. |HoleEdges_0| image:: /images/UModeler_Bridge_HoleEdges_0.jpg
   :scale: 95 %
   
.. |HoleEdges_1| image:: /images/UModeler_Bridge_HoleEdges_1.jpg
   :scale: 95 %      

|HoleEdges_0| |HoleEdges_1|
   The linked selected edges will create a polygon with ``Bridge Edges Tool`` (|Icon_Add_BridgeEdges|).
   
.. |Polygons_0| image:: /images/UModeler_Bridge_Polygons_0.jpg
   :scale: 95 %
   
.. |Polygons_1| image:: /images/UModeler_Bridge_Polygons_1.jpg
   :scale: 95 %   

|Polygons_0| |Polygons_1|
   In case that Several polygons are selected ``Bridge Polygons Tool`` (|Icon_Add_BridgePolygons|) makes polygons between edges of them.