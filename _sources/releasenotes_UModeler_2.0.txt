############################
UModeler 2.0
############################

 .. figure:: /images/UModeler_Banner.png
 
Version 2.2.3.1
==================================================================================
 - BugFix : Fixed leaving blue vertex/polygon selection boxes after deleting the UModeler object.
 
Version 2.2.3
==================================================================================
 - Feature : Added the One-Click Build feature to Rectange, Disk, Box, Room, Stair, Cylinder, Cone, Spiral Stair, Sphere and Capsule tools.
 - Enhancement : Added the New UModeler Object button to the toolbar in the scene view.
 - Enhancement : Allowed the 3D cursor to move to the center of a polygon under the mouse cursor by ``CTRL+SHIFT+RMB``.
 - BugFix : Reverting the changes done just before pressing Play button.
 - BugFix : Enabled z-test of the transparent selection polygon displayed on the selected polygons, and resolved z-fighting issue. 

Version 2.2.2
==================================================================================
 - Feature : Added Spiral Stair Tool
 - BugFix : Line Tool - Disappearance of a part of a line drawn across a polygon more than twice
 - BugFix : The mesh out of UModeler disappeared while the camera is near it due to a incorrect bound box.
 - Enhancement : Enabled the text based menu to be displayed on the separate menu window like Icon based Menu.
 - Enhancement : Reduced the flickering of outlines of UModeler mesh.

Version 2.2.1
==================================================================================
 - BugFix : Vertex/Edge/Polygon Tools - Adding multiple selections by dragging LMB holding CTRL
 - BugFix : Line Tool - Cutting a polygon by a new edge between another existing two edges.
 - BugFix : Line Tool - Wrong shape of polygon when connecting the last point to the first point.
 - BugFix : UModelerize - Fixed UModelerization failure.
 - BugFix : Remove Doubles - Immediate update of blue vertex boxes for selection.
 - BugFix : UI of the inspector - Fixed blocking key inputs in a parameter editor box.
 - Change : Adding the popup menu for selecting menu mode in both the UV Editor and the inspector window.

Version 2.2.0
==================================================================================

General
---------------
 - Change : Replaced ``Tools`` and ``Settings`` foldout arrows with Toolbar UI in the inspector.
 - Change : Changed ``Transform`` group name into ``Elements``.
 - Change : Moved ``Pivot Tool`` from ``Transform group`` to ``Tweak group``.  (See :ref:`this <PivotTool>`)
 - Change : Disabled the Local Ruler display of the selected elements.
 - Change : ``Snap Tool`` has been renamed to ``Snap Move Tool`` and moved from ``Transform grooup`` to ``Tweak group``. (See :ref:`this <SnapMoveTool>`)
 - Change : ``3D Cursor Tool`` has been removed. Instead 3D cursor can be enabled via Settings and it can be positioned anytime. (See :ref:`this <Use3DCursor>`)
 - Change : Removed ``Cursor As Pivot`` property in ``Vertex/Edge/Polygon Tools``. Instead just enabling ``3D Cursor`` in ``Settings`` does it.
 - Change : ``Help`` button has been replaced with ``?`` button in the inspector.
 - Change : Renamed ``Invert Face Tool`` into ``Flip Tool``.
 - Change : Renamed ``Flip Tool`` into ``Axis Flip Tool``.
 - Change : Moved UModeler status box displayed on Scene view to the inspector.
 - Change : Disabled ``Input Viewer`` which will be replaed with ``Commentary Box``
 - Change : Moved ``Open UVEditor`` button from ``Surface Group`` into ``UV Tool`` property.
 - Change : Removed Polygon group button and list in UModeler status. They are only availabe within ``Polygon Group Tool``.
 - Enhancement : Improved a way of positioning 3D Cursor by ``Ctrl+Shift+LMB`` on a vertex.
 - Enhancement : Auto snapping ``3D Cursor`` to the cloeset UV vertex.
 - Enhancement : ``Align Tool`` - Replacing Axis/Location combo boxes with Toolbar buttons.
 - Enhancement : ``Boolean Tool`` - Revealed each boolean operation as tools in the inspector.
 - Enhancement : ``Pivot Tool`` - Enhanced a way of setting a pivot. 3D Cursor position will be the pivot as soon as selecting ``Pivot Tool``.
 - BugFix : ``Clone Tool`` - Fixed invisible polygon outlines along a line while dragging LMB.
 - BugFix : ``Eraser Tool`` - Fixed incorrect edge removal on a quad of a cube which is converted from a Unity primitive cube.
 - BugFix : Fixed wrong directions and positions of gizmos after rotating or scaling an object.
 - BugFix : Fixed wrong positions of vertex/polygon boxes used for selecting vertex/polygon.
 - BugFix : Fixed a shared mesh after duplicating a UModeler object.
 - BugFix : Fixed replacing Unity primitive shape mesh with UModeler mesh after UModelerizing.
 - BugFix : ``Multi PushPull Tool`` - Fixed former polygons disappearance when one step pushpull is done just after pushpull by dragging an arrow
 - BugFix : Fixed Duplicated Cancel action triggered by pressing ``ESC`` while selecting Vertex/Edge/Polygon.

