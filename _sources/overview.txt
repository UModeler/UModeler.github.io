##################
Overview
##################

Introduction
===============

UModeler is a ultimate and intuitive modeling extension that is available on Unity Editor. You can draw 2D shapes on any polygons in easy ways and turn them into 3D shapes intuitively.

Moreover UModeler has also adopted useful features of popular DCC tools like Max and Blender etc to empower you to create complicated and rich mesh assets as well as game levels easily and quickly without any help of the external DCC tools.

----------------------------------------------------------------------------------------------------------------------

Layout
========

.. figure:: /images/UModeler_Layout.png
   :scale: 95 %
	
   UModeler Layout   

``[1]`` Working Area
 Editing meshes. 
 
``[2]`` UModeler Inspector

 .. figure:: /images/UModeler_Inspector_HeaderSettings.jpg
    :scale: 45 %

    UModeler Inspector - ``Header`` and ``Settings`` 

 Header 
  | ``UModeler Ver 2.xx`` - Opens the About dialog box.  
  | ``Close`` - Disables UModeler for the current object.
 
 .. figure:: /images/UModeler_OpenCloseButtons.gif
    :scale: 95 %

    Closes and Opens UModeler component. With Closing state UModeler's behaviour and visualization are like the normal game object. You can open UModeler tool whenever you want to edit it.
 
 Settings
  Settings regarding ``Display``, ``Gizmo`` and ``Snap``. 
  
 .. figure:: /images/UModeler_Inspector_Tools.jpg
    :scale: 45 %

    UModeler Inspector - ``Search EditBox`` and ``Tools``   

 Search EditBox
  Search for a specific tool. This edit box can be activated by pressing ``ENTER`` in the scene view or inspector.  
  
 .. figure:: /images/UModeler_SearchEditBox.gif
    :scale: 95 %

    Search Edit Box demo

 Tools and Properties
  A set of Tools and Properties
 
``[3]`` Status HUD
 Information of UModeler mesh

``[4]`` Input Viewer
 Viewing which keyboard and mouse buttons are pressed.
 
``[5]`` Gizmos
 Selecting a gizmo among ``Translate``, ``Rotate`` and ``Scale``. 

``[6]`` Coordinate Frame
 Selecting a coordinate frame of both ``Global`` and ``Local``.
 
``[7]`` UV Editor
 The area for editing UVs.
 
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