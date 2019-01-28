#####################################
Toolbar, Settings and Preference
#####################################

.. figure:: /images/SceneView_For_Toolbar.jpg
   :scale: 80 %
	
   Scene view.
   
The top of the scene view consists of several icon buttons. They are divided into two parts as below.

.. figure:: /images/Toolbar_Left.png
   :scale: 80 %
   
The first part has Vertex/Edge/Polygon/Object tool buttons - These are explained in the other page.

.. figure:: /images/Toolbar_Right.png
   :scale: 80 %

The second part consists of New UModeler object tool, Settings and 3D Cursor. We'll cover only them here.


.. figure:: /images/Icon_Misc_NewUModelerObject.png
   :scale: 100 %
   
   New UModeler Object
   
When you click on this button, a new empty UModeler object will be created in a scene. At first you can fill it with primitives shapes and 2D polygons using the tools in Primitive Shapes group and Drawing group.

.. figure:: /images/Icon_Misc_Cursor.png
   :scale: 100 %
   
   3D Cursor
   
When this is on, 3D cursor is activated and displayed on the scene view. The pivot of roatation and scaling is the 3D cursor position at this time. And the cursor can move along X,Y or Z axis with the move tool over the cursor. If the cursor passes nearby a vertex, it will be snapped to the vertex. If you press ``LMB`` holding ``CTRL`` and ``SHIFT``, the cursor will move to the cursor position at once. If the mouse cursor is over a UModeler mesh then, the 3D cursor will move to a picked position on the mesh.

.. figure:: /images/Icon_Misc_Settings.png
   :scale: 100 %

   Settings
  
Lastly we'll take a look at ``Settings``   
   
.. _seamless-edit:
   
Seamless Edit
 Selects the UModeler object under the mouse cursor every time the mouse moves to edit UModeler objects seamlessly. The object set affected by this mode is decided according to which category is chosen.
 
 - ``Single`` : Only the selected object is a subject to be edited.
 - ``All`` : All the UModeler objects in a scene are subjects to be edited.
 - ``Group`` : All the UModeler objects under the identical root object are subjects to be edited.
 
.. tip::

   | You can disable ``Seamless Edit`` holding ``SHIFT`` while moving the mouse.   
 
Text Based Menu 
 Turns on and off the text based menu. It is same as ``Text Based Menu`` in the popup menu brought up by RMB on the menu panel.

Snap
======
Here are the settings related to grid and rotation snapping.

Enable
 Enables snapping

Popular Grid Size
 Most used grid sizes

Grid Size
 Custom grid size
 
Rotation Snap Size
 Most used rotation snap sizes

Display
========
Here are the settings about displaying information which helps modeling.

Triangulation
 Displays triangulated polygons. They are fed to the renderer in order to be rendered.
  
Status
 Shows the UModeler status in the inspector such as Total selected element count, total polygon count and total triangle count.
 
Commentary
 Displays UModeler commentary at the bottom on the left. You can check what key is pressed and which tool is selected etc through this.
 
Global Overlay
 Displays width, depth and height of the bound box of the selected UModeler mesh. 

Local Overlay
 Displays specific values of the current tool. eg. How long the polygon is pushed or pulled in ``PushPull`` tool
 
----------------------------------------------------------------------------------------------------------------------

.. _AdvancedPreferences:

Preferences
===========

You can set shortcuts and general settings of UModeler in Unity Preferences window to which you can go through ``Edit > Preferences`` in the top menu. 

.. figure:: /images/PreferenceWin.jpg
   :scale: 80 %
	
   UModeler Preferences.
   
Text Based Menu
 Enables the text based menu

Detailed Tooltip
 Enables very detailed tooltip of each tool. If you feel the tooltip occupies much space, you can turn it off.
 
Lightmap by Default
 When this is on, the lighting method of every new created UModeler object will be the lightmap.