UV Editor
---------------
 - Feature : Added ``Packing Tool``. (See :ref:`this <PackingTool>`)
 - Feature : Added ``Fit Tool``. (See :ref:`this <FitTool>`)
 - Feature : Renamed ``Collapse Tool`` to ``Weld Tool`` and divided it into ``Weld to First``, ``Weld to Ave`` and ``Weld to Last``.  (See :ref:`this <WeldTools>`)
 - Enhancement : Auto snapping ``Cross Cursor`` to the cloeset UV vertex.
 - Enhancement : Improved the whole performance.
 - Change : ``Make Island Tool`` has been renamed to ``Detach`` Tool.
 - Change : ``Sew Group`` and ``Break Merge Group`` has been merged and the merged group has been named ``Weld and Break``.

3.0 Beta
---------------
 .. figure:: /images/UModeler_NewUI.gif
    :scale: 95 %

    New Menu System - Switchable between Text based and Icon based by clicking ``T`` toggle in the inspector.

 - Feature : New Menu System (Icon and Context based). This can be enabled by toggling ``T`` off in the inspector.
 - Feature : ``Commentary Box`` - Can be enabled/disabled via ``Settings``.
 - Feature : Added ``T`` toggle to the top of the inspector to switch the menu between Text-based and Icon-based
 - Feature : Added ``F`` toggle next to ``T`` toggle to make the menu dockable and floatable.
 - Feature : Placed Vertex/Edge/Polygon Tools icons on the top-center of the scene view.
 - Feature : Placed Settings icon and 3D Cursor icon next to Vertex/Edge/Polygon tool icons on the scene view. They can be toggled on and off.
 - Change : Added ``UModeler Window`` to the top menu.

Version 2.1.1
==================================================================================

 - Feature : Edge/Polygon Tranform - Added Extrusion fuctions holding ``SHIFT``. (See :ref:`this <basicextrusionintransform>`)
 - Enhancement : Vertex/Edge/Polygon Selection - Added ``Select only visible`` property to selects non occluded elements from a camera. (See :ref:`this <selectonlyvisibleintransform>`)
 - Enhancement : Multi PushPull - Changed a helper line to an arrow.
 - Enhancement : Multi PushPull - Added One step push/pull. (See :ref:`this <onesteppushpull>`)
 - Enhancement : Multi PushPull - Added Vertex Normal type extrusion. (See :ref:`this <vertexnormalpushpull>`)
 - Change : Multip PushPull - ``Individual`` in PushPull type has been renamed to ``Individual Polygon``
 - Change : Removed ``Game Object`` tool and Renamed ``Collider Object`` to ``New UModecler`` in Misc group.
 - Feature : UVTool - Added ``Export`` tool to export uv outlines to .png file. (See :ref:`this <exportuvoutline>`)

Version 2.1.0
==================================================================================

 - Feature : Export/import button in the Preference window to export/import shortcuts and general settings as a xml format.
 - Enhancement : Collider tool - Added Assign Mesh button to assign the current mesh to the mesh collider.
 - BugFix : Ballooned gizmos when scale in transform component has been changed.
 - BugFix : Not coming back to the previous mesh immediately after canceling action by pressing ESC

Version 2.0.9
==================================================================================

 - Feature : Added "Triangulate" in the menu
 - Enhancement : Inset tool - Enabling an inset from a hole.
 - Enhancement : UModelerizing probuilder mesh. After converting, probuilder specific components are removed.
 - BugFix : Keeping Polygon mode after using Combine tool or Flatten tool.
 - BugFix : Spammed warning messages displayed while typing numbers in the inspector after transfoming/extruding.

Version 2.0.8
==================================================================================

 .. figure:: /images/UModeler_ProSkin.png

 - Feature : Added a new tool - Polygon Group Tool. (See :ref:`this <polygongrouptool>`)
 - Fix : Some incorrect colors on Pro skin.

