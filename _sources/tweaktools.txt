############
Tweak Tools
############

Invert Face Tool
==================

Flips the selected polygons.

.. figure:: /images/UModeler_InvertFace.gif
   :scale: 40 %

   Selects several polygons and flips them.
   
Flatten Tool
==============

Flattens the selected polygons so that all the selected polygons will be aligned with the last polygon’s plane.

This tool is useful when you merges coplanar polygons using ``Combine Tool``.

Properties
------------

Projection Dir  
  * Up - Y direction
  * Right - X direction
  * Forward - Z direction
  * Last Polygon - The normal direction of the last selected polygon.
  
.. note::

   In order to change properties you should select ``Flatten Tool`` without any selected elements.
   
   
.. figure:: /images/UModeler_FlattenTool.gif
   :scale: 40 %

   Flattens a few polygons and combines them using ``Combine Tool``.