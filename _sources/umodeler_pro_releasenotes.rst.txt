%%%%%%%%%%%%%%%%%%%%
Release Notes (Pro)
%%%%%%%%%%%%%%%%%%%%

You can get UModeler Pro `here <https://www.assetstore.unity3d.com/#!/content/80868>`__

1.0.4 (Due on 05/05/2017)
======================================
 - Fix - Preferece for key setting : Wrong positions of UIs in Preference for setting up keys on Unity 5.6
 - Fix - Transform tool : Flickering gizmos in Vertex/Edge/Polygon tools when more 2 views are open.
 - Fix - Display : Incorrect vertex cubes' size bug.
 - Fix - Combine Tool : A bug about not working the merge of co-planar polygons.
 - Improvement - Transform Tool : Makes the way of changing gizmo same as the way of Unity.
 - Improvement - Rectangle Tool : Adds Corner Segment property in Rectangle tool to enable to change how many edges are placed in a rounded corner.

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