Version 2.0.7
==================================================================================
 - Feature : Advanced menu tooltips.
 - Feature : Added ``Help`` button at the top of tools in the Inspector to show Online Manual
 - Feature : Added Color settings in Preferences. (See :ref:`this <AdvancedPreferences>`)
 - Enhancement : Shortcut Settings in Preferences - Modifiers' list box has been replaced with 3 toggle boxes (``Shfit``, ``Ctrl`` and ``Alt``) (See :ref:`this <AdvancedPreferences>`)
 - Documentation : 3D Cursor Tool.
 - Documentation : Pivot Tool (See :ref:`this <PivotTool>`)
 - Documentation : Snap Tool
 - Fix : Material Tool - Added codes to deal with null material.
 - Fix : Error of invalid selected polygon display.

Version 2.0.6
==================================================================================
 - Feature : New snapping - Snap to X-axis or Y-axis of the current placed points. This makes drawing a rectangle and a right angle triangle etc possible using ``Line Tool`` (See :ref:`this <SnapToXY>`)
 - Feature : Seamless Editing - UModeler objects in a scene can be edited seamlessly. (See :ref:`this <seamless-edit>`)
 - Enhancement : Edge display - Disabled showing invisible parts' edges.
 - Fix : Added recalculating tangents (See :ref:`this <recalculate-tangents>`)
 - Fix : Z-fighting of the polygon selection mesh.

Version 2.0.51
==================================================================================
 - Hotfix : Adding/Removing material in Material tool wreren't allowed.
 - Hotfix : Individual edge transform holding ``SHIFT``.
 - Hotfix : Incorrect triangle count. The former displayed triangle number was twice more than the real one.

Version 2.0.5
===============
 - UV Editor : PBR texture preview
 - UV Editor : Keeps width/height ratio of the polygon after unwrapping.
 - UV Editor : Keeps the orientation of the polygons after unwrapping.
 - Supports the Surforge preview texture wrapped in UModeler.
 - UV Editor : 1D snapping done by transforming elements holding ``CTRL``
 - Transform tool : 1D snapping done by transforming elements holding ``CTRL``
 - Transform tool : Exposure of ``Insert Vertex`` property.
 - ``Transform Tool`` : Vertex splits when transforming a vertex holding ``SHIFT``.
 - ``Material Tool`` : Improvement of displaying material preview in the list. The material with no texture is also displayed well.
 - ``Bevel Tool`` : Made the selected vertices/edges/polygons visible at the beginning of Beveling.
 - ``Vertex Color Tool`` has been added.
 - The Color tool has been renamed to ``Polygon Color Tool``.
 - Grid Setup : ``0.0315``, ``0.0625`` grid size have been added to Popular Grid Size

Version 2.0.0
===============
 - UV Editor has been added. See :ref:`uveditor_label`
 - ``Properties`` in the inspector is displayed under the group of the selected tool.
 - Added the clone of the selected polygons.
 - ``FreezeXForm Tool`` - Renamed to ``Bake Transform`` and divided it into Scale and Rotation.
 - Added generating Lightmap UVs in ``Local Settings Tool`` under ``Misc`` group in the inspector.
 - ``Arrange UV Islands`` menu item has been added in UModeler tool menu.
 - Made a new UModeler game object created under the parent object when clicking on "Game Object" or "Collider Object" button.
 - ``Grid Size`` field has been added to ``Settings/Snap`` to make it possible to specify any grid size.
 - ``Mirror Tool`` - Now you can move the mirror plane by ``LMB Drag`` over the arrow of the mirror plane.
 - ``Flip Tool`` has been added in ``Tweak`` group.
 - ``Align Tool`` has been added in ``Tweak`` group.
 - ``UV Tool`` - Added moving UVs by pressing Up or Down arrow keys holding CTRL.
 - ``Combine Tool`` - Pressing ``SPACE`` will combine the selected vertices in ``Combine Tool``.
 - ``Vertex/Edge/Polygon Tool`` - 1D Snapping has been added. It works by moving a cursor to another vertex holding ``CTRL`` while dragging the translation gizmo.
 - ``Vertex/Edge/Polygon Tool`` - ``Insert Vertex`` property has been added.
 - Change - ``PushPull Tool`` : Renamed ``Draw Edges`` property to ``Continuous``.
 - Change - ``Multiple PushPull`` button has been added. see :ref:`pushpull_tool_label`
 - Change - ``Cut Tool`` : Made Cutting direction flipped by pressing ``SPACE`` while ``LMB`` Dragging
 - Change - ``Backface Tool`` : Renamed to ``Local Settings``
 - Change - ``Copy Tool`` : Renamed to ``Duplicate Tool``
 - Change - ``Game Object`` and ``Collider Object`` buttons have been moved to ``Misc`` group.
 - Bugfix - Not displaying triangulation result has been fixed.
 - Bugfix - Spotty lightmap bug has been fixed.
