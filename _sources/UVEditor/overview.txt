*************
Overview
*************
 | There are two ways of running UVEditor as follows.
 |
 |  • Select ``Tools > UModeler > Open UVEditor`` in the upper menu or 
 |  • Click on ``Open UVEditor`` in ``Surface`` group on the UModeler inspector.
 |
 .. figure:: /images/UVEditor_Overview.png 
    :scale: 55 %

    UVEditor with a UV map

 | The UVEditor looks like the upper image and consists of three areas. 
 |
 |  • Working Area - This is used for viewing and editing the UVs.
 |  • Toolbar - This is located on the top of the window, which used for choosing gizmo type.
 |  • Inspector - Various tools and settings necessary to unwrap and edit.
 
Automatic UV and Manual UV
=========================
 | The polygons created in UModeler basically have UVs, which have tiling charactericstic, generated automatically based on position and normal of each vertex. From UModeler 2.0 those UVs can be unwrapped and edited manually using UVEditor. Both types of UVs can exist in one mesh at the same time. 
 
Keyboard
==========
+-----------------+---------------------+
| ``W``           | Translate Gizmo     |
+-----------------+---------------------+
| ``E``           | Rotate Gizmo        |
+-----------------+---------------------+
| ``R``           | Scale Gizmo         |
+-----------------+---------------------+
| ``T``           | Rect Gizmo          |
+-----------------+---------------------+
|``CTRL+Z``       | Undo                |
+-----------------+---------------------+
|``CTRL+Y``       | Redo                |
+-----------------+---------------------+
|Holding ``SHIFT``| Separate Transform  |
+-----------------+---------------------+
|Holding ``CTRL`` | Continuous Selection|
+-----------------+---------------------+

Getting Started
==================

 .. figure:: /images/UVEditor_GettingStarted.gif
    :scale: 55 %
 
    Unwrapping the selected polygons and basic demo to show how to edit UVs

 | The process to get started on using UVEditor is as follows.
 |
 | • Open UVEditor by clicking on ``Open UVEditor`` in the inspector of UModeler.
 | • Select several polygons in the scene view.
 | • Select ``Plane/View`` or ``Cube`` button on the inspector in UV Editor.
 | • Click on ``Unwrap`` button in the property group.
 | • Now you can select Vertex/Edge/Polygon in UVEditor and edit them.

