############################
UModeler 2019
############################

 .. figure:: /images/releasenote2019_3.jpg
 
Version 2.6.13 - Aug.5.2019
==================================
- Hotfix : BoxTool - Fixed one click build bug where unnecessary polygons were created.
- Hotfix : Fixed bug where Global/Local Overlay size and location are wrong when a mesh is translated/roatated/scaled.
- Hotfix : Fixed missing UVs after UModelerization.
- Hotfix : Fixed wrong outline of a scaled mesh. 
- Hotfix : Fixed black polygons appearance after UModelerization due to the wrong calculation of the plane normal.
 
Version 2.6.12 - July.23.2019
==================================
- Hotfix : Select All Tool - Fix bug where vertex overlays aren't updated when selecting all vertices using Select All Tool.
- Hotfix : Line Tool - Fix bug where a line couldn't cut a polygon when the umodeler object is too large.
 
Version 2.6.11 - July.16.2019
==================================
 - Hotfix : Fix bug where Settings are not preserved.
 - Hotfix : Fix bug where Scaling using the scale gizmo isn't correct.
 - Hotfix : Fix bug where mouse events aren't captured off the scene view.
 
Version 2.6.10 - July.02.2019
==================================
 - Hotfix : Fix bug where lightmaps are broken in play mode. 
 - Hotfix : Fix bug where the gizmo disappear when getting back to edit mode from play mode. 
 - Enhancement : Enhanced ``Tools > UModeler > Refresh All`` to fix invisible mesh and generate secondary uvs etc. 
 - Change : Changed ``Generate Lightmap UVs`` to ``Lightmap Static`` and added ``Generate UV2 channel for Lightmap`` button to ``Local Settings`` tool
 
Version 2.6.9 - June.28.2019
=================================
 - Hotfix : Fixed bug of primitive shape group tools and pushpull tool where pushing or pulling a face sometimes causes unexpected sudden move when the mouse cursor points at somewhere in the background. 
 - Hotfix : Enables 3D cursor to be displayed in object mode. 
 - Hotfix : Fix bug where UModeler meshes with smoothing groups disappears in play mode
 - Enhancement : Added ``Top Center``, ``Center`` and ``Bottom Center`` buttons to ``Pivot To Center`` tool.
 
Version 2.6.8 - June.7.2019
=================================
 - Hotfix : Fix bug where .asset file wasn't created when exporting to .prefab using Export Tool in UModeler.

Version 2.6.7 - June.5.2019
=================================
 - Hotfix : Improved compatibility with ProBuilder 4.x for displaying icons without overlapping and UModelerizing ProBuilder Object with deleting ProBuidlerMesh component. 
 - Hotfix : Fixed bug where UModeler mesh is missing after instantiating UModeler object at runtime. Added UModeler.Builder() in UModeler.Start() message to have the mesh updated when UModeler component starts.
 
Version 2.6.6 - May.31.2019
=================================================================================
 - Hotfix : Fixed bug where triangle count is not correct
 - Hotfix : Fixed bug where the detached uv islands or polygons don't move separately without holding CTRL+SHIFT.
 - Hotfix : Fixed bug where blue cubes representing vertex positions and polygon center positions aren't vanished when UModeler object is deleted.
 
Version 2.6.5 - May.13.2019
=================================================================================
 - Hotfix : Fixed bug where moving a vertex or an edge sharing two polygons that have different materials doesn't work.
 
Version 2.6.4 - May.10.2019
=================================================================================
 - Hotfix : Fixed errors while UModelerizing.
 - Hotfix : Fixed bug where the selected UModeler object disappearing when entering the game mode.
 - Hotfix : Fixed bug where icons look a little bit whitish.
 
Version 2.6.3 - May.7.2019
==================================================================================
 - Hotfix : Fixed bug where Export Tool in UV Editor doesn't work in the latest Unity.
 
Version 2.6.2 - May.3.2019
==================================================================================
 - Hotfix : Fixed bug where combine objects and boolean operation don't work.  
 
Version 2.6.1 - May.2.2019
==================================================================================
 - Hotfix : Missing  sciprt in the existing UModeler component.
 - Hotfix : Not displaying the cursor and overlays in Unity 2019.1.0f2
 
Version 2.6 - Apr.29.2019.4
==================================================================================
 - Enhancement : Added two buttons to MeshFilter component inspector to have the mesh saved as .asset file (See :ref:`this <meshfiltercomponent>`)
 - Enhancement : Added ``Don't save in build`` to ``Local Settings`` tool to make you decide if UModeler component is included or not in build.
 - Enhancement : Enabled to build UModeler mesh at runtime
 - Enhancement : Renewed the Preference window.  
 - BugFix : Fixed broken icons caused as UModeler root folder is moved.
 - Change : Added preselection color setting to ``Color settings`` in ``Preference``
 
Version 2.5 - Feb.26.2019
==================================================================================
 - New Feature : Add UV Auto Layout function to the polygon tool.
 - New Feature : Add Color palettes to Vertex/Polygon color tools
 - New Feature : Introduce the Slot concept in Smoothing Group Tool
 - New Feature : Introduce the Slot concept in Material Tool
 - New Feature : Add Direct UV transform using Move/Rotate/Scale tools in the Scene view.
 - New Feature : Pre-selection Vertex/Edge/Polygon highlight
 - New Feature : Enable shortcuts in UV Editor
 - Enhancement : Improve Shortcut Setting UI in Preference to display only names of tools belonging to the selected group. 
 - Enhancement : Add a button to assign a material to the whole object at once to the Material tool.
 - Enhancement : Allow camera panning in UV Editor by LMB dragging with ALT holding.
 - Enhancement : Allow the shorcut of New UModeler Tool all the time even when no umodeler object is selected. 
 - Enhancement : Make the cone slicing possible using Loop Slice tool.
 - Change : Assgin New UModeler tool's default shortcut as ``CTRL + SHIFT + M``
 - Change : Change the default shortcuts for vertex/edge/polygons tools to Shift + 1/2/3
 - Change : Deprecate Edge Extrusion tool
 - Change : Update the help doc links  
 - Change : Display the tool bar icons in the text based menu on UV editor.
 - Change : Add Confirm/Cancel buttons to the Property window of Clone Tool 
 - BugFix : Fix stack overflow errer of Loop Slice Tool. 
 - BugFix : Fix a bug not updating collider immediately.
 - BugFix : Fix a bug drawing a unexpected selection quad just when UV Editor is opened. 
 
Version 2.4 - Jan.4.2019
==================================================================================
 - Enhancement : Kept Toolbar visible while the text menu is enabled.
 - Enhancement : Stored the manu type in the registry whenever the menu is changed between text based and icon based
 - BugFix : Fixed not bringing the Meshfilter mesh when UModeler component is added to a game object with MeshFilter component.
 - BugFix : Gizmo scaling issue occuring when a couple of scene views are opened. 
 - BugFix : Discarded .asset export in Export tool. It can be replaced with .prefab export.
 - BugFix : Invisible UModeler object with a parent prefab after its parent prefab is placed on the scene.