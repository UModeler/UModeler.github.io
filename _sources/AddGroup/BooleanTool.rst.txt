.. |Icon_Add_BooleanUnionimage| image:: /images/Icon_Add_BooleanUnion.png
   :scale: 100 %
  
.. |Icon_Add_BooleanSubtract| image:: /images/Icon_Add_BooleanSubtract.png
   :scale: 100 %
   
.. |Icon_Add_BooleanIntersection| image:: /images/Icon_Add_BooleanIntersection.png
   :scale: 100 %

############################################################################################################################################
Boolean Tool |Icon_Add_BooleanUnionimage| |Icon_Add_BooleanSubtract| |Icon_Add_BooleanIntersection| 
############################################################################################################################################

This tool creates a single game object out of two game objects by applying one of the three boolean operations.
   
Steps
-----------

1. Select two game objects with UModeler component.
2. Select one among ``Union``, ``Subtract`` and ``Intersection`` in the menu.
 
.. figure:: /images/UModeler_Boolean_Selection.jpg
   :scale: 95 %

   Two UModeler objects are selected.
   
.. figure:: /images/UModeler_Boolean_Union.jpg
   :scale: 95 %

   Union boolean operation |Icon_Add_BooleanUnionimage|

.. figure:: /images/UModeler_Boolean_Intersection.jpg
   :scale: 95 %

   Intersection boolean operation |Icon_Add_BooleanIntersection|
   
.. figure:: /images/UModeler_Boolean_Subtract.jpg
   :scale: 95 %

   Subtract boolean operation |Icon_Add_BooleanSubtract|
   
.. note::

  Boolean Tool is not perfect to all meshes. If you find some broken parts after applying booelan operations, you can repair them using the following tools.
  
  | Bridge Tool    
  | Eraser Tool  
  | Remove Double Tool  
  | Collapse Tool