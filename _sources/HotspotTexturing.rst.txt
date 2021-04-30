###################
Hotspot Texturing
###################

.. figure:: /images/HotspotTexturing_UrbanBuildings.png

Introduction
===============

``Hotspot Texturing`` is a new feature added to the toolkit that makes UV unwrapping easier and faster. When
you define UV layouts using the hotspot layout editor, UVs of each polygon can be placed according to the predefined layouts automatically.

-----------------------------------------------------------------------------------------------------------------------------------------------------------

Features
==============

- Built-in ``Hotspot Layout Editor`` made from the UV Editor framework. 
- A triangle layout as well as a rectangle is supported
- Auto mode called ``Auto Hotpost`` which enables UVs to be applied automatically every time a polygon is modified.
- ``Padding`` parameter to gives consistant gap between a hotspot layout and assigned UVs
- Applies a selected hotspot layout to UVs by clicking on ``Apply Selected Hotspot`` button.

----------------------------------------------------------------------------------------------------------------------

Hotspot Layout tool
========================================

.. figure:: /images/Hotspot_Texturing_tool_location.jpg
   :scale: 50 %

   ``Hotspot Layout`` tool 

``Hotspot Layout`` tool is for hotspot texturing. It is located in the ``Surface`` group.

.. figure:: /images/hotspottexturing_properties_window.png
   :scale: 60 %

   ``Hotspot Layout`` tool properties

1.Select Only Visible
 If on, only visible polygons can be selected in the scene view.

2.Auto Hotspot
 If on, hotspot texturing is applied to every polygon whose is involved in being edited at realtime.

3.Hotspot Group
 If on, adjacent polygons are placed in one layout.

4.Hotspot Padding
 If enabled, UVs are away by this pixel value from the layout

 .. figure:: /images/hotspot_texturing_border.png
    :scale: 45 %

    ``Hotspot Padding`` parameter

5.Hotspot Scale

 | The ratio of the hotspot layout to the size of the polygon in the world.
 | In case of 1, the size of 1.0 in the hotspot layout and 1.0 in the world is the same.
 | In case of 2, 0.5 of the hotspot layout will be equal to the 1.0 size in the world.

 .. figure:: /images/hotspotScale0.png
    :scale: 40 %

 For example, when the texture and hotspot layout are configured as above, and the world size is set to 1.0, 0.5, 0.25, 0.125, respectively, and a cube is created.

 .. figure:: /images/hotspotScale1.png
    :scale: 40 %

 You can see the UVs are placed differently depending on the hotspot scale value. If the hotspot scale is 1, you can see that a 1.0-sized cube is placed in the UVs according to the 1.0-sized layout.

 Since the 0.5-size cube is also 1/2 of 1.0 to fit the size, the UVs have been placed according to the 1/2-size layout in the hotspot layout editor.

 If the hotspot scale is 2, a layout of 1/2 size is applied to a cube of 1.0 size, and accordingly, you can see that UV is placed on other sized models as well.

6.Hotspot Layout
 Hotspot layout file. The format is .asset. This layout file can be applied to several objects.

7.New Hotspot Layout/Open Layout Editor
 If a hotspot layout file isn't set, ``New Hotspot Layout`` button is enabled so that you can create a new layout file.  
 If a hotspot layout file is set, ``UV Layout Editor`` will be opened.

8.Apply Hotspot
 If enabled, the hotspot texturing will be applied to the selected polygons. The selected polygons' UV coordinates will be place in the most appropriate layout.

9.Apply Selected Hotspot
 If enabled, the selected polygons' UV coordinates will be placed in the selected hotspot layout.

----------------------------------------------------------------------------------------------------------------------

Hotspot Layout Editor
===========================

Defines layouts for hotspot texturing. The usage is somewhat similar to UV Editor.

.. figure:: /images/HotspotLayout_Editor.png
  :scale: 60 %

  ``Hotspot Layout Editor`` 

1.Move
 Moves the selected layout polygon or UV

2.Rectangle
 Resizes the selected layout polygon or UV using ``Rectangle`` gizmo.

3.UV Tool
 Selects each UV and transform it using gizmos.

4.Polygon Tool
 Selects each layout polygon and transform it using gizmos.

5.Texture Slot
 Opens a texture displayed in the editor. This texture is just a guide.

6.Open Active Hotspot Layout
 Opens a hotspot layout file of the current object.

