.. |Icon_Surface_PolygonColor| image:: /images/Icon_Surface_PolygonColor.png
   :scale: 100 %
   
############################################################
Polygon Color Tool |Icon_Surface_PolygonColor|
############################################################

Sets colors to the polygons. Pressing or Dragging ``LMB`` holding ``SHIFT`` will paint a polygon below the mouse cursor in the selected color.

.. note::

 | A material with a shader supporting Vertex Color should be set to assign colors with Material Tool. Recommended materials for assigning colors(VC - Vertex Color) are as follows.
 |  • UModelerPro_OnlyVC
 |  • UModelerBasic_OnlyVC
 
.. figure:: /images/UModeler_PolygonColorTool.jpg
   :scale: 100 % 

Steps
---------
1. Go to ``Polygon Color Tool``
2. Select polygons like you did in ``Polygon Tool`` if no polygon is selected.
3. Click ``LMB`` on a color in the color palette. If there isn't color you want, add a new color to the palette.

Interface
---------------
LMB
 Selects a polygon and pick a color of the color.
 
SHIFT + LMB
 Assigns the color in Color bar in Properties to a polygon where the mouse cursor point.
 
LMB Drag
 Selects several polygons in a rectangle.

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
 
.. figure:: /images/UModeler_PolygonColor.jpg
   :scale: 100 %
	
   Different colors at each face.