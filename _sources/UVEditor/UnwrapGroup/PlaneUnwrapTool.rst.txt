.. |Icon_UVEditor_Unwrap_PlaneViewUnwrap| image:: /images/Icon_UVEditor_Unwrap_PlaneViewUnwrap.png
   :scale: 100 %
   
******************************************************************************
Plane/View Unwrap Tool |Icon_UVEditor_Unwrap_PlaneViewUnwrap|
******************************************************************************

``Plane/View`` mapping projects a mesh in a selected direction below.

Begin by selecting all polygons to be unwrapped in the 3D view. With our polyons selected, it is now time to unwrap them. In the UVEditor inspector, select ``Unwrap > Plane/View`` and click on ``Unwrap`` button.

Properties
-----------
Margin
   Margin size

Spacing
   The space between UV Islands.

Separate All
   If on, each polygon will be a UV island. If not, each connected polygon group will be a UV Island. 

Keep Size
   If true, UV size is propotional to the size of the selected polygon. If false, UV sizes of the selected polygons when being unwrapped are identical.

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
	  
Unwrap
   Unwrap the selected polygon in 3D Scene view.	  

.. figure:: /images/UModeler_UVEditor_Unwrap_MarginSpacing.jpg
  
     ``Margin`` and ``Spacing``
	 
.. figure:: /images/UModeler_UVEditor_PlaneUnwrap_1.jpg
  
     Connected polygons become one UV island.