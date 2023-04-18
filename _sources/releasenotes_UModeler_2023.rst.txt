############################
UModeler 2023
############################

Version 2.10.7 | Apr.18.2023
==================================
- Fixed another NullReferenceException issue in the CheckAllUModelerPrefabInstance() method. This issue occurred in a level containing many prefab UModeler instances created with an older version of UModeler.

Version 2.10.6 | Apr.10.2023
==================================
- Fixed a NullReferenceException issue that occurred while setting a prefab instance during the loading process.

Version 2.10.5 | Mar.24.2023
==================================
- Fixed an issue where polygon counts got doubled when UModelerizing with "Create Smoothing Groups as UModelerize"

Version 2.10.4 | Feb.27.2023
==================================
- Fixed an issue where polygons to which smoothing groups are assigned are invisible.

Version 2.10.3 | Feb.23.2023
==================================
- Fixed a flickering issue caused in a UModeler mesh to which the smoothing group and lightmaps are applied.
- Fixed an issue where some vertices of Capsule and Cylinder shapes are detached when they are moved.

Version 2.10.2 | Feb.2.2023
==================================
- Fixed a bug where UV settings like Shift, Scale, Rotate etc in the UV tool are reset when a polygon is split using Loop Slice tool.
- Fixed an issue where UVs coordinates on the polygons with smoothing groups aren't updated in real time while you change the UV tool parameters like Shift, Scale and Rotate etc.

Version 2.10.1 | Jan.31.2023
==================================
- Fixed the vertex selection issue where the occluded vertices that should not have been selected were selected using the rectangle selection

Version 2.10.0 | Jan.25.2023
==================================
- Fixed an issue where ``Error : mainRenderableMesh is Null`` error occurred when a mesh was saved.
- Fixed displaying different scale UIs of the transform component.
- Fixed an issue occurred in Unity 2022.2 where undoing an 'Unpack Prefab' action shows a prompt "You can't add a UModeler component in a Prefab instance" and selecting 'OK' crashes the Editor