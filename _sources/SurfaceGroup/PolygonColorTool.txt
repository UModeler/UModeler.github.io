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

Steps
---------
1. Go to ``Polygon Color Tool``
2. Select polygons like you did in ``Polygon Tool`` if no polygon is selected.
3. Click ``LMB`` on Color bar in Properties
4. Choose a color which you want. 

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
 Selects only visible vertices/edges/polygons from a camera. Occluded elements from other polygons will not be selected. This is available only when the game object has MeshCollider component.

Color
 Color which will be assigned to the selected polygons.
 
Select Polygons
 Selects polygons with the color in ``Color`` property.
 
.. figure:: /images/UModeler_PolygonColor.jpg
   :scale: 100 %
	
   Different colors at each face.