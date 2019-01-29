.. |Icon_Misc_PolygonGroup| image:: /images/Icon_Misc_PolygonGroup.png
   :scale: 100 %

################################################
Polygon Group Tool |Icon_Misc_PolygonGroup|
################################################

Groups the selected polygons into a single group. ``Active Group`` in the UModeler Status on the scene view displays the current polygon group. The newly created polygons will belong into the activated group.
You can choose a group via either ``Active Group`` in the UModeler status or ``Polygon Group Tool`` in the inspector.

Properties
------------
Select Only Visible
 Selects only visible vertices/edges/polygons from a camera. Occluded elements from other polygons will not be selected. This is available only when the game object has MeshCollider component.
 
Group Name
 The current polygon group name
 
Polygon Count
 The polygon count in the current polygon group.
  
Add Group
 Adds a new polygon group from the current selected polygons.
 
Remove Group
 Removes the current polygon group.
 
Rename Group
 Renames the current polygon group.
 
Remove Empty
 Removes polygon groups which have no polygons.
 
Select Polygons
 Selects polygons in the current polygon group.
 
Add Polygons
 Adds the selected polygons to the current polygon group.
 
Remove Polygons
 Gets rid of the selected polygons from the current polygon group.
 
.. |UModeler_PolygonGroup_0| image:: /images/UModeler_PolygonGroup_0.jpg
   :scale: 100 %
   
.. |UModeler_PolygonGroup_1| image:: /images/UModeler_PolygonGroup_1.jpg
   :scale: 100 %
   
.. |UModeler_PolygonGroup_2| image:: /images/UModeler_PolygonGroup_2.jpg
   :scale: 100 %
   
.. |UModeler_PolygonGroup_3| image:: /images/UModeler_PolygonGroup_3.jpg
   :scale: 100 %
   
|UModeler_PolygonGroup_0| |UModeler_PolygonGroup_2|
 ``Roof`` group

|UModeler_PolygonGroup_1| |UModeler_PolygonGroup_3|
 ``Wall`` group