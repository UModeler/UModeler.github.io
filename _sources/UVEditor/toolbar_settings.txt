********
Toolbar
********

Transform Tools
=========================  
  
.. figure:: /images/UV_ToolBar_Gizmos.png 
   :scale: 100 %
   
   From left to right ``Move Tool``, ``Rotation Tool``, ``Scale Tool`` and ``Rectangle Tool``

If elements like UV, Edge or Polygon are selected, the correspoinding gizmo of the current transform tool is displayed at the center of the elements. You can trasnform the selected elements using these gizmos.  

.. note::

 ``Separate Transfoming`` - Usually transforming elements affects the adjacent polygons. It means that all overlapped UVs will be transformed together. However holding ``SHIFT`` will make you transform elements separatelly. Even though several UVs occupied the same position, only one UV will be affected.

.. figure:: /images/UModeler_UVEditor_Transform_MoveTool.jpg
   :scale: 100 %
   
   Move Gizmo
   
.. figure:: /images/UModeler_UVEditor_Transform_RotationTool.jpg
   :scale: 100 %
   
   Rotation Gizmo

.. figure:: /images/UModeler_UVEditor_Transform_ScaleTool.jpg
   :scale: 100 %
   
   Scale Gizmo
   
.. figure:: /images/UModeler_UVEditor_Transform_RectangleTool.jpg
   :scale: 100 %
   
   Rectangle Gizmo - You can scale the selected elements by dragging the small blue boxes on the rectangle.
   
Element Tools
=========================

.. figure:: /images/UV_ToolBar_ElementTools.png 
   :scale: 100 %
   
   ``UV``, ``Edge``, ``Polygon`` and ``UV Island`` Tool from left to right.

.. figure:: /images/UModeler_UVEditor_ElementTools_Vertex.jpg
   :scale: 100 %
   
   UV - A point. Two edges meet at one UV.

.. figure:: /images/UModeler_UVEditor_ElementTools_Edge.jpg
   :scale: 100 %
   
   Edge - Two connected UVs.

.. figure:: /images/UModeler_UVEditor_ElementTools_Polygon.jpg
   :scale: 100 %
   
   Polygon - A flat closed shape which consists of n-UVs and n-edges

.. figure:: /images/UModeler_UVEditor_ElementTools_UVIsland.jpg
   :scale: 100 %
   
   UV Island - A set of polygons

.. note::
   ``Overlapped Edges`` - An edge in uv space can be overlapped the other edge in 3D space so it will be helpful to display the overlapped edges of the selected edges to make it easiser to edit UVs. Therefore The overlapped edges are displayed as green edges.   
   
Settings and Cursor
=========================

.. figure:: /images/UV_ToolBar_SettingsCursor.png 
   :scale: 100 %
   
   ``Settings`` and ``Cursor``

Settings
----------

.. figure:: /images/UModeler_UVEditor_UVSettings.jpg
   :scale: 100 %
   
Enable Snap
   If this is on, UV transform will be affectad by ``Grid Snap Size`` and ``Rotation Snap Size`` specified below. With ``Snap`` enabled you can move or rotate the selected elements by a specified unit. 
   
Grid Snap Size
   This defines how many size the UVs move whenever they are dragged or translated by the gizmo.
Rotation Snap Size
   This defines how many degree the UVs are rotated whenever a mouse is dragged on the rotation gizmo.
Show Island Boundary
   Displays UV Island boundary rectangles.
Fill Polygons
   Fills UV polygons with transparent blue.
Show Axes
   Shows the principal axes.
Show Texture
   Displays the current texture on the working area.
Show All Polygons
	Displays all polygons no matter what materials they have.
Material List
   A material list of the selected object.	
  
   
Cursor
--------

.. figure:: /images/UModeler_UVEdtor_Cursor.jpg
   :scale: 100 %
   
   Displays ``Cross Cursor``, which is used as a pivot of transformation, flip, 90 rotation etc. It can be moved by dragging. While moving it is snapped to a close point. 