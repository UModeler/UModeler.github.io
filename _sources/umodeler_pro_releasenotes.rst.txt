%%%%%%%%%%%%%%%%%%%%
Release Notes (Pro)
%%%%%%%%%%%%%%%%%%%%

1.0.2 (Due on 04/20/2017)
======================================
 - Obj Exporter has been fixed fixed so that duplicated vertices, edges and polygons are avoided.
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