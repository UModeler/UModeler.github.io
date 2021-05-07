############
Menu
############

.. figure:: /images/new_menu_items2.png
   :scale: 80 %

You can see a new menu called ``Tools`` at the top of Unity Editor after UModeler is installed. 

About
===============
Opens ``About`` window.

.. figure:: /images/AboutDialog.jpg
   :scale: 80 %

---------------------------------------------------------------------------------------------------------------------------------

New UModeler
========================================
Creates a game object with a ``UModeler`` component and a ``Mesh Collider`` component.

---------------------------------------------------------------------------------------------------------------------------------

UModeler Window
========================================
Opens up the UModeler menu window. The menu in the inspector won't be displayed after it is opened up.

.. figure:: /images/MenuWindow.jpg
   :scale: 80 %
   
---------------------------------------------------------------------------------------------------------------------------------

UV Editor
========================================
Opens up the UV Editor.

.. figure:: /images/UVEditor.jpg
   :scale: 80 %   

.. note::

  ``UV Editor`` isn't available in the Lite version.

---------------------------------------------------------------------------------------------------------------------------------

UModelerize
========================================
Converts the selected static mesh objects or UModeler Lite objects to UModeler objects so that they can be edited using UModeler tools.

---------------------------------------------------------------------------------------------------------------------------------
   
UModelerize Hierarchically
========================================
Converted the selected objects and all their children objects to UModeler objects. 

.. note::

  ``UModelerize`` and ``UModelerize Hierarchically`` aren't available in the Lite version.

---------------------------------------------------------------------------------------------------------------------------------

Export as .Obj
========================================
Exports the selected UModeler objects as one .obj file. This menu can be used when the selection includes a non-UModeler object.

Triangulate
========================================
Divides all polygons into triangles.

.. figure:: /images/Before_After_Triangulation.jpg
   :scale: 95 %

.. note::

  ``Triangulate`` isn't available in the Lite version.   

---------------------------------------------------------------------------------------------------------------------------------

Diagnose All UModeler Objects
========================================
Diagnose All UModeler Objects in the current scene to find corrupt or invalid UModeler meshes.

Repair All Corrupt UModeler Objects
========================================
Repaired all corrupt UModeler objects so that any errors won't happen.

.. note::

  There are two types of abnormal UModeler objects which cause lightmap issues, UV2 issues, visual defects or performance issues etc.
   ``Corrupt UModeler Object`` refer to UModeler objects with corrupt polygons. Cases of corrupt polygons are as follows.
    - Some indices are out of vertex number.
   ``Invalid UModeler Object`` has invalid polygons. Cases of invalid polygons are as follows:
    - A polygon's area is 0.
    - There are intersected edges.
    - There are an edge whose two vertices positions are identical.
    - There are holes outside the area of the polygon.
    - The whole vertex number is 1.

.. note::

  ``Diagnose All`` and ``Repair All`` aren't available in the Lite version.       

---------------------------------------------------------------------------------------------------------------------------------

Refresh All
========================================
Refreshes every resource of all UModeler objects in the current scene. This doesn't change and remove any data. It might resolve a broken mesh issue or light map problems etc.

----------------------------------------------------------------------------------------------------------------------------------

Preferences
==============
Opens the Preferences window.
   
See :ref:`AdvancedPreferences` to get more info.

.. note::

  ``Preferences`` window isn't available in the Lite version.   