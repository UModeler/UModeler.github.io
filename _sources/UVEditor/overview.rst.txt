*************
Overview
*************
There are two ways of running UVEditor as follows.

 • Select ``Tools > UModeler > Open UVEditor`` in the upper menu or 
 • Click on ``Open UVEditor`` in ``Surface`` group on the UModeler inspector.

 
 .. figure:: /images/UModeler_UVEditor_Overview_0.jpg

    UVEditor with a UV map

The UVEditor looks like the upper image and consists of three areas. 

 1) ``Toolbar`` - Most frequently used tools. 4 gizmos (Move, Rotate, Scale, Box), 4 elements (UV, Edge, Polygon, UV Island) and, ``Settings`` and ``Cursor`` icons from left to right.
 2) ``Menu`` - All tools' icons are located here.
 3) ``Property`` - Properties of the current tool.
 4) ``Working Area`` - This is used for viewing and editing the UVs.
 
Automatic UV and Manual UV
============================
The polygons created in UModeler basically have UVs, which have tiling charactericstic, generated automatically based on position and normal of each vertex. From UModeler 2.0 those UVs can be unwrapped and edited manually using UVEditor. Both types of UVs can exist in one mesh at the same time. 
 
.. _autolayout: 

Auto Layout
===========================
``LMB Double click`` on a polygon to automatically unwrap and stitch it. This is a very handy way of unwrapping polygons.

 .. figure:: /images/UModeler_AutoLayout.gif

    Auto Layout
 
Icon or Text based menu
===========================
When you press ``RMB``, the pop up menu will be brought up as below. You can switch the menu between icon-based and text-based there.

 .. figure:: /images/UModeler_UVEditor_Overview_1.jpg
    :scale: 95 %
 
Keyboard
==========
+---------------------------+---------------------+
| ``W``                     | Translate Gizmo     |
+---------------------------+---------------------+
| ``E``                     | Rotate Gizmo        |
+---------------------------+---------------------+
| ``R``                     | Scale Gizmo         |
+---------------------------+---------------------+
| ``T``                     | Rect Gizmo          |
+---------------------------+---------------------+
|``CTRL+Z``                 | Undo                |
+---------------------------+---------------------+
|``CTRL+Y``                 | Redo                |
+---------------------------+---------------------+
|Holding ``SHIFT+CTRL``     | Separate Transform  |
+---------------------------+---------------------+
|Holding ``CTRL``           | Continuous Selection|
+---------------------------+---------------------+
|Holding ``Alt`` or ``Cmd`` | Camera panning      |
+---------------------------+---------------------+

 .. |Icon_UVEditor_Unwrap_PlaneViewUnwrap| image:: /images/Icon_UVEditor_Unwrap_PlaneViewUnwrap.png
   :scale: 100 %
   
Getting Started
==================

1. .. figure:: /images/UModeler_UVEditor_GettingStarted_0.jpg

    Create a box using ``Box Tool``	

2. .. figure:: /images/UModeler_UVEditor_GettingStarted_1.jpg

    Go to ``Tools > UModeler > UV Editor`` at the top menu of the editor or, select ``UV Tool`` and press ``UV Editor`` button.

3. .. figure:: /images/UModeler_UVEditor_GettingStarted_2.jpg
 
    Select three polygons visible from the camera.

4. .. figure:: /images/UModeler_UVEditor_GettingStarted_3.jpg
 
    Click on ``Plane Unwrap Tool`` (|Icon_UVEditor_Unwrap_PlaneViewUnwrap|) in UV Editor.

5. .. figure:: /images/UModeler_UVEditor_GettingStarted_4.jpg
 
    Press ``Unwrap`` button in ``Properties`` window. Then you can check out that the selected polygons are unwrapped.
	
6. .. figure:: /images/UModeler_UVEditor_GettingStarted_5.jpg
 
    Select ``Move Tool`` and ``Polygon Tool`` on the toolbar and move a unwrapped polygon using the gizmo in UV Editor.