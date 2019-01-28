################
Axis Flip Tool
################

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
