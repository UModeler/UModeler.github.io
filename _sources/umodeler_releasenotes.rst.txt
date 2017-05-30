%%%%%%%%%%%%%%%%%%%%
Release Notes
%%%%%%%%%%%%%%%%%%%%

You can get UModeler `here <https://www.assetstore.unity3d.com/#!/content/80868>`__

1.0.6 
======================================

 Please read `this document <https://docs.google.com/document/d/1C_M8YwejCqEgie0QEt1s147jvfXKwL7cyApMXWn7bWs/edit?usp=sharing>`__ before upgrading to 1.0.5 or 1.0.6

 ## Tweak
 
 - Added Readme button to the About Dialog box.

1.0.5 (05/24/2017)
======================================

 .. figure:: /images/UModeler_1.0.5_ScreenShot.png

 ## Improvements & Features

 - Improved the About dialog box.
 - Added a button for object mode to the inspector
 - Added two buttons for creating new object and new collider object to the UModeler inspector
 - Added painting polygons in a material ID by holding SHIFT + LMB drag in Material tool
 - Added painting polygons in a color by holding SHIFT + LMB drag in Material tool.
 - Added Input viewer next to Status box to the scene view.
 - Improved the way of displaying and setting materials in Material tool

 ## Fixes & Tweaks

 - Fixed getting slow and unresponsive happening after a UModeler prefab is loaded, the GUI gets slow and unresponsive
 - Scaled up and straightened up the status text on scene view
 - Made Vertices/Edges/Polygons selected when LMB is up after dragging to avoid a lag.
 - Made a system child object called __Modeler_Specific__ invisible.
 - Made selection of several polygons by CTRL + LMB drag in Material tool.
 - Fixed a bug about getting gizmos hided when multiple UModeler objects are selected
 - Hided mesh filter component and materials in the inspector
 - Pro has been left out so that UModeler Pro became just UModeler.
 - Excluded UModeler component in game build
 - Enabled to get shortcut input possible in the inspector.
 - Removed Resources folder and moved all data there to UModeler folder reorganizing the folder structure.

1.0.4 (05/02/2017)
======================================
 - Fix - Preferece for key setting : Wrong positions of UIs in Preference for setting up keys on Unity 5.6
 - Fix - Transform tool : Flickering gizmos in Vertex/Edge/Polygon tools when more 2 views are open.
 - Fix - Display : Incorrect vertex cubes' size bug.
 - Fix - Combine Tool : A bug about not working the merge of co-planar polygons.
 - Fix - Gizmo : A bug about getting a gizmo locked when UModeler object exits.
 - Improvement - Transform Tool : Made the way of changing gizmo same as the way of Unity. The gizmo can be switched to another by clicking on the cursor icons as well as pressing W,E and R.
 
 .. figure:: /images/UModeler_Gizmo_Switch.gif
 
 - Improvement - Rectangle Tool : Added Corner Segment property in Rectangle tool to enable to change how many edges are placed in a rounded corner.
 
 .. figure:: /images/UModeler_Rectangle_Corner_Length_Segment.gif

1.0.3 (04/26/2017)
======================================
 - Feature - Combine Tool : Added "Combine Vertex" button in the inspector to enable to merge vertices without leaving Combine tool. 
 
 .. figure:: /images/UModeler_CombineTool_EditMode.gif
 
 - Feature - Arc Tool : Added "Close" property to enable to create a closed shape. 
 
 .. figure:: /images/UModeler_Arc_Close_property.gif
 
 - Feature - Rectangle Tool : Added "Corner Length" property to support rounded corners.
 
 .. figure:: /images/UModeler_Rectangle_rounded_corner.gif
 
 - Fix - Export tool : Fixed x-axis flipped coordinates bug as exporting to .OBJ file.

1.0.2 (04/19/2017)
======================================
 - Obj Exporter has been fixed so that duplicated positions, uv coordinates and normals are handled.
 - Remove Doubles Tool - The default value of the Distance property has been changed from 0.0001 to 1.0.
 - Push/Pull tool - DrawMargins property has been renamed to DrawEdges.
 - ShearTool has been renamed to CutTool.

1.0.1 (04/11/2017)
======================================
 - Fixed a bug about the 3D cursor, which didn’t work as having the selected elements rotated or scaled around 3D cursor.
 - Added .prefab export.
 - Fixed a bug in .obj exporter so that material information will be exported well.
 - Windows Material has been changed so that Standard shadow is used.
 - Assigned the window material used in the building in Demo.unity to the window, where a proper texture wasn’t assigned, in the modern building
 - Fixed a bug about not visible gizmo when the other object get selected from the modeler object on the Hierarchy window.
 - Fixed “Convert from Mesh” bug so that a mesh with several materials can be converted to UModeler object well.