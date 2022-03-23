############################
UModeler 2021-2022
############################

Version 2.8.20 - March.23.2022
=======================================

- Fix : Fixed an issue where removing multiple vertices weren't removed using Eraser Tool.
- Fix : Fixed an issue where the following error message recurred in Unity 2022.1.
   MissingMethodException: Method not found: void UnityEditor.Unwrapping.GenerateSecondaryUVSet

Version 2.8.19 - March.14.2022
=======================================

- Improvement : Added a new function to disable cursor magnet(snap) by holding CTRL.
- Fix : Fixed an edge duplication issue happening as using the Duplicate tool.

Version 2.8.18 - March.10.2022
========================================

- Improvement : Made Loop Selection tool more perfect.
- Fix : Fixed an issue where Mesh Collider component is toggled on and off automatically.

Version 2.8.17 - Feb.25.2022
=======================================

- Fix : Fixed a bug where UV polygons are strecthed as unwrapped using the Autolayout.
- Fix : Fixed a bug of Mirror Object tool where vertices can't be selected after running Duplicate and Mirror

Version 2.8.16 - Feb.17.2022
=======================================

- Fix : Fixed a bug whose error message is "Unable to add Renderer to the Scene after Culling" in a project with the AQUAS asset.

Version 2.8.15 - Feb.14.2022
=======================================

- Fix : Fixed a bug where the current tool changed to the Object Tool as an element was selected. 

Version 2.8.14 - Feb.7.2022
=======================================

- Fix : Fixed a bug where creating a primitive shape didn't work on another UModeler object.

Version 2.8.13 - Feb.7.2022
=======================================

- Enhancement : Forces the current tool to be the object tool when selected. This can be enabled in the Preference window.
- Enhancement : Rotates the global gizmo by the transform. This can be enabled in the Preference window.
- Fix : Fixed the issue of ``Isolation Selection Tool`` where overlapped faces not connected were selected.

.. figure:: /images/Preference_EnablesTheObjectTool_RotatesTheGlobalGizmo.png
    :scale: 70 %

Version 2.8.12 - Jan.24.2022
=======================================

- Fix : Fixed a warning regarding non-secure network connections in Unity 2022.1b

Version 2.8.11f3 - Jan.19.2022
=======================================

- Fix : Fixed an error occuring when exiting the prefab mode.
- Fix : Fixed another issue where edited parts disappear while modifying and appear again at the end of editing intermittently when both the scene view and the game view are opened.

Version 2.8.11f2 - Jan.18.2022
=====================================

- Asset : Includes the PastelTown-BuiltInRP-UModeler package by default.
- Fix : Fixed a TryGetComponent() issue in Unity 2019.1 or less.
- Fix : Fixed an issue where edited parts continue to appear and disappear while modifying

Version 2.8.11 - Jan.18.2022
=====================================

- Asset : Includes the PastelTown-BuiltInRP-UModeler package by default.
- Fix : Fixed an issue where changes are displayed on all copies while editing any of the copies when objects are duplicated.
- Optimization : Enhanced the performance by stopping unnecessary memory allocation which happened when UModeler objects were selected.

Version 2.8.10f3 - Jan.3.2022
=====================================

- Asset : Includes the Moonglow Village Demo Package for 2.8.10 users.
- Fix : Fixed a crash error when undoing creating UModeler object in Unity 2021.2.1 and higher versions.
- Fix : Fixed a warning issue regarding "Serialization depth limit 10 exceeded" caused by the codes of Mirror Cancel Function which was implemented in 2.8.10. The cancel function of the mirror tool has been reverted so it won't be available for now till we'll find a solution.
- Fix : Fixed a .obj exporer bug where the multiple materials in the exported UModeler object couldn't be imported in Unity. 

Version 2.8.10f2 - December.14.2021
========================================

- Asset : Includes the Moonglow Village Demo Package for 2.8.10 users.
- Fix : Fixed an issue where the several same online document windows pop up when the mouse is over a text menu item in UV Editor.

