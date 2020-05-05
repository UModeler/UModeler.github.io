############################
UModeler 2020
############################

 .. figure:: /images/Releasenote2020.png
 
Version 2.7.11 - May.5.2020
=====================================
- Fixed a freezing issue happening when UModeler object gets selected. 
- Fixed UModeler mesh disappearing with many error messages when entering the play mode. 
- Fixed a prefab issue happening in a untitled scene
 
Version 2.7.10 - April.27.2020
=====================================
- Feature : Added V Vertex Snapping
 
Version 2.7.9 - April.15.2020
===================================
- Fix : Fixed an issue where duplicated UModeler objects shared meshes 
- Fix : Fixed a material issue where new assigned  materials of UModeler prefab objects returned to the default ones.
- Fix : Fixed a bug where UModeler mesh disappeared when it is selected after Lightmap Static in Local Settings is toggled on/off  with multiple selected UModeler objects.
- Fix : Fixed an issue where X axis corresponded with Depth param and Y axis corresponded with Width param in Rectangle, Box, Room and Stair tools.
- Enhancement : Exposed an icon for UModelerizing on the toolbar in the scene view only when non-umodeler objects with mesh filters are selected.
- Enhancement : Added UModelerlize item to the GameObject menu and the popup menu in the hierarchy window.
 
Version 2.7.8 - April.7.2020
===================================
- Fix : Fixed an issue of UV Default parameters for UV Tool. 
- Fix : Fixed a bug where helper arrows and planes in Multiple PushPull and Mirror tool are affected by transform's scale and rotation 
- Fix : Fixed a bug where UModelerized meshes disappear when they are selected. 
- Change : Allows 3D cursor to be snapped to the center of edge and polygon by moving a gizmo holding LMB 
 
Version 2.7.7 - March.31.2020
=================================
- Enhancement : Added UV Tool default parameters to Preference. Shift, Rotation, Scale parameter in UV Tool are reset based on them.
- Enhancement : Added [Create Smoothing Groups as UModelerize]. If it is enabled, smoothing groups will be created when UModelerlizing.
- Fix : Wrong Settings windows location while Multiple Scene views are opened.
- Fix : Fixed an issue where a shape created with One-Click Build wasn't affected by World Grid Snap.
- Fix : Fixed a bug where a primitive shape object went away when undoing/redoing.

Version 2.7.6 - March.26.2020
=======================================
- Fix : Fixed a bug where object highlight is invisible after UModeler component is removed.
- Fix : Fixed UModeler mesh disappearing when multiple UModeler objects are deleted and undone and one of them are selected.
- Fix : Fixed an issue where the created UModeler object by redoing wasn't selected so more redoing didn't work.
- Fix : Fixed a bug where a mesh isn't rendered when a UModeler component is added to the empty game object and create some primitive shapes.
- Improvement : Warning message is displayed when Rotate and Scale gizmo are invisible because the 3D cursor is away from the current camera view. 

Version 2.7.5 - March.16.2020
======================================= 
- Feature : Added Auto layout tool to UV Editor to enable multiple selected polygons to be unwrap using Auto layout at once.
- Enhancement : Added "Select Only Visible" property to the 18 following tools.
- Drawing Group - Line, Arc, Rectangle, Disk, Side Stair, Parallel
- Primitive Shapes Group - Box, Room, Stair, Cylinder, Cone, Spiral Stair, Sphere, Capsule
- Add Group : PushPull, Inset, Clone
- Remove Group : Eraser
- Enhancement : Now while "Select Only Visible" property is on, backfaced polygons can't be selected.
- Enhancement : Refresh All button has been exposed in the toolbar.
- Fix : Fixed a bug where Unity gizmo disappeared when 3D cursor button is clicked.
- Fix : Fixed an issue where two cube cursors were displayed in Cylinder, Cone and Capsule Tools
- Fix : Fixed a bug where children objects were moved when the parent UModeler object pivot was changed.
- Fix : Fixed an issue where Polygon tool was forced to be selected after Settings icons were toggled. 
 
Version 2.7.4 - March.10.2020
=======================================
- Fix : Fixed an issue where the size of box overlay for selection representation changed abruptly when you move a mouse between the game view and the scene view on play mode. 
- Feature : Implemented Smoothing group generation when UModelerizing considering polygon's adjacency and normals.
 
Version 2.7.3 - March.6.2020
=======================================
- Feature : Added a module to collect usability data using Google analyst.
- Feature : Added focusing on selected elements pressing 'F' in UV Editor
- Fix : Fix an issue where UV Editor camera isn't located at the center of the view, which causes unwrapped polygons with autolayout being out of the center of the view.
- Fix : Fix a bug where edges in too small UModeler mesh aren't selected correctly.
- Fix : Fix an issue where the Settings window is occluded by the global axis when the scene view is too narrow.
- Fix : Allowed minus scale values in UV Tool so that up-side down UVs can be reset by pressing Reset UVs button.

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