################
Push/Pull Tools
################

Single PushPull Tool
=====================
	
Extrudes a polygon in a normal direction of it. You can push/pull any type of polygon, including circular, rectangular, and abstract polygons.

Properties
---------------

Height
 Precise height.

Border Check
 If this is enabled, the ray cast will run and it checks if the new created polygons while pushing or pulling will be beyond the other polygons. This can be used to cut a 3d shape, too..
 
Continuous
 Continuous  

------------------------------------------------------------------------------------------------------

Multi PushPull Tool
======================

Multiple polygons are pushed or pulled along a helper line

Properties
---------------

Distance
 How long the selected polygons are extruded

Pushpull Type
 * ``Individual`` : The selected polygons are extruded in each direction of the polygons.
 * ``Average Normal`` : The selected polygons are extruded in the average direction of them.
 * ``X`` : The selected polygons are extruded in X-axis direction.
 * ``Y`` : The selected polygons are extruded in Y-axis direction.
 * ``Z`` : The selected polygons are extruded in Z-axis direction.

Continuous
 Leaves edges of the extruded polygons at starting points after Push Pull