7.Hotspot Layout Slot
 Hotspot layout file (.asset).

8.Grid Snap
 Grid snap size list.

9.Rectangle Tool
 You can use this to make a rectangle layout.

10.Right Angled Triangle Tool
 You can use this to make a right angled triangle layout.

11.Icosceles Angled Triangle Tool
 You can use this to make an icosceles angled triangle layout.

12.Delete Tool
 You can remove the selected layout. The shortcut is ``Del`` key.

13.Rotate Pos90 Tool
 Rotates the selected layout by positive 90 degrees.

14.Rotate Neg90 Tool
 Rotates the selected layout by negative 90 degrees.

15.Flip Horizontal Tool
 Flips the selected layout horizontally.

16.Flip Vertical Tool
 Flips the selected layout vertically.

----------------------------------------------------------------------------------------------------------------------

How to Use
============

Using ``Auto Hotspot``
------------------------

.. figure:: /images/UsingAutoHotspot.png	
   :scale: 40 %

   ``Hotspot Layout`` tool properties


1. At first you should select a UModeler mesh or create it.
2. Enter ``Hotspot Layout`` tool
3. You should create a new Hotspot layout file by pressing ``New Hotspot Layout`` or open the existing layout file via ``Hotspot Layout`` slot.
4. Now click on ``Open Layout Editor`` to opens the Layout Editor

.. figure:: /images/hotspotlayout_editor_autohotspot_0.png	
   :scale: 50 %

   ``Hotspot Layout Editor``

5. Selects a texture via the texture slot at the top of the editor. 
 
.. figure:: /images/hotspot_texture_editor_texslot.png
   :scale: 70 %

   Texture slot.

6. Now a guide texture is displayed. Then select ``Rectangle Tool`` on the right and drag ``LMB`` to create a rectangle layout.

.. figure:: /images/rectangle_tool_menu.png
   :scale: 60 %

   Rectangle Tool icon.

.. figure:: /images/DrawRectangleLayout.png
   :scale: 60 %

   Draws a rectangle layout.

.. figure:: /images/hotspot_guidtexture.png
   :scale: 70 %

   A loaded texture in the editor. This texture is just a guide.

.. figure:: /images/complete_layout.png
   :scale: 70 %

   All layouts are defined.

7. Returning to ``Hotspot Layout`` properties toggle on ``Auto Hotspot``

.. figure:: /images/ToggleOnAutoHotspot.png
   :scale: 50 %

   Toggle on ``Auto Hotspot``

8. You can check out that UV coordinates are set automatically according to the predefined layouts in the Hotspot Layout Editor.
 
.. figure:: /images/autohotspot_layout.png
   :scale: 45 %

   UV work will get easier than ever :)


Using ``Hotspot Group``
-------------------------

You can apply hotspot texturing to the selected adjacent textures as a group using ``Hotspot Group``

This is an example mesh.

.. figure:: /images/hotspot_group0.png
   :scale: 45 %

   Selected adjacent polygons

1. Select the polygons as shown below.

.. figure:: /images/hotspot_group1.png
   :scale: 45 %

   Selected adjacent polygons

2. Toggle on ``Hotspot Group`` and click on ``Apply Hotspot``

.. figure:: /images/hotspot_group2.png
   :scale: 45 %

   ``Hotspot Group`` toggle and ``Apply Hotspot`` button

3. You can see that the selected polygons' UV coordinates are placed in one layout as shown below.

.. figure:: /images/hotspot_group_5.png
   :scale: 60 %

   Unwrapped UV coordinates according to the predefined layout.

.. figure:: /images/hotspot_group6.png
   :scale: 55 %

   Wow!


Using ``Apply Selected Hotspot``
----------------------------------

``Apply Selected Hotspot`` assigns the selected polygons in the selected layout in ``Hotspot Layout Editor``.

1. Select polygons.

.. figure:: /images/applyselectedhotspot0.png
   :scale: 55 %  

2. Select a layout in which UV coordinates are placed in the ``Hotspot Layout Editor``

.. figure:: /images/applyselectedhotspot1.png
   :scale: 55 %

3. Click on ``Apply Selected Hotspot``

.. figure:: /images/applyselectedhotspot2.png
   :scale: 80 %

4. Now you can see that UVs of the selected polygons are set to the selected layout.

.. figure:: /images/applyselectedhotspot3.png
   :scale: 80 %