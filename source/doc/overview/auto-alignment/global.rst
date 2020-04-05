Global Space
============

Using an auto-alignment is easy as selecting the **Align** tool and **left clicking** over some arrow of a gizmo.

To do this now, just select some objects with volume in your scene, you may now notice that there are some **white** dots around the Active object.
Those are the face centers of the bound box that surround the object, and they provide a base point where the alignment will occur.

.. figure:: /images/2.8/auto_align_start.jpg
   :align: center

   The initial alignment. With 2 objects selected, white and black dots appear.

The dots are **white** when they refer to the **Active** object, and **black** when they refer to your current **Selection** of objects.
The black dots will not appear when you have only one object selected.

When the mouse cursor is close to some of the dots, the gizmo with the axes appear, along with the bound box representing the considered objects, also in **white** for the **Active** object and **black** for your current **Selection** of objects.

Now you will be able to point an arrow in the gizmo and do **left click** to select its predetermined alignment.
This action replaces your current selection of origin point, projection plane, direction and local/global space.

Confirm the selected alignment with **Enter/Return** or by pressing the **Align Objects** button in the Sidebar (**N**).

.. figure:: /images/2.8/auto_align_active_preview.jpg
   :align: center

   Clicking over one of the white dot gizmos. Hovering the cursor shows the associated bound box.

.. figure:: /images/2.8/auto_align_active_aligned.jpg
   :align: center
   
   Pressing Enter/Return aligns the objects according to the Active object.

.. figure:: /images/2.8/auto_align_selected_preview.jpg
   :align: center
   
   Clicking over one of the black dot gizmos. Hovering the cursor shows the associated bound box.

.. figure:: /images/2.8/auto_align_selected_aligned.jpg
   :align: center
   
   Pressing Enter/Return aligns the objects according to the Selected objects.

