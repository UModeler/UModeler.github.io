*************
Transform
*************

 | There are 4 types of elements you can select and transform.
 |
 |  • UV - A point. Two edges meet at one UV.
 |  • Edge - Two connected UVs.
 |  • Polygon - A flat closed shape which consists of n-UVs and n-edges
 |  • Island - A set of polygons
 |
 | A way of selecting them is to click on each element or drag a mouse holding ``LMB`` to include elements in a rectangle. Holding ``CTRL`` enables you to select elements successively without canceling former selection.
 |
 | The element type is determined by what tool among UV, Edge, Polygon and Island on the inspector is chosen. 
 |
 
  .. figure:: /images/UVEditor_Transform.png
  
     Element types which can be chosen on the inspector.
	 
 | Once several elements are selected, they can be transformed using 4 sorts of gizmos.
 | Each gizmo can be switched by clicking on a corresponding button on the top toolbar or pressing ``W``, ``E``, ``R`` or ``T`` like you do in Unity.
 | If you drag an element, the element will follow the mouse cursor.
 |
 
  .. figure:: /images/UModeler_UVEditor_UV.gif
     :scale: 55 %
  
     Selecting and transfoming UVs
 
Pivot
=======
 | The default pivot position for rotating and scaling is the center of the selected elements. If you want to change the pivot location, use ``Cross Cursor``, which can be enabled in `Settings` on the inspector. The location of the ``Cross Cursor`` will be the pivot when you transform elements while it is visible on the working area.
 |

  .. figure:: /images/UModeler_UVEditor_UsingCrossCursor.gif
     :scale: 55 % 

     Using ``Cross Cursor`` while scaling and rotatin	

Snap
========
 | With ``Snap`` enabled you can move or rotate the selected elements by a specified unit. These ``Snap`` parameters can be set in ``Settings`` on the inspector.
 |
 
  .. figure:: /images/UModeler_UVEditor_Snapping.gif
     :scale: 55 % 

     Applying `Snap` to moving and rotating elements.
 
Separate Transfoming
=====================
 | Usually transforming polygons affects the adjacent polygons. It means that all Overlapped UVs will be transformed together. However holding ``SHIFT`` will make you transform elements separately. Even though several UVs occupied the same position, only one UV will be affected.
 
  .. figure:: /images/UModeler_UVEditor_NotHoldingShift.gif
     :scale: 55 % 

     Transfoming elements not holding ``SHIFT``
	 
  .. figure:: /images/UModeler_UVEditor_HoldingShift.gif
     :scale: 55 % 

     Transfoming elements holding ``SHIFT``
 
Overlapped Edge
=================
 | An edge in uv space can be overlapped the other edge in 3D space so it will be helpful to display the overlapped edges of the selected edges to make it easiser to edit UVs. Therefore The overlapped edges are displayed as green edges.
 
   .. figure:: /images/UModeler_UVEditor_SharedEdges.gif
     :scale: 55 % 

     Overlapped edges are represented in green.
 