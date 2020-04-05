Global Space
============

When holding the **Shift** key pressed in the 3D View, you access the **Plane selection mode**.
This mode allows you to select a plane from common places like the **bounding boxes** of objects, the **location** of objects, the origin of the **world**, the **cursor** or any **other object** that you may have defined as **Plane target**.

To select the plane interactively, hold the **Shift** key while you move the mouse cursor.
Below it, a small rounded box with a legend appears, to let you know what selection mode you are in. In this case, it shows the word ‘Plane’.

.. figure:: /images/2.8/plane_selection_start.jpg
   :align: center
   
   While you hold the key, you can see all the available rounded points from where you can select *the Plane*.


There are three different key points that you may select in this mode:

* **White** rounded points in the corners of the active object will set a plane that follows the **Active** object’s bound box.
* **Black** rounded points in the corners of all selected objects will set a plane that follows the bound box of your current **Selection** of objects.
* **Red**, **green** and **blue** colored points belong to a key point such as the **location** of the Active object (its origin pivot point), the origin of the **world** or the **cursor**. The three colored points form a triad of crossed axes that relate to the same location.

When you pass close to a selectable point, it highlights in **yellow**, indicating that you can select it.
Along with the point, a **colored line** will be drawn, this is the **normal** of the Plane, indicating the axis that will be taken.

The bound box also highlights when you are close to one of its points, to help you understand what kind of plane are you selecting.
The bound box is drawn **white** when referring to the **Active** object, and **black** when referring to your current **Selection** of objects.

The colors of the normal lines are codified, meaning, **light red** as the X axis Plane, **light green** as the Y axis Plane, and **light blue** as the Z axis Plane.

If you are over a clickable point and do **left click** while you still hold the **Shift** key, the Plane is selected.
If you check the **Plane** subpanel in the Sidebar (**N**), you can see that your actions get reflected there, from where you can change the settings at any time and select another **Plane**, **Axis** and **Depth**.

.. figure:: /images/2.8/plane_selection_active.jpg
   :align: center
   
   Selecting the global Y axis Plane from the Active object.

.. figure:: /images/2.8/plane_selection_selection.jpg
   :align: center
   
   Selecting the global Y axis Plane from the current Selection of objects.

.. figure:: /images/2.8/plane_selection_cursor.jpg
   :align: center
   
   Selecting the global Z axis Plane from the cursor location.
   You can see the other key points that can be selected:
   the origin of the world at the left and the location of the Active object at the right.

|

To show the bound box used to obtain the Plane, enable the little **bounding box button** next to the **Plane** panel.

.. figure:: /images/2.8/plane_panel.jpg
   :align: center
   :width: 40%
   
   The bounding box button enabled.


The Plane’s bound box gets drawn only when referred to the box of the **Active** object or the current **Selection** of objects.
When you use the origin of the world, the cursor or the location of an object, there is no bound box to draw.
The Plane’s bound box is colored with the current axis Plane in use.

.. figure:: /images/2.8/plane_selection_bound_box.jpg
   :align: center
   
   The Plane bound box being drawn.

