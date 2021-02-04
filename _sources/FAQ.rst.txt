############
FAQ
############

Q) Is it possible to edit meshes or make them procedurally at runtime?
---------------------------------------------------------------------------------------------------------------------------------------------------------------------
No, unfortunately UModeler was designed for 3D modeling only in the Editor so it doesn't support a runtime editing and, APIs for the procedural mesh creation officially.
 
Q) How can a static mesh be converted to UModeler mesh?
------------------------------------------------------------------------------------------------------------------------------------------------
You have to select a game object with a static mesh. And go to ``Tool > UModeler > UModelerize`` at the top of Unity editor to convert the selected mesh.
Several static meshes can also be converted if you select them before trying to UModelerize.
 
Q) The UModelerized mesh is still a triangle-based shape. I want to have more like UModeler mesh. In other words All adjacent coplanar faces have to be merged into one face.
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Click on ``Combine Tool`` button once you select all polygons. This will combine adjacent coplanar polygons into one polygon.
See the `Combine Polygon Tool <https://umodeler.github.io/RemoveGroup/CombineTool.html#combine-polygon-tool-icon-remove-combinepolygons>`_.

Q) How can I set the pivot to the center of UModeler object?
-----------------------------------------------------------------------------------------
Navigate to ``Pivot to Center`` in ``Tweak`` group and click on ``Center`` button in Properties. ``Top Center``, ``Center`` and ``Bottom Center`` buttons were added from Ver 2.6.9
 
Q) UModeler meshes disappear.
-------------------------------------------
Click on ``Tools > UModeler > Refresah All`` at the top of the editor. It will build all UModeler components in the current scene to create renderable meshes.
 
Q) Broken lightmaps
-------------------------------------------
Click on ``Tools > UModeler > Refresah All`` at the top of the editor. If lightmaps are still broken, make sure that ``Light Static`` is on and click on ``Generate UV2 channel for Lightmap`` button in ``Local Settings`` tool.
And then try to ``Clear Baked Data`` and ``Generate Lighting`` in ``Lighting`` window.
 
 .. figure:: /images/LocalSettings.jpg
 .. figure:: /images/LightingWindow.jpg
 
Q) How can I hide the Toolbar at the top of the scene view when UModeler object isn't selected?
---------------------------------------------------------------------------------------------------------------------------------
Navigate to ``Tools > UModeler > Preferences`` and turn off ``Keep System Toolbar on always``.  
See :ref:`AdvancedPreferences` to get more info.