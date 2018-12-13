##################
Overview
##################

Introduction
===============

UModeler is a ultimate and intuitive modeling extension that is available on Unity Editor. You can draw 2D shapes on any polygons in easy ways and turn them into 3D shapes intuitively.

Moreover UModeler has also adopted useful features of popular DCC tools like Max and Blender etc to empower you to create complicated and rich mesh assets as well as game levels easily and quickly without any help of the external DCC tools.

----------------------------------------------------------------------------------------------------------------------

Install
=================

.. figure:: /images/UModelerImport2.jpg
   :scale: 95 %
   
Import UModeler in your project after purching it.

.. figure:: /images/UModelerMenu.png
   :scale: 95 %
   
Make sure that ``Tools/UModeler`` menu has been created at the top. If you click on ``New UModeler`` as shown in the upper image, a new game object with UModeler component will be created and you can see the layout looking like the following.
   
----------------------------------------------------------------------------------------------------------------------

Layout
========

.. figure:: /images/UModelerLayout0.jpg
   :scale: 95 %
	
   UModeler Layout
   

``[1]`` Working Area
 Editing meshes. 
 
``[2]`` Toolbar
 Frequently used tools are located here. i.e. ``Vertex/Edge/Polygon Selection/Transform`` tools, ``New UModeler Object``, ``Settings`` and ``3D Cursor`` Tools.
 
``[3]`` UModeler Inspector
 .. figure:: /images/UModelerInspector.jpg
    :scale: 70 %
	
    UModeler Inspector

 Header 
  | ``UModeler Ver 2.xx`` - Opens the About dialog box.  
  | ``Close`` - Disables UModeler for the current object to make the current UModeler object behave and visulized same as the general obejct. It can be enabled again by clicking on Open button which is shown up during the disable status. 
  | ``?`` - Opens the online manual describing what the current tool is and how to use it.
  | ``Search EditBox`` - Searches for a specific tool. This edit box can be activated by pressing ENTER in the scene view.

 Menu part
  There are icons on various UModeler tools. You can switch the menu mode between icon-based and text-based via the popup menu which is brought up by pressing ``RMB``. And it's possible to detach it from the inspector to the separated window.
  
 Properties  part
  The properties and UIs related to the current tool are displayed here. This can also be detached to the separated window via the popup menu. 
 
``[4]`` Gizmo type
 .. figure:: /images/GizmoType.png
    :scale: 95 %   
	
    Selecting a gizmo among ``Translate``, ``Rotate`` and ``Scale``. These buttons are interlocked with the UModeler gizmo type.

``[5]`` Coordinate Frame
 .. figure:: /images/CoordinateFramePivotSetting.png
    :scale: 95 %   
	
    Selecting a coordinate frame of both ``Global`` and ``Local``. These buttons are also interlocked with the UModeler gizmo's frame.
 
``[6]`` UV Editor
 UV Editor can be opened by selecting Tools/UModeler/UV Editor at the top menu or clicking ``Open UV Editor`` button in UV Tool. If you want to know how to use UV editor more, please visit :doc:`here </UVEditor/index>`.
 
----------------------------------------------------------------------------------------------------------------------

User Interface
================

+---------------------------------------+----------------------------------------------------------+
| ``SPACE``                             | Confirms the current action.                             |
+---------------------------------------+----------------------------------------------------------+
| ``ESC``                               | Cancels the current function or Exit the current tool.   |
+---------------------------------------+----------------------------------------------------------+
| ``ENTER``                             | Enables Search Edit Box.                                 |
+---------------------------------------+----------------------------------------------------------+
| ``CTRL + Z``                          | Undo                                                     |
+---------------------------------------+----------------------------------------------------------+
| ``CTRL + Y``                          | Redo                                                     |
+---------------------------------------+----------------------------------------------------------+
| ``W``                                 | Translation Gizmo                                        |
+---------------------------------------+----------------------------------------------------------+
| ``E``                                 | Rotation Gizmo                                           |
+---------------------------------------+----------------------------------------------------------+
| ``R``                                 | Scale Gizmo                                              |
+---------------------------------------+----------------------------------------------------------+
| ``LMB``                               | Selects or moves several elements.                       |
+---------------------------------------+----------------------------------------------------------+
| ``LMB Drag``                          | Selects or moves several elements.                       |
+---------------------------------------+----------------------------------------------------------+
|``SHIFT + LMB`` or ``LMB Drag``        | Special action depending on the current tool             |
+---------------------------------------+----------------------------------------------------------+
|``CTRL + LMB`` or ``LMB Drag``         | Special action depending on the current tool             |
+---------------------------------------+----------------------------------------------------------+

``LMB`` - Left Mouse Button ``CTRL`` - Control Key

----------------------------------------------------------------------------------------------------------------------

Let's get started with a box.
=======================================

1. Select ``Tools``/``UModeler``/``New UModeler`` to create a new UModeler object.
 .. figure:: /images/GettingStarted_0.jpg
    :scale: 95 %   

2. Make sure that a new UModeler object has been created and Box Tool has been selected in the inspector.
 .. figure:: /images/GettingStarted_1.jpg
    :scale: 95 %   

3. Press ``One Click Build`` in the Properties to make sure that a box with 1m X 1m X 1m is created.
 .. figure:: /images/GettingStarted_2.jpg
    :scale: 95 %

	
4. If you want to change the size of the box, type proper values in  Width, Depth and Height fields in the Properties.
5. Click on ``Confirm`` button if you like it.
6. Now you've made the first mesh with UModeler.
 .. figure:: /images/GettingStarted_3.jpg
    :scale: 95 %