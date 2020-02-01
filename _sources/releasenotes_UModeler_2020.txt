############################
UModeler 2020
############################

Version 2.7.1.2 - Jan.30.2020
=======================================
- Fix : Fixed an issue where Transform properties in the inspector have different looks from the original ones.

Version 2.7.1.1 - Jan.29.2020
=======================================
- Fix : Fixed an issue related to upside down material UVs.

Version 2.7.1 - Jan.28.2020
=======================================
- Enhancement : Allowed minus thickness of Room tool
- Enhancement : Allowed Flip Tool in Object mode, which enables flipping all polygons at once.
- Enhancement : Added Increment Snap. Now None, World Grid Snap and Increment Snap are available.
- Fix : Fixed an issue that a Prefab icon in the project window would change quickly
- Fix : Fixed an issue regarding editing UModeler in Prefab mode 
- Fix : UV reset bug when vertex/edge/polygons being transformed by adding [Reset UVs] property. 
- Fix : Fixed a bug where UModeler prefab instance would disappear when a prefab is placed in a level by dragging.
- Fix : Fixed an issue where child UModeler objects would get invisible when its parent prefab is instanced.
- Fix : Made a mesh collider up to date whenever UModeler mesh changes.

Version 2.7.0 - Jan.7.2020
=============================
- Fix : Fixed InvalidCastException in TPUModelerEditor.BaseTool.Properties[T]
- Fix : Fixed bug where a material assigned by dragging gets back to the previous one when entering play mode.
- Fix : Fixed bug where .obj file exported from UModeler has floating number with commas for separating decimals in Russian locale.
- Enhancement : Enabled Grid snap to be done along each X, Y, Z.
- Enhancement : Improved Autolayout so that the current double-clicked polygon can be stitched next to the just previous selected polygon.