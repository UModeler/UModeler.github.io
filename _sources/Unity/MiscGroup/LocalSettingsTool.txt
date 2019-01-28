########################
Local Settings Tool
########################

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
 
.. figure:: /images/UModeler_GenerateLightmapUVs.gif
   :scale: 95 %
	
   ``Generate Light UVs`` Demo.
   
.. figure:: /images/UModeler_RecalculatingTangents.gif
   :scale: 95 %
	
   ``Tangent Recalculataion`` Demo.