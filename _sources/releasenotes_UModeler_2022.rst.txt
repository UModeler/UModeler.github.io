############################
UModeler 2022
############################

Version 2.9.25 | Dec.30.2022
==================================
- Fixed an issue where a child asset object of a prefab was removed when the prefab mode was closed.
- Fixed a bug where components were removed when UModelerizing.

Version 2.9.24 | Dec.27.2022
==================================
- Fixed an error which occurred in TPUModelerEditor.UModelerEditorInitializer.OnSceneLoaded()
- Fixed an issue where a vertex selection by LMB clicking didn't work in the Hotspot Layout Editor. 

Version 2.9.23 | Dec.19.2022
=================================
- Supports the basic materials for URP and HDRP by default. You don't need to convert them in URP or HDRP project anymore.

Version 2.9.22 | Dec.2.2022
=================================
- Fixed an issue where the prefab editor is paused when the prefab UModeler object has children.
- Fixed an issue where drawing a line using the Line tool doesn't work on the bent quad polygon to cut it out.

Version 2.9.21 | Nov.24.2022
=================================
- Fixed a Mirror Object Tool issue where the original mesh disappears when Duplicate and Mirror runs.

Version 2.9.20 | Nov.14.2022
===================================
- Giveaway the New 3D asset called Riverwalk City made for URP.

Version 2.9.19 | Nov.11.2022
===================================
- Fixed an issue where the original material changed to UModeler material after UModelerizing.
- Added Remove UModeler and Remove UModeler Hierarchically in the menu to remove UModeler components of the selected game objects.
- Creates UModeler as Byte Stream Data option in the Preference has been remove because it isn't supported anymore.

Version 2.9.18-2 hotfix | October.20.2022
=============================================
- Fixed a bug where NullReferenceException error occurs when non-UModeler object is selected in the hierarchy window

Version 2.9.18-1 hotfix | October.18.2022
==============================================
- Fixed an issue where "mainRenderableMesh is null" message was displayed in the console when UModelerize tool is used.

Version 2.9.18 | October.17.2022
=======================================
- Prefab workflow : UModeler's prefab workflow has be improved a a lot in this update. Now UModeler prefab instance can be edited only in the Prefab Editor. Please read `this document`_ before updating UModeler.
- PushPull tool : Fixed an issue where the polygons disappear when you started to push or pull a polygon.

.. _this document: https://tripolygon.notion.site/The-Improvement-of-the-Prefab-workflow-in-UModeler-2-9-18-7b654e55da934db190396e3e9c21aeab 

Version 2.9.17-1 | September.08.2022
=======================================
- Fixed a mirror tool issue where the undo/redo actions while using mirror tool caused some broken mesh.

Version 2.9.17 | September.08.2022
=======================================
- Fixed an issue where some error messages regarding EditableMeshCache occurred after hot-reloading due to the Pastel Town asset which is the built-in 3d package of UModeler.

Version 2.9.16 | September.02.2022
====================================
- Fixed an issue where the buttons for saving as .asset in Meshfilter were not displayed when both UModeler and UModeler lite were installed.
- Added some slide bars in the Preference to adjust fade in/out tmee and duration of commentary box and texts in the Preference.
- Fixed a PushPull tool issue where pulling a polygon to the opposite polygon caused some errors.

Version 2.9.15 | August.19.2022
====================================
- Fixed an issue where the smoothing group isn't applied when UModeler object is exported as .obj

Version 2.9.14 | August.11.2022
====================================
- Fixed an issue where the UModeler Lite object wasn't converted to UModeler object using UModelerize
- Fixed an issue where the Scene dirty flag was enabled when UModeler object was selected.
- Fixed an issue where element selection between UV Editor and Scene view wasn't synced.
- Fixed an issue where the Cancel tool in UVEditor to cancel unwrapping didn't work.
- Fixed an issue where Auto Smooth property in Sphere and Capsule tools etc didn't work.
- Fixed a bug where a box disappeared while it was created due to an error.

