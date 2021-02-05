##################
UModeler Lite
##################

.. note::

 The first verion of UModeler Lite will be available soon! 

.. figure:: /images/lite_titleimage.png

Introduction
===============

``UModeler Lite`` includes core functionality of the full version so it will be enough for you to experience the power and conveience of UModeler.

----------------------------------------------------------------------------------------------------------------------

Install
=================
  
Import ``UModeler Lite`` package in your project after getting it from the asset store.
   
Make sure that ``Tools/UModeler Lite`` menu has been created at the top. If you click on ``New UModeler`` as shown in the upper image, a new game object with UModeler component will be created and you can see the layout looking like the following.
   
----------------------------------------------------------------------------------------------------------------------

Layout
========

.. figure:: /images/UModelerLite_Layout.png
	
 ``UModeler Lite`` Layout
   

``[1]`` Working Area
 Editing meshes. 
 
``[2]`` Toolbar
 Tools used frequently are located here. i.e. ``Vertex/Edge/Polygon Selection/Transform`` tools, ``New UModeler Object``, ``Settings`` and ``3D Cursor`` Tools. However, ``3D Cursor`` cannot be used in the Lite version.
 
``[3]`` UModeler Inspector
 .. figure:: /images/UModelerLite_Inspector.png
    :scale: 60 %
	
    The Inspector window of ``UModeler Lite``
 
 Menu part
  There are icons on various UModeler tools. Tools marked with black icons are only available in the full version.
  
 Properties  part
  The properties and GUIs related to the current tool are displayed here.  
 
``[4]`` Gizmo type
 .. figure:: /images/GizmoType.png
    :scale: 95 %   
	
    Selecting a gizmo among ``Translate``, ``Rotate`` and ``Scale``. These buttons are interlocked with the UModeler gizmo type.

``[5]`` Coordinate Frame
 .. figure:: /images/CoordinateFramePivotSetting.png
    :scale: 95 %   
	
    Selecting a coordinate frame of both ``Global`` and ``Local``. These buttons are also interlocked with the UModeler gizmo's frame. 
 
----------------------------------------------------------------------------------------------------------------------

User Interface
================

+---------------------------------------+---------------------------------------------------------------+
| ``SPACE``                             | Confirms the current action.                                  |
+---------------------------------------+---------------------------------------------------------------+
| ``ESC``                               | Cancels the current function or Exit the current tool.        |
+---------------------------------------+---------------------------------------------------------------+
| ``CTRL + Z``                          | Undo                                                          |
+---------------------------------------+---------------------------------------------------------------+
| ``CTRL + Y``                          | Redo                                                          |
+---------------------------------------+---------------------------------------------------------------+
| ``W``                                 | Translation Gizmo                                             |
+---------------------------------------+---------------------------------------------------------------+
| ``E``                                 | Rotation Gizmo                                                |
+---------------------------------------+---------------------------------------------------------------+
| ``R``                                 | Scale Gizmo                                                   |
+---------------------------------------+---------------------------------------------------------------+
| ``LMB``                               | Selects or moves several elements.                            |
+---------------------------------------+---------------------------------------------------------------+
| ``LMB Drag``                          | Selects or moves several elements.                            |
+---------------------------------------+---------------------------------------------------------------+
|``SHIFT + LMB`` or ``LMB Drag``        | Special action depending on the current tool                  |
+---------------------------------------+---------------------------------------------------------------+
|``CTRL + LMB`` or ``LMB Drag``         | Special action depending on the current tool                  |
+---------------------------------------+---------------------------------------------------------------+

``LMB`` - Left Mouse Button ``CTRL`` - Control Key

----------------------------------------------------------------------------------------------------------------------

MeshFilter Component 
===========================

There are new UIs in the MeshFilter component to save a mesh as .asset file.
The asset file is a kind of a reference to geometry data. It prevents mesh data from being lost in the prefab.

When you create a UModeler object at first, the mesh doesn't exist yet.

 .. figure:: /images/MeshFilterComonent(1).jpg
    :scale: 95 %
	
The new asset file named after the mesh name is created after you click on Save button.

 .. figure:: /images/MeshFilterComonent(2).jpg
    :scale: 95 %
	
With ``Save As`` button, you can rename it or save it in a different folder. Once a mesh is saved as .asset the mesh data in the asset file will be synchronized with the UModeler mesh.

----------------------------------------------------------------------------------------------------------------------

Available Tools
=======================================

The available tools listed below in the Lite version are core ones for 3D modeling so we're sure that with just following tools you can create great levels and artworks.

.. toctree::
   :maxdepth: 1

   Vertex, Edge and Polygons Tools <ElementGroup>
   Loop Select Tool <SelectionGroup/loopselectiontool>
   Line Tool <DrawingGroup/linetool>
   Rectangle Tool <DrawingGroup/rectangletool>
   Box Tool <PrimitiveShapesGroup/BoxTool>
   Cylinder Tool <PrimitiveShapesGroup/CylinderTool>
   PushPull Tool <AddGroup/PushPullTool>
   LoopSlice Tool <AddGroup/LoopSliceTool>
   Bridge Tool <AddGroup/BridgeTool>
   Eraser Tool <RemoveGroup/EraserTool>
   Combine Tool <RemoveGroup/CombineTool>
   Detach Tool <RemoveGroup/DetachTool>
   Flip Tool <TweakGroup/FlipTool>
   Material Tool <SurfaceGroup/MaterialTool>
   UV Tool <SurfaceGroup/UVTool>
   Local Settings Tool <MiscGroup/LocalSettingsTool>
   New UModeler Tool <MiscGroup/NewUModelerTool>

----------------------------------------------------------------------------------------------------------------------   

Features difference between Lite ver and Full ver
========================================================================

 .. figure:: /images/Lite_FullVersion_FeatureDifference.png
    :scale: 50 %

----------------------------------------------------------------------------------------------------------------------    

Tools difference between Lite ver and Full ver
========================================================================

 .. figure:: /images/Lite_FullVersion_Icons_Difference.png
    :scale: 65 %

----------------------------------------------------------------------------------------------------------------------

Let's get started with UModeler Lite
=========================================
1. To get started with UModeler Light you should create a ``UModeler Lite`` object at first through ``Tools`` > ``UModeler Lite`` > ``New UModeler``

.. figure:: /images/UModelerLite_GettingStarted1.png
 :scale: 35 %


2. Select ``Box Tool`` in the inspector after making sure that a new ``UModeler Lite`` object is created in the hierachy window.

.. figure:: /images/UModelerLite_GettingStarted2.png
 :scale: 35 %

3. Create a box whose size is 1m x 1m x 1m by clicking on ``One-Click Build`` button.

.. figure:: /images/UModelerLite_GettingStarted3.png
 :scale: 35 %

4. You can adjust width, depth and height by entering number in the Properties in the inspector.
If you think the box looks as you wished, click on ``Confirm`` button. 
Now you are ready to make a fantastic world with ``UModeler Lite`` in Unity.

.. figure:: /images/UModelerLite_GettingStarted4.png
 :scale: 35 %

----------------------------------------------------------------------------------------------------------------------

Artworks made with UModeler Lite
=========================================

.. figure:: /images/lite_screenshot4.png
 :scale: 35 %

 Level Design

.. figure:: /images/lite_screenshot3.png
 :scale: 35 %

 3D Modeling

.. figure:: /images/lite_screenhot1.png
 :scale: 35 % 

 VFX

.. figure:: /images/lite_screenshot0.png
 :scale: 35 %

 Concept Design