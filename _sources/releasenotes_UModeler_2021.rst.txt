############################
UModeler 2021
############################

Version 2.8.4 - May.10.2021
=================================
.. figure:: /images/blacksmith.png

- Assets : Includes ``Blacksmith`` demo pack.
- Enhancement : Added The Pixl snap to ``UV Editor``.
- Enhancement : V snap - If you drag the XYZ axis and snap to another point holding ``V`` key, only the dragged axis coordinate will be aligned with that point.
- Enhancement : Added ``Menu > Tools > UModeler > Export as .Obj`` menu. Using this menu, you can export UModeler objects to an OBJ file even when multiple objects are selected at once and an object without UModeler is selected.
- Fix : Fixed a bug where snaps were applied twice when moving edges or polygons in the world grid.
- Fix : Changed the grayscale icons not to be loaded when entering play mode.
- Fix : Changed the lightmap UV2 coordinates to be updated every time the umodeler is modified.
- Fix : The minimum values ​​of ``Width`` and ``Depth`` of the ``Rectangle Tool`` and the ``Box Tool`` have been changed from 0.01 to 0.001.
- Fix : Increased the overlay size of ``Vertex tool`` and ``Rectctangle Selection tool`` in ``UV Editor``.

Version 2.8.3f3 - April.30.2021
=================================

- Assets : Includes The Medieval Town : Vermilion demo pack.
- Assets : Includes The Urban Buildings demo pack to showcase Hotspot Texturing feature.
- Fix : Fixed the broken light map issue when LMB is clicked on a polygon in the Box Tool.
- Fix : Fixed ModelerHelper_Objects error message.
- Fix : Fixed UV disappearing in UV Editor when pushing or pulling a polygon.
- Enhancement : Assigned shortcuts to ``Hotspot Group`` toggle and ``Apply Selected Hotspot`` button.
- Enhancement : Added ``Hotspot Scale`` parameter in ``Hotspot Layout`` tool.

Version 2.8.3f2 - April.26.2021
=================================
.. figure:: /images/HotspotTexturing_UrbanBuildings.png

- Assets : Includes The Medieval Town : Vermilion demo pack.
- Assets : Includes The Urban Buildings demo pack to showcase Hotspot Texturing feature.
- Feature : Added the Hotspot Texturing.
- Fix : Fixed z-fighting issue of a face overlay in ISO mode.
- Fix : Fixed a bug where a duplicated polygon moves along with the original polygon when it's unwrapped and duplicated.
- Enhancement : Implemented Picking Vertex Color. Pick Color button has been added in the Vertex Color tool and the Polygon color tool.
- Enhancement : Modified the scale gizmo behaviour so that it is snapped to (0,0,0) and it can't have minus scale values.

Version 2.8.3 - April.12.2021
====================================
.. figure:: /images/Vermilion_screenshot.png

- Assets : Includes the Medieval town : Vermilion deom package.

Version 2.8.2f3 - March.29.2021
====================================
- Assets : Includes the Dreadnought: SF combat robot demo pack.
- Fix : Fixed V Snapping not working from Unity 2020.2 and newer versions.

Version 2.8.2f2 - March.19.2021
====================================
- Assets : Includes the Dreadnought: SF combat robot demo pack.
- Fix : Fixed the toolbar disappearing caused by the fix in 2.8.2f1

Version 2.8.2f1 - March.17.2021
==================================
- Assets : Includes the Dreadnought: SF combat robot demo pack.
- Fix : Fixed Null Reference Exception when ``Open`` button in the inspector is clicked.
- Fix : Fixed typos of tooltips etcs.
- Enhancement : Supported converting a quad-based mesh using ``UModelerize``.

Version 2.8.2 - March.3.2021
==================================
.. figure:: /images/dreadnought_image.png

- Assets : Includes the Dreadnought: SF combat robot demo pack.
- Enhancement : Supported collaborating with the Surforge asset.
- Fix : Fixed not being able to select vertices on the mirror plane in Mirror mode.

Version 2.8.1f3 - Feb.17.2021
==================================
- Assets : Includes the Turtle Ship demo pack.
- Enhancement : Added the Hand tool in UV Editor.
- Enhancement : Added Alt+RMB Move to Zoom in/out in UV Editor
- Fix : Fixed not being able to move 3D cursor using the move gizmo.
- Fix : Fixed overlapped polygons after UV unwrapping and using LoopSlice tool.
- Fix : Fixed Hand tool not working on the edit mode in the scene view.
- Fix : Fixed a bug where double click for loop selection didn't work when the cursor is on a gizmo.
- Fix : Fixed Select Only Visible not working on edges.

Version 2.8.1f1 - Feb.2.2021
==================================
- Assets : Includes the Turtle Ship demo pack.
- Fix : Fixed a bug where a object move using a move gizmo's arrow isn't correct in a rotated UModeler object.

Version 2.8.1 - Feb.1.2021
==================================
.. figure:: /images/TurtleShip.png

- Assets : Includes the Turtle Ship demo pack.
- Enhancement : The existing Move, Rotate and Scale gizmos have been replaced with the Unity Move, Rotate and Scale Handles.
- Enhancement : Length of every selected edge has been displayed when ``Local Overlay`` is on.
- Enhancement : Length of every edge consisting of the selected faces has been displayed when ``Local Overlay`` is on.
- Enhancement : ``Arc tool``'s overlay info has be upgraded.

Version 2.8.0f1 - Jan.14.2021
==================================
- Assets : Includes the ``Witch's Cauldron`` demo pack.
- Fix : Fixed ``Loop Selection`` bug where it didn't work on the cap polygon of beveled shape
- Fix : Fixed a Parallel tool bug where repeating the previous action by the ``LMB Double click`` made an incorrect parallel edge.
- Fix : Fixed a renaming issue of Polygon Group tool.    
- Improvement : Now the mesh .asset folder which you used recently is restored when you save your mesh as .asset

Version 2.8.0 - Jan.4.2021
==================================
.. figure:: /images/WitchCauldron.png

- Assets : Includes the ``Witch's Cauldron`` demo pack.
- Fix : Fixed UV disappearing bug as UModeler objects are duplicated 