*************
Unwrap
*************
Begin by selecting all polygons to be unwrapped in the 3D view. With our polyons selected, it is now time to unwrap them. In the UVEditor inspector, select ``Unwrap > Plane/View`` or ``Unwrap > Cube`` and click on ``Unwrap`` button.

Common Properties
==================
Separate All
   If on, each polygon will be a UV island. If not, each connected polygon group will be a UV Island.
Padding
   Turn on padding.
Padding Size
   The space between UV Islands.
Unwrap
   Unwrap the selected polygon in 3D Scene view.
  
Plane/View Projection
========================
``Plane/View`` mapping projects a mesh in a selected direction below.

Properties
-----------
Axis
   Select which axis is used for projection.
   
   Normal
      The normal direction of the connected polygons.
   View
      Camera viewing direction.
   X
	  X-Axis
   Y
      Y-Axis
   Z
      Z-Axis

.. figure:: /images/UModeler_UVEditor_PlaneViewProjection.gif
     :scale: 55 %
  
     Unwrapping the selected polygons in the ``View`` direction and ``Normal`` direction.

Cube Projection
=================
``Cube`` mapping projects a mesh onto six separate planes, creating six UV islands. 

  .. figure:: /images/UModeler_UVEditor_CubeProjection.gif
     :scale: 55 %
  
     Unfolding the selected polygons using ``Cube`` unwrapping adjusting the properties.

Cancel
========
``Cancel`` will remove the selected polygons from UV Islands and the UVs of them will be reset to have UVs created automatically.
