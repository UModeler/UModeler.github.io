############################
UModeler 2.0
############################

 .. figure:: /images/UModeler_Banner.png

Version 2.0
===============

Improvements & Features
--------------------------
 
 - UV Editor has been added. See :ref:`uveditor_label`
 - ``Properties`` in the inspector is displayed under the group of the selected tool.
 - Added the clone of the selected polygons.
 - ``FreezeXForm Tool`` - Renamed to ``Bake Transform`` and divided it into Scale and Rotation.   
 - Added generating Lightmap UVs in ``Local Settings Tool`` under ``Misc`` group in the inspector.
 - ``Arrange UV Islands`` menu item has been added in UModeler tool menu. 
 - Made a new UModeler game object created under the parent object when clicking on "Game Object" or "Collider Object" button. 
 - ``Grid Size`` field has been added to ``Settings/Snap`` to make it possible to specify any grid size. 
 - ``Mirror Tool`` - Now you can move the mirror plane by ``LMB Drag`` over the arrow of the mirror plane.
 - ``Flip Tool`` has been added in ``Tweak`` group.
 - ``Align Tool`` has been added in ``Tweak`` group.
 - ``UV Tool`` - Added moving UVs by pressing Up or Down arrow keys holding CTRL.
 - ``Combine Tool`` - Pressing ``SPACE`` will combine the selected vertices in ``Combine Tool``.
 - ``Vertex/Edge/Polygon Tool`` - 1D Snapping has been added. It works by moving a cursor to another vertex holding ``CTRL`` while dragging the translation gizmo.
 - ``Vertex/Edge/Polygon Tool`` - ``Insert Vertex`` property has been added.

Fixes & Tweaks
----------------

 - Tweak - ``PushPull Tool`` : Renamed ``Draw Edges`` property to ``Continuous``.
 - Tweak - ``Multiple PushPull`` button has been added. see :ref:`pushpull_tool_label` 
 - Tweak - ``Cut Tool`` : Made Cutting direction flipped by pressing ``SPACE`` while ``LMB`` Dragging
 - Tweak - ``Backface Tool`` : Renamed to ``Local Settings``
 - Tweak - ``Copy Tool`` : Renamed to ``Duplicate Tool``
 - Tweak - ``Game Object`` and ``Collider Object`` buttons have been moved to ``Misc`` group.
 - Bugfix - Not displaying triangulation result has been fixed.
 - Bugfix - Spotty lightmap bug has been fixed.
  