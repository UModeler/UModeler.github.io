.. |Icon_Misc_LocalSettings| image:: /images/Icon_Misc_LocalSettings.png
   :scale: 100 %

################################################
Local Settings Tool |Icon_Misc_LocalSettings|
################################################

Sets up local variables.

Properties
-------------
Backface
 backfaces on/off

Generate Lightmap UVs
 If this is on, Secondary UVs for lightmap will be generated every time UModeler mesh changes. 

.. _recalculate-tangents:
 
Recalculate Tangents
 If this is on, tangent vectors will be calculated every time UModeler mesh changes. If the materials in UModeler have normal textures, this should be on.
 
Don't Save In Build
 If this is on, UModeler component isn't included in Build. If you want to edit a mesh using UModeler at runtime, it needs to be on when the project is built.
 Usually this property is on because most meshes are just for rendering at runtime.
 
