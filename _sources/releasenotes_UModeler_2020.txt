############################
UModeler 2020
############################

 .. figure:: /images/Releasenote2020.png
 
Version 2.7.3 - March.6.2020
=======================================
Feature : Added a module to collect usability data using Google analyst.
Feature : Added focusing on selected elements pressing 'F' in UV Editor
Fix : Fix an issue where UV Editor camera isn't located at the center of the view, which causes unwrapped polygons with autolayout being out of the center of the view.
Fix : Fix a bug where edges in too small UModeler mesh aren't selected correctly.
Fix : Fix an issue where the Settings window is occluded by the global axis when the scene view is too narrow.
Fix : Allowed minus scale values in UV Tool so that up-side down UVs can be reset by pressing Reset UVs button.

Version 2.7.2 - Feb.25.2020
=======================================
- Fix : Fixed issues in font, size and position of Commentary box on Unity 2019.3 
- Fix : Added shortcuts of 3D cursor(SHIFT+A) and Settings(SHIFT+W). 
- Fix : Fixed a pivot of rotation and scale gizmos when 3D cursor is enabled. 
- Fix : Made unwrapped polygons' uvs not transformed in UV Tool. 
- Fix : Fixed an auto layout issue where a polygon is unwrapped with the same density as the adjacent one which has been already unwrapped. 
- Fix : Fixed an auto layout issue where the first unwrapped polygon is too big. Now it is re-scaled so that it is fit in the UV Editor view size.

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