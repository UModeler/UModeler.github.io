.. |Icon_UVEditor_Unwrap_CubeUnwrap| image:: /images/Icon_UVEditor_Unwrap_CubeUnwrap.png
   :scale: 100 %

****************************************************
Cube Unwrap Tool |Icon_UVEditor_Unwrap_CubeUnwrap|
****************************************************

Begin by selecting all polygons to be unwrapped in the 3D view. With our polyons selected, it is now time to unwrap them. In the UVEditor inspector, select ``Unwrap > Cube`` and click on ``Unwrap`` button.
``Cube`` mapping projects a mesh onto six separate planes, creating six UV islands. 
	 
Properties
-----------
Margin
   Margin size

Spacing
   The space between UV Islands.

Keep Size
   If true, UV size is propotional to the size of the selected polygon. If false, UV sizes of the selected polygons when being unwrapped are identical.   

Separate All
   If on, each polygon will be a UV island. If not, each connected polygon group will be a UV Island.   
	  
Unwrap
   Unwrap the selected polygon in 3D Scene view.
   
.. figure:: /images/UModeler_UVEditor_CubeUnwrap.jpg
     :scale: 30 %
  
     Unfolding polygons consisting of a sphere using ``Cube Unwrap Tool``
