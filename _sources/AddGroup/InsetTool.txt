############
Inset Tool
############

.. figure:: /images/Icon_Add_Inset.png
   :scale: 100 %
   
   ``Inset Tool`` icon

This tool creates a slightly smaller or bigger polygon of the selected one. 

Move the cursor over a desired polygon and start to drag a mouse. Then you'll see that the polygon outline will be bigger or smaller. Release ``LMB`` to be done. Try to change the properties in the inspector if necessary. And press ``SPACE`` to confirm.

Multiple Inset
 If several polygons are already selected when ``Inset Tool`` is activated, ``Inset`` will be applied to them at once. 
 
Repeat the previous
 ``SHIFT + LMB`` on a desired polygon repeats the previous inset. 
   
Steps - Single Inset
----------------------
1. Select ``Inset Tool`` with no selection.
2. Click on a polygon you want to apply Inset to.
3. Drag the cursor to define thickness.
4. Release ``LMB``
5. Adjust ``Thickness`` properties if necessary
6. Press ``SPACE`` or start another inset action to confirm.

Steps - Multiple Inset
----------------------
1. Select ``Inset Tool`` with some polygons selected using ``Polygon Tool``.
2. Start to drag the mouse from a polygon or adjust ``Thickness`` property directly.
3. If necessary, adjust ``Thickness`` property in ``Properties`` to give the precise value.
4. Press ``SPACE`` to complete or Press ``ESC`` to cancel.
   
Interface
---------------

``LMB Drag``
 Creates an inset of the selected polygon.

``SHIFT + LMB``
 Duplicates the previous inset.

``SPACE``
 Confirms the current inset.

``ESC``
  Cancels the current inset or exit Inset tool.

Properties
---------------
Thickness
 How smaller or bigger the polygon is. This is the distance between the starting point and the current point.

Type (for ``Multiple Inset``)
 * ``Individual`` -  Each selected face is inset on its own.
 * ``Group`` - ``Inset Tool`` operates on the region around selected faces

Bridge Edges
 Links corresponding edges between the original polygon and the inset polygon.
 
.. figure:: /images/UModeler_Inset_0.jpg
   :scale: 95 %

   Single Inset.
   
.. figure:: /images/UModeler_Inset_1.jpg
   :scale: 95 %

   Multi Inset - Three polygons are selected.
   
.. figure:: /images/UModeler_Inset_2.jpg
   :scale: 95 %

   Multi Inset - as ``Type`` property is ``Individual``

.. figure:: /images/UModeler_Inset_3.jpg
   :scale: 95 %

   Multi Inset - as ``Type`` property is ``Group``