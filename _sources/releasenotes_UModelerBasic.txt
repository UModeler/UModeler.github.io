############################
UModeler Basic
############################

.. Note::

   | Deprecated so it's not available anymore as of 05/24/2017

1.0.6
-----------------------------------------
 - Fix - Preferece for key setting : Wrong positions of UIs in Preference for setting up keys on Unity 5.6
 - Fix - Transform tool : Flickering gizmos in Vertex/Edge/Polygon tools when more 2 views are open.
 - Fix - Display : Incorrect vertex cubes' size bug.
 - Fix - Gizmo : A bug about getting a gizmo locked when UModeler object exits.
 - Improvement - Transform Tool : Made the way of changing gizmo same as the way of Unity. The gizmo can be switched to another by clicking on the cursor icons as well as pressing W,E and R.
 
 .. figure:: /images/UModeler_Basic_Gizmo_Switch.gif
 
1.0.5
-----------------------------------------
 - Fix - Export tool : Fixed x-axis flipped coordinates bug as exporting to .OBJ file.

1.0.4
-----------------------------------------
 - Fixed obj exporter to avoid duplicated vertices
 - Push/Pull - DrawMargins property should be renamed to DrawEdges
 
1.0.3
-----------------------------------------
 - Fixed a bug about not visible gizmo when the other object get selected from the modeler object on the Hierarchy window.
 - Added .prefab export.
 - Fixed a bug in .obj exporter so that material information will be exported well.

1.0.2
-----------------------------------------
 - FreezeXForm tool has been added. 
 - Export to obj tool has been added.
 - Fixed a camera rotation bug by Alt+LMB Drag