Version 2.8.10 - December.13.2021
========================================

.. figure:: /images/moonglow_village_thumbnail.png
    :scale: 50 %

- Asset : Includes the Moonglow Village Demo Package for 2.8.10 users.
- Fix : Fixed an issue of ``Flatten`` tool where unnecessary Edit mode was enabled.
- Fix : Fixed a null exception error occurring as UV unwrapping tools like ``Plane``, ``Cube`` etc are executed when no object is selected.
- Fix : Fixed an issue where ``Shift+LMB`` clicking the ``UV Editor`` that is already selected didn't work to open in its documentation page.
- Fix : Fixed an issue where a highlighted edge was obscured.
- Fix : Fixed the Seamless Edit mode issue where Closed UModeler object and disabled UModeler object were selected.
- Fix : Fixed a crash issue which occurred as being undone after being cut using the ``Cut`` tool.
- Fix : Fixed a smart snap issue where  the cursor wasn't snapped well to the closest a vertex or an edge in a large UModeler object.
- Tweak : Added a new toggle in the Preference window called ``Disable popping up the About window`` to disable opening up the About window as UModeler is updated.
- Tweak : Changed ``Angle`` property name to ``Angle Along Y Axis`` in the ``Mirror`` tool.
- Enhancement : Added a new feature to select another UModeler object by LMB holding CTRL+Shift in Edit mode.
- Enhancement : Added a new button called ``Select by Selected Polygons`` to select a smoothing group which includes the selected polygon.
- Enhancement : Added a new button named ``Cancel`` in ``Mirror`` tool to revert changes that are made in Mirror mode.
- Enhancement : Added a new button named ``Auto Smoothing`` in ``Cylinder``, ``Cone``, ``Spiral Stair``, ``Sphere`` and ``Capsule`` tools to create smoothed surfaces.

Version 2.8.9f3 - December.7.2021
========================================

- Asset : Includes the Basilica Cathedral Package for 2.8.9 users.
- Fix : Fixed an error where UModelerEditor.dll isn't loaded in Unity 2021.2.5

Version 2.8.9f2 - November.29.2021
===================================

- Asset : Includes the Basilica Cathedral Package for 2.8.9 users.
- Fix : Fixed constant GUI errors which were thrown while in the Hotspot Layout Editor in Unity 2021.2
- Fix : Fixed a bug where Hotspot Scriptable object doesn't get saved and is reset after each Unity Editor in Unity 2021.2

Version 2.8.9 - November.14.2021
===================================

.. figure:: /images/Basilica_Cathedral_Scenes.jpg
    :scale: 50 %

- Asset : Includes the Basilica Cathedral Package for 2.8.9 users.

Version 2.8.8f8 - November.5.2021
====================================

- Asset : Includes the Medieval Weapons Package - Bow and Magic wands plus Swords and Shields for 2.8.8 users.
- Asset : Includes Hamster Knight character pack for 2.8.8 users
- Fix : Fixed GUI error in the UVEditor on Unity 2021.2.0f1.

Version 2.8.8f7 - November.4.2021

- Asset : Includes the Medieval Weapons Package - Bow and Magic wands plus Swords and Shields for 2.8.8 users.
- Asset : Includes Hamster Knight character pack for 2.8.8 users
- Enhancement : Added a hotkey to toggle on and off UV Editor. ``Ctrl + Shift + U``.
- Enhancement : Added a hotkey to toggle on and off floating the Menu and Property Windows. ``Ctrl + Shift + 8``.
- Enhancement : Added a hotkey for ``Auto Smooth``. ``Ctrl + Shift + 6``.
- Enhancement : Added a hotkey for ``Remove All`` in ``Smoothing Group Tool``. ``Ctrl + Shift + 9``.

Version 2.8.8f6 - November.1.2021
====================================

