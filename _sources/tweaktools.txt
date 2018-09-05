############
Tweak Group
############

Flip Tool (Formerly called Invert Face Tool)
==============================================

.. note::

 Since Ver 2.2 ``Invert Face Tool`` has been renamed to ``Flip Tool``.

Flips the selected polygons.

.. figure:: /images/UModeler_InvertFaceTool.gif
   :scale: 95 %

   Selects several polygons and flips them.
   
   
----------------------------------------------------------------------------------------------------------------
   
Flatten Tool
==============

Flattens the selected polygons so that all the selected polygons will be aligned with the last polygon’s plane.

This tool is useful when you merges coplanar polygons using ``Combine Tool``.

Properties
------------

Projection Dir  
  * ``Up`` - Y direction
  * ``Right`` - X direction
  * ``Forward`` - Z direction
  * ``Last Polygon`` - The normal direction of the last selected polygon.
  
.. note::

   In order to change properties you should select ``Flatten Tool`` without any selected elements.
   
   
.. figure:: /images/UModeler_FlattenTool_v2.gif
   :scale: 95 %

   Flattens a few polygons and combines them using ``Combine Tool``.
   
   
----------------------------------------------------------------------------------------------------------------
   
Align Tool
==============

Aligns the vertices of the selected elements within bounds.

Steps
---------------------------------
1. Select ``Align Tool`` with the selected elements, or Enter ``Align Tool`` and select vertices.
2. Choose Axis and Location in Properties.
3. Click on ``Align`` button.

Properties
---------------
Select Only Visible
 If on, Selects only visible vertices/edges/polygons from a camera. Occluded elements from other polygons will not be selected. This is available only when the game object has MeshCollider component.
 
 Axis  
  X, Y, or Z axis for alignment.
  
 Location
  * ``Min`` - Minimum location of the selected axis.
  * ``Middle`` - Middle location of the selected axis.
  * ``Max`` - Maximum location of the selected axis.
  
.. figure:: /images/UModeler_AlignTool.gif
   :scale: 95 %

   Align Tool Demo.
   

----------------------------------------------------------------------------------------------------------------
   
Axis Flip Tool (Formerly called Flip Tool)
============================================

.. note::

 Since Ver 2.2 ``Flip Tool`` has been renamed to ``Axis Flip Tool``.

Flips the selected polygons along its local X-, Y- or Z-Axes across the mirror plane center. This tool behaves like the Mirror tool to some degree.

Steps
--------------------------------
1. Select ``Flip Tool`` with the selected polygons.
2. Adjust ``Axis``, ``Distance`` and ``Invert`` properties to set the mirror plane.
3. Click on ``Flip`` button.

Properties
---------------
Select Only Visible
 Selects only visible vertices/edges/polygons from a camera. Occluded elements from other polygons will not be selected. This is available only when the game object has MeshCollider component.
 
Axis
 Mirror plane axis

Invert
 Inverts the direction of the mirror plane.

Distance
 The distance of the mirror plane.

Flip
 Flips the mirror plane.
 
.. figure:: /images/UModeler_FlipTool.gif
   :scale: 95 %

   Flip Tool Demo.
   
----------------------------------------------------------------------------------------------------------------------

.. _PivotTool:

Pivot Tool
====================================

.. note::

 Since Ver 2.2 ``Pivot Tool`` has moved here from ``Transform`` group.
 
Sets a position of a pivot of the current object. The current position of 3D cursor will be a pivot pos immediately after selecting this tool.

-----------------------------------------------------------------------------------

.. _PivotToCenterTool:

Pivot To Center Tool
=======================

.. note::

 Since Ver 2.2 ``Pivot To Center Tool`` has moved here from ``Misc Group``.

Changes the pivot location to the bottom center.

----------------------------------------------------------------------------------------------------------------------

.. _SnapMoveTool:

Snap Move Tool (Formerly called Snap Tool)
============================================

.. note::

 Since Ver 2.2 ``Snap Tool`` has moved here from ``Transform Group`` and it has been renamed to ``Snap Move Tool``.

Moves a polygon to the specific position. This tool can be used to set a profile polygon for ``Follow Tool``.

Interface
-----------
``SPACE``
 Flips the selected polygon horizontally.

``LMB Down``
 Selects a position.

``ESC``
 Goes back to the previous step or exits the Snap tool.

Properties
-----------

Flip
 Flips the polygon horizontally.

 .. figure:: /images/UModeler_snaptool.gif
   :scale: 95 %

   ``Snap Move Tool`` Demo