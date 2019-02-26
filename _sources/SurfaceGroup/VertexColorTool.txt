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
 
.. figure:: /images/UModeler_VertexColorTool.jpg
   :scale: 100 %   
   
Steps - 1
----------
1. Go to ``Vertex Color Tool``
2. Select Vertices like you did in ``Vertex Tool`` if no vertex is selected.
3. Click ``LMB`` on a color in the color palette. If there isn't color you want, add a new color to the palette.

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
 Assigns the selected color in the color palette to vertices within the sphere brush. 
 
``SHIFT + Scroll Wheel``
 Increases the size of the brush.
 
``LMB Drag``
 Selects several vertices in a rectangle.
 
Properties
---------------
Select Only Visible
 If on, Selects only visible vertices/edges/polygons from a camera. Occluded elements from other polygons will not be selected. This is available only when the game object has MeshCollider component.

Brush Radius
 The sphere brush radius

Color Palette
 Colors you can use for painting.

.. tip::

 `Color Palette`
 
 You can keep frequently used colors in the color palette which is used in both ``Vertex Color Tool`` and ``Polygon Color Tool``. The color palette is stored in the registry.
 
 .. figure:: /images/ColorPalette.jpg
   :scale: 100 % 
   
 1) Color number
 2) Removes the color
 3) Chooses a color
 4) Adds a new color
 
Select Vertices
 Selects vertices with the selected color in the color palette.
 
Paint Vertices
 Paints vertices with the selected color in the color palette.
 
.. figure:: /images/UModeler_VertexColor.jpg
   :scale: 100 %
   
   Blue at the top and Oragne at the bottom