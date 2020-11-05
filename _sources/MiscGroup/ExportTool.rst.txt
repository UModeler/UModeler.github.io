.. |Icon_Misc_Export| image:: /images/Icon_Misc_Export.png
   :scale: 100 %

.. _ExportTool:

################################################
Export Tool |Icon_Misc_Export|
################################################

.. figure:: /images/UModeler_ExportTool.jpg

Exports the current UModeler mesh to a file in a specific file format. 
If you select multiple UModeler objects and then export as .Obj, the selected UModeler meshes will be exported as a single .Obj file.

Properties about .obj
-----------------------

Create Folder
 A folder will be created and .OBJ and .MTL will be exported inside it 

Export Material
 A Material file(.MTL) will be created.
 
Export Vertex Colors
 RGB channel is added to each vertex. This format doesn't guarantee compatibility according to a program where .obj is loaded. 

Optimize UV
 Optimizes UVs to avoid duplication.
 
Export to .obj
 Exports the UModeler mesh to .obj

.. note::

 As from UModeler 2.7.26 Multiple UModeler Objects' meshes can be exported to one .obj file.

 
Properties about .prefab
--------------------------

Export to .prefab
 Exports the UModeler mesh to .prefab. Prefab is saved only in a folder under Project folder.