Version 2.9.13 | August.1.2022
====================================
- Bevel Tool : Fixed an issue where some polygons disappeared which missed in the previous update when the bevel tool splitted multiple edges in nearly straight more edges.
- The new asset called Pixel Farm 3D made with UModeler is included. 

Version 2.9.12 | July.30.2022
====================================
- Bevel Tool : Fixed an issue where the bevel tool didn't work at a vertex connecting with 4 edges.
- Bevel Tool : Fixed an issue where side polygons disappear while the bevel tool running.
- The new asset called Pixel Farm 3D made with UModeler is included.

Version 2.9.11 | July.27.2022
====================================
- The new asset called Pixel Farm 3D made with UModeler is included.
- Fixed the Boolean tool issue where the resulting object disappeared.

Version 2.9.10 | July.25.2022
====================================
- Improved the performance of UModelerize by about 40 times so that any meshes even with smoothing groups can be converted to UModeler mesh immediately.
- Improved the way of drawing wireframe to increase the drawing speed and not to be affected by the postprocess.
- Improved the performance of mesh editing so that at least the meshes in the synty studio's asset packages can be edited comfortably.

Version 2.9.9 | July.15.2022
===================================
- Fixed a bug where an edge polygon was created when two vertices were connected by pressing "SPACE"

Version 2.9.8 | July.14.2022
======================================
- Fixed massive error messages recurred while the mouse cursor was moving as Seamless Editor mode is "All" or "Group"

Version 2.9.7 | July.13.2022
======================================
- Fixed an issue where some edge polygons were left after removing edges by using the Eraser tool or pressing 'Del' key.

Version 2.9.6 | July.09.2022
======================================
- Fixed some buggy behaviours related to vertex/edge/polygon movement.
- Added ``Reset all settings`` in the menu.
- Fixed the aspect ratio issue of UV Editor and Hotspot layer Editor.
- Fixed a bug where an edge polygon is created when two edges are connected by pressing ``SPACE``
- Fixed a bug where an narrow polygons are created when using Inset tool.

Version 2.9.4 | June.29.2022
======================================
- Added the Subdivide tool in Add group. This enables you to subdivide selected polygons.
- Fixed an issue regarding the orange outline.
- Fixed an issue where the large icons' size was same as the small icons' size when the menu window was floating.

Version 2.9.3 | June.10.2022
======================================
- Added a new feature to export and import whole settings of UModeler such as Preference, Tool properties, Settings, UV Editor Settings etc.

Version 2.9.2 | May.31.2022
======================================
- Fixed an issue where selection Outline was disabled when UModeler object got selected.
- Hotspot Layout : Added a new property called Hotspot Priority to map a triangle polygon   to a more precise triangle layout.

Version 2.9.1 | May.23.2022
=======================================
- UV Editor : Fixed the Setting window issue of the UV Editor where the bottom item wasn't visible wholly.
- Boolean Tool : Fixed an Boolean tool error occuring when two meshes with lots of polygons are operated using the Boolean operation.
- Vertex/Edge/Polygon Tools : Fixed an issue regarding Generate UVs property in Element tools.
- Polygon Tool : Fixed a bug where Snap to Polygon doesn't work when a polygon gets close to another polygon.
- Capsule Tool : Fixed an issue where Auto Smoothing property didn't work in the Capsule tool.
- Hotspot Texturing : Fixed an issue of Hotspot texturing to make Scale property work better for a triangle.
- Stair Tool : Replaced Wide Step and Reverse properties with Rotate by 90° button.


Version 2.9.0 | April.11.2022
=======================================
- NEW FEATURE : Remastered Menu Icon Mode. The Reshaped Icons and The Large Ion Mode.
- Fix : Fixed a crash bug recurring when undoing after detaching polygons with the Detach tool
- Fix : Fixed a crash bug recurring when undoing a cut operation that detaches the object.

