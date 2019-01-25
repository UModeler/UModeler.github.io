################
PushPull Tool
################
.. tip::

 If you want a uniform size of height in ``PushPull Tool``, enable ``Snap`` in ``Settings > Snap``

Extrudes a polygon in a normal direction of it. You can push/pull any type of polygon, including circular, rectangular, and abstract polygons.
   
Steps
-----------
1. Go to ``PushPull Tool`` with no selection
2. Move the mouse cursor to a polygon you want to extrude
3. Start to drag from the polygon in a normal direction of it.
4. Release ``LMB`` when you finish the extrusion.
5. If you need the precise height, fill ``Height`` field out in ``Properties``.
6. Press ``SPACE`` to confirm or press ``ESC`` to cancel.

Interface
-----------

``LMB Drag``
 Pushes or pulls a polygon in a normal direction of the polygon.
 
``CTRL + LMB Drag``
 Pushes or pulls a polygon at a time so that its height will be aligned to the other parallel polygon where the mouse points.
 
``SHIFT + LMB``
 Repeats the previous extrusion to double the size of the extrusion or create a separate but identical extrusion.
 
``SPACE``
 Confirms ``Push/Pull``.
 
``ESC``
 Cancels ``Push/Pull`` or exit ``Push/Pull``.
 
Properties
---------------

Height
 Precise height.

Border Check
 If this is enabled, the ray cast will run and it checks if the new created polygons while pushing or pulling will be beyond the other polygons. This can be used to cut a 3d shape, too.
 
.. note::

 Please note that ``Border Check`` property needs many pre-calculations so it may affect the performance. Therefore, if you feel any lag at the beginning of push/pull, please turn this property off and try again.
 
Continuous
 If off, the boundary edges between the existing side polygons and the new side polygons will be left. 

.. figure:: /images/UModeler_PushPullToolBasic.gif
   :scale: 95 %

   Basic PushPull Tool Demo - ``Height`` and ``Continuous`` properties
   
.. figure:: /images/UModeler_PushPullToolBoundaryCheck.gif
   :scale: 95 %

   ``Boundary Check`` property Demo   

.. figure:: /images/UModeler_PushPullToolDuplicateThePrev.gif
   :scale: 95 %

   Duplicate the previous extrusion by ``SHIFT + LMB``.
   
.. figure:: /images/UModeler_PushPullToolHeightAlignment.gif
   :scale: 95 %
   
   Height Aligntment ``CTRL + LMB Drag``  
