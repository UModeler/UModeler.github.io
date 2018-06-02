############################
UModeler 2.0
############################

 .. figure:: /images/UModeler_Banner.png
 
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
 - Documentation : 3D Cursor Tool (See :ref:`this <3DCursorTool>`)
 - Documentation : Pivot Tool (See :ref:`this <PivotTool>`)
 - Documentation : Snap Tool (See :ref:`this <SnapTool>`)
 - Fix : Material Tool - Added codes to deal with null material.
 - Fix : Error of invalid selected polygon display.
 
Version 2.0.6
==================================================================================
 - Feature : New snapping - Snap to X-axis or Y-axis of the current placed points. This makes drawing a rectangle and a right angle triangle etc possible using ``Line tool`` (See :ref:`this <SnapToXY>`)
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
 - ``Transform tool`` : Vertex splits when transforming a vertex holding ``SHIFT``.
 - ``Material tool`` : Improvement of displaying material preview in the list. The material with no texture is also displayed well.
 - ``Bevel Tool`` : Made the selected vertices/edges/polygons visible at the beginning of Beveling.
 - ``Vertex Color Tool`` has been added.
 - The Color tool has been renamed to ``Polygon Color tool``.
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
 - Tweak - ``PushPull Tool`` : Renamed ``Draw Edges`` property to ``Continuous``.
 - Tweak - ``Multiple PushPull`` button has been added. see :ref:`pushpull_tool_label` 
 - Tweak - ``Cut Tool`` : Made Cutting direction flipped by pressing ``SPACE`` while ``LMB`` Dragging
 - Tweak - ``Backface Tool`` : Renamed to ``Local Settings``
 - Tweak - ``Copy Tool`` : Renamed to ``Duplicate Tool``
 - Tweak - ``Game Object`` and ``Collider Object`` buttons have been moved to ``Misc`` group.
 - Bugfix - Not displaying triangulation result has been fixed.
 - Bugfix - Spotty lightmap bug has been fixed.
  