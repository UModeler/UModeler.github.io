*****************
Weld and Break
*****************

.. note::

 Since Ver 2.2 ``Sew Tool`` and ``Move Sew Tool`` have been moved from ``Sew Group`` to ``Weld and Break Group``.
 
.. note::

 Sew and Move/Sew tools will work with one of the following conditions.	
  1. Two groups of edges are selected.
  2. One group of edges are selected and the correspoinding overlapped edges exist.
  
Sew
=====

Attaches UVs along the selected borders, but does not move them together. 


Move/Sew
=========

Move/Sew combines separate UV islands along their selected border edges by moving the first selected UV island to the other selected UV island and merging the selected edges together so that one UV island results. 
This tool is useful for quickly joining together separate UV islands.
 
 .. figure:: /images/UModeler_UVEditor_SewTools.gif
    :scale: 95 %
  
    Demo of Sew and Move/Sew Tools 

.. _WeldTools:
 
Weld To First
==============

.. note::

 Since Ver 2.2 ``Collapse Tool`` has been renamed to ``Weld Tool`` which are divided into 3 tools. ``Weld To First``, ``Weld To Ave`` and ``Weld to Last``.
 
Merges the selected UVs to the first UV position.
	
Weld To Ave
==============
Merges the selected UVs to the avearage pos of the selected UVs.

Weld To Last
==============	

Merges the selected UVs to the last UV.
 
 .. figure:: /images/UModeler_UVEditor_CollapseTool.gif
    :scale: 95 %
  
    ``Weld To Last Tool`` Demo

  
Detach (Formerly called Make Island)
======================================

Separates the selected polygons from what they belonged into and puts them into a new island.
 
 .. figure:: /images/UModeler_UVEditor_MakeIslandTool.gif
    :scale: 95 %
  
    Detach Tool Demo