- Asset : Includes the Medieval Weapons Package - Bow and Magic wands plus Swords and Shields for 2.8.8 users.
- Asset : Includes Hamster Knight character pack for 2.8.8 users
- Enhancement : Added ''Auto Smoothing'' property in ``Bevel Tool``
- Fix : Fixed a bug where the Scale gizmo axis isn't aligned with the Object's rotation.
- Enhancement : Added a snapping function to snap the straight cut plane straightly in ``Cut Tool``.
- Enhancement : Added a new function to separate an half part to another game object in ``Cut Tool``. 

Version 2.8.8 - October.13.2021
====================================

.. figure:: /images/UModeler2.8.8Update.png
    :scale: 25 %

- Asset : Includes the Medieval Weapons Package - Bow and Magic wands plus Swords and Shields for 2.8.8 users.
- Asset : Includes Hamster Knight character pack for 2.8.8 users
- Enhancement : Added the Center Snap function in ``Parallel Tool``
- Enhancement : Added ``Remove UModeler`` menu to remove UModeler components of the selected objects.
- Enhancement : Added ``Copy Materials`` and ``Paste Materials`` buttons in ``Material tool`` to allow you to copy materials and paste them in other UModeler object.
- Enhancement : Added ``Keep Size`` property in ``Plane Unwrap Tool`` and ``Cube Unwrap Tool``  of the UV Editor to unwrap a polygon whose size is proportional to its size. 
- Enhancement : Implemented transferring element selection when ``Vertex Tool``, ``Edge Tool`` and ``Polygon Tool`` being selected to keep selection.

Version 2.8.7f2 - September.13.2021
====================================
- Asset : Includes the Medieval Weapons - Swords and Shields Pack for 2.8.7 users.
- Asset : Includes Hamster Knight character pack for 2.8.7 users
- Fix : Fixed a bug where ``Invisible in Playmode`` in ``Local Settings tool`` toggle removes any secondary materials from the object and causes ``Submesh Index Out of Bounds`` errors.
- Fix : Fixed a ``Material Tool`` issue where it is possible to remove all material slots, which then throws ArgumentOutOfRangeExceptions and breaks the Inspector window if the GameObject is de-selected and re-selected
- Fix : Fixed an issue where the gizmos' size of ``UV Editor`` is too large and not adpative according to the UV editor size. 
- Fix : Fixed a stack overflow issue where a mesh object is umodelerized using ``UModelerize Hierarchically``.
- Fix : Fixed an issue where Shift was displayed in view commentary in ``Extrusion mode`` even when the extrude modifier key changed to Caps Lock in the Preference.
- Fix : Fixed a ``Multi-PushPull Tool`` bug where Selecting ``One Step Pull`` without an active polygon selected throws NullReferenceExceptions
- Fix : Fixed a ``Mirror Object Tool`` bug where MissingReferenceExceptions are thrown when repainting the scene view(moving the mouse around) after undoing a Mirror Object action
- Fix : Fixed a ``Clone Tool`` bug where Dragging on a polygon with the left mouse button only slightly and then clicking on an empty space in the Scene view throws an unhandled NullReferenceException
- Fix : Fixed a ``Clip Tool`` bug where Unhandled NullReferenceException in certain scenarios
- Fix : Fixed a ``Polygon Group Tool`` bug where Remove Polygons button without a polygon selected throws a NullReferenceException
- Fix : Fixed a bug where Shift+LMB on the selected menu button doesn't work to bringing up a online manual.
- Fix : Fixed a ``Grow Select Tool`` bug of UV editor where Unhandled NullReferenceException is thrown when attempting to grow selection on a single face in the ``UV Editor``
- Fix : Fixed a ``Export Tool`` bug of ``UV Editor`` where warnings about releasing render texture that is set to be RenderTexture.active are thrown upon exporting
- Fix : Fixed shortcut crash of ``Arc Tool`` and ``Duplicate Tool`` - Arc Tool shortcut changed to ``Ctrl+Shift+Q``. Duplicate Tool shortcut changed to ``Ctrl+Shift+D``.

Version 2.8.7 - September.7.2021
===================================
.. figure:: /images/UModeler2.8.7.png
    :scale: 50 %

