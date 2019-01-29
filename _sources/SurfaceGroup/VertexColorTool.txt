.. |Icon_Surface_VertexColor| image:: /images/Icon_Surface_VertexColor.png
   :scale: 100 %
   
######################################################
Vertex Color Tool |Icon_Surface_VertexColor|
######################################################

Sets colors to the Vertices. Pressing or Dragging ``LMB`` holding ``SHIFT`` will paint a polygon below the mouse cursor in the selected color.

.. note::

 | A material with a shader supporting Vertex Color should be set to assign colors with Material Tool. Recommended materials for assigning colors(VC - Vertex Color) are as follows.
 |  • UModelerPro_OnlyVC
 |  • UModelerBasic_OnlyVC

Steps - 1
----------
1. Go to ``Vertex Color Tool``
2. Select Vertices like you did in ``Vertex Tool`` if no vertex is selected.
3. Click ``LMB`` on Color bar in Properties
4. Choose a color which you want. 

Steps - 2
----------
1. Go to ``Vertex Color Tool``
2. Drag a mouse holding ``SHIFT``

Interface
---------------
``LMB``
 Selects a vertex and pick a color of the color.
 
``Shift``
 Makes the sphere brush visible.
 
``SHIFT + LMB``
 Assigns the color in Color bar in Properties to vertices within the sphere brush. 
 
``SHIFT + Scroll Wheel``
 Increases the size of the brush.
 
``LMB Drag``
 Selects several vertices in a rectangle.

Properties
---------------
Select Only Visible
 If on, Selects only visible vertices/edges/polygons from a camera. Occluded elements from other polygons will not be selected. This is available only when the game object has MeshCollider component.

Color
 Color which will be assigned to the selected vertices.

Brush Radius
 The sphere brush radius
 
Select Vertices
 Selects vertices with the color in ``Color`` property.
 
.. figure:: /images/UModeler_VertexColor.jpg
   :scale: 100 %
   
   Blue at the top and Oragne at the bottom