Version 2.8.21 | March.31.2022
=======================================

- Fix : Fixed a NullReferenceException error occuring when a polygon is rotated and it is triangulated.

Version 2.8.20 | March.23.2022
=======================================

- Fix : Fixed an issue where multiple vertices weren't removed using Eraser Tool.
- Fix : Fixed an issue where the following error message recurred in Unity 2022.1. MissingMethodException: Method not found: void UnityEditor.Unwrapping.GenerateSecondaryUVSet

Version 2.8.19 | March.14.2022
=======================================

- Improvement : Added a new function to disable cursor magnet(snap) by holding CTRL.
- Fix : Fixed an edge duplication issue happening as using the Duplicate tool.

Version 2.8.18 | March.10.2022
========================================

- Improvement : Made Loop Selection tool more perfect.
- Fix : Fixed an issue where Mesh Collider component is toggled on and off automatically.

Version 2.8.17 | Feb.25.2022
=======================================

- Fix : Fixed a bug where UV polygons are strecthed as unwrapped using the Autolayout.
- Fix : Fixed a bug of Mirror Object tool where vertices can't be selected after running Duplicate and Mirror

Version 2.8.16 | Feb.17.2022
=======================================

- Fix : Fixed a bug whose error message is "Unable to add Renderer to the Scene after Culling" in a project with the AQUAS asset.

Version 2.8.15 | Feb.14.2022
=======================================

- Fix : Fixed a bug where the current tool changed to the Object Tool as an element was selected. 

Version 2.8.14 | Feb.7.2022
=======================================

- Fix : Fixed a bug where creating a primitive shape didn't work on another UModeler object.

Version 2.8.13 | Feb.7.2022
=======================================

- Enhancement : Forces the current tool to be the object tool when selected. This can be enabled in the Preference window.
- Enhancement : Rotates the global gizmo by the transform. This can be enabled in the Preference window.
- Fix : Fixed the issue of ``Isolation Selection Tool`` where overlapped faces not connected were selected.

.. figure:: /images/Preference_EnablesTheObjectTool_RotatesTheGlobalGizmo.png
    :scale: 70 %

Version 2.8.12 | Jan.24.2022
=======================================

- Fix : Fixed a warning regarding non-secure network connections in Unity 2022.1b

Version 2.8.11f3 | Jan.19.2022
=======================================

- Fix : Fixed an error occuring when exiting the prefab mode.
- Fix : Fixed another issue where edited parts disappear while modifying and appear again at the end of editing intermittently when both the scene view and the game view are opened.

Version 2.8.11f2 | Jan.18.2022
=====================================

- Asset : Includes the PastelTown-BuiltInRP-UModeler package by default.
- Fix : Fixed a TryGetComponent() issue in Unity 2019.1 or less.
- Fix : Fixed an issue where edited parts continue to appear and disappear while modifying

Version 2.8.11 | Jan.18.2022
=====================================

- Asset : Includes the PastelTown-BuiltInRP-UModeler package by default.
- Fix : Fixed an issue where changes are displayed on all copies while editing any of the copies when objects are duplicated.
- Optimization : Enhanced the performance by stopping unnecessary memory allocation which happened when UModeler objects were selected.

Version 2.8.10f3 | Jan.3.2022
=====================================

- Asset : Includes the Moonglow Village Demo Package for 2.8.10 users.
- Fix : Fixed a crash error when undoing creating UModeler object in Unity 2021.2.1 and higher versions.
- Fix : Fixed a warning issue regarding "Serialization depth limit 10 exceeded" caused by the codes of Mirror Cancel Function which was implemented in 2.8.10. The cancel function of the mirror tool has been reverted so it won't be available for now till we'll find a solution.
- Fix : Fixed a .obj exporer bug where the multiple materials in the exported UModeler object couldn't be imported in Unity. 