- Asset : Includes the Medieval Weapons - Swords and Shields Pack for 2.8.7 users.
- Asset : Includes Hamster Knight character pack for 2.8.7 users
- Fix : Fixed a bug where the default thickness value was -0.01 in Room tool
- Fix : Fixed a bug where Status window and Cursor window aren't visible in Unity 2021.2. The windows have changed to Unity editor windows.

Version 2.8.6f3 - August.24.2021
====================================
- Asset : Includes Hamster Knight character pack for 2.8.6 users
- Asset : Includes the Ancient Dungeon demo pack for 2.8.5 and 2.8.6 users
- Fix : Fixed a bug where ProBuidler 5.0.3 mesh isn't converted.

Version 2.8.6f2 - August.17.2021
====================================
- Asset : Includes Hamster Knight character pack for 2.8.6 users
- Asset : Includes the Ancient Dungeon demo pack for 2.8.5 and 2.8.6 users
- Fix : Fixed Scale gizmo's tip not being picked in UV Editor.
- Fix : Fixed elements not being selected using Rect selection while overlays are docked in Unity 2021.2
- Enhancement : Added a shortcut to toggle on and off the Edit mode which can also be toggled on and off Open and Close buttons in the inspector. The default shortcut is ``Ctrl + Shift + Number 0``

Version 2.8.6f1 - August.8.2021
================================
- Asset : Includes Hamster Knight character pack for 2.8.6 users
- Asset : Includes the Ancient Dungeon demo pack for 2.8.5 and 2.8.6 users
- Fix : Fixed broken UVs caused by padding property in the Hotspot Layout tool.
- Fix : Fixed cutting line not being aligned with the cursor in Cut tool
- Fix : Fixed incorrect UVs as texture's width and height is different. 
- Enhancement : Added ``Toolbar Position`` property in Preference to change a location of the toolbar in the scene view.
.. figure:: /images/toolbarposition_property_preference.PNG
    :scale: 40 %

Version 2.8.6 - July.12.2021
================================
.. figure:: /images/HamsterKnight_Image.png
    :scale: 50 %

- Asset : Includes Hamster Knight character pack for 2.8.6 users
- Asset : Includes the Ancient Dungeon demo pack for 2.8.5 and 2.8.6 users
- Fix : Fixed a shortcut of Rect Select Mode not working
- Fix : Fixed Autolayout undo bug.

Version 2.8.5f3 - July.2.2021
================================
- Assets : Includes new Ancient Dungeon demo pack for 2.8.5 users
- Fix : Fixed incorrect UVs of an .obj exported mesh when Export Face Type is Quads.
- Fix : Fixed incorrect fold out arrow directions in the inspector window of UVEditor and 3D Modeling.
- Fix : Made Rect Select Mode property only visible in Edge and Polygon tools.

Version 2.8.5f2 - June.29.2021
================================
- Assets : Includes new ``Ancient Dungeon`` demo pack for 2.8.5 users
- Enhancement : Added ``Grow Select`` tool in ``Selection`` group of UV Editor.
- Enhancement : Added ``Rect Select Mode`` for Edge and Polygon selection. ``Intersect`` and ``Complete`` modes are available. The default shortkey is ``CTRL+SHIFT+W``.
- Enhancement : Increased gizmos' size in UV Editor entirely.

Version 2.8.5 - June.17.2021
================================

.. figure:: /images/AncientDungeonScenes.png
    :scale: 30 %

- Assets : Includes new ``Ancient Dungeon`` demo pack for 2.8.5 users
- Fix : Fixed PushPull tool bug where null exception error happens when a polygon is pushed until the end.
- Enhancement : Added a shortcut for ``Select Only Visible`` in Element Tools. The default one is ``CTRL + SHIFT + V``
- Enhancement : Added a shortcut to toggle on and off ``Triangulation`` in Settings. The default one is ``CTRL + SHIFT + 1``
- Enhancement : Added a shortcut to toggle on and off ``Restrict To Angle`` in Settings. The default one is ``CTRL + SHIFT + X``

