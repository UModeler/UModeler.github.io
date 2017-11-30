############
Tweak Tools
############

Invert Face Tool
==================

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
   
Flip Tool
==============   

Flips the selected polygons along its local X-, Y- or Z-Axes across the mirror plane center. This tool behaves like the Mirror tool to some degree.

Steps
--------------------------------
1. Select ``Flip Tool`` with the selected polygons.
2. Adjust ``Axis``, ``Distance`` and ``Invert`` properties to set the mirror plane.
3. Click on ``Flip`` button.

Properties
---------------

Axis
 Mirror plane axis

Invert
 Inverts the direction of the mirror plane.

Distance
 The distance of the mirror plane.

Flip
 Flips the selected polygons.
 
.. figure:: /images/UModeler_FlipTool.gif
   :scale: 95 %

   Flip Tool Demo.
   