Version 2.8.4f5 - June.11.2021
=================================
- Assets : Includes ``Blacksmith`` demo pack.
- Feature : ``Shrink Selection Tool`` has been added - :ref:`Shrink Selection Tool`
- Tweak : Renamed ``Increase Selection tool`` to ``Grow Selection Tool`` 
- Enhancement : Added some properties like ``Restrict To Angle``, ``Max Angle`` and ``Interative`` in Settings window for ``Grow Select``
- Enhancement : Added Triangulation color field in the Preference.
- Fix : Fixed the edge selection bug again.
- Fix : Fixed a bug where a polygon becomes black when Vertex snap holding ``V`` key is applied.

 .. figure:: /images/GrowSelection_RestrictToAngle.gif
    :scale: 30 %

    Grow Selection where ``Restrict To Angle`` is applied


 .. figure:: /images/GrowSelection_NoIterative.gif
    :scale: 30 %

    Grow Selection where ``Iterative`` is off

Version 2.8.4f4 - June.10.2021
=================================
- Assets : Includes ``Blacksmith`` demo pack.
- Fix : Fixed the edge selection bug where edges can't be selected.
- Fix : Fixed a bug in Unity 2021.1 where orange highlight wasn't turned off when entering the edit mode.
- Fix : Fixed a bug where occluded vertices/edges were selected as ``Select Only Visible`` was enabled.
- Fix : Fixed a bug where long delay happened in play mode when a UModeler object is selected due to processing menu icons. 
- Enhancement : Added ``Remove All`` button in the Smoothing Group Tool

Version 2.8.4f2 - May.31.2021
=================================
- Assets : Includes ``Blacksmith`` demo pack.
- Enhancement : Added ``Extrude Modifier Key`` to ``Preference`` window to set the modifier key for extruding using the gizmos. Either ``Shift`` or ``Capslock`` is available.

.. figure:: /images/ExtrudeModifierKeySettings.png
   :scale: 60 %

- Enhancement : Added ``Enable Alpha Channel`` to ``Settings`` window in ``UV Editor`` to apply the alpha channel to display transparent pixels.

.. figure:: /images/EnableAlphaChannel_UVEditorSettingsWindow.png
   :scale: 60 %
 
- Fix : Fixed the edge selection bug when a UModeler object scale is not uniform.

Version 2.8.4f1 - May.18.2021
=================================
- Assets : Includes ``Blacksmith`` demo pack.
- Enhancement : A function to select overlapping polygons has been added to the Diagnosis Tool.
- Fix : Fixed a bug where objects hidden in the Hierarchy were clicked.
- Fix : Fixed a bug where UVs move suddenly when a vertex moves. The UVs are transformed in UV tool.
- Fix : Fixed a bug that caused the scene's pull-down menu to close immediately when the UV editor is on.

Version 2.8.4 - May.10.2021
=================================
.. figure:: /images/blacksmith.png

- Assets : Includes ``Blacksmith`` demo pack.
- Enhancement : Added The Pixel snap to ``UV Editor``.
- Enhancement : V snap - If you drag the XYZ axis and snap to another point holding ``V key``, only the dragged axis coordinate will be aligned with that point. Namely ``1D snapping`` has been restored.
- Enhancement : Added ``Menu > Tools > UModeler > Export as .Obj`` menu. Using this menu, you can export UModeler objects to an OBJ file even when multiple objects are selected at once and an object without UModeler is selected.
- Fix : Fixed a bug where snaps were applied twice when moving edges or polygons in the world grid.
- Fix : Changed the grayscale icons not to be loaded when entering play mode.
- Fix : Changed the lightmap UV2 coordinates to be updated every time the umodeler is modified.
- Fix : The minimum values ​​of Width and Depth of the Rectangle Tool and the Box Tool have been changed from 0.01 to 0.001.
- Fix : Increased the overlay size of Vertex tool and Rectctangle Selection tool in UV Editor.
- Fix : Fixed a bug where V Snapping to other objects didn’t work in 2020.3 and newer versions.

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