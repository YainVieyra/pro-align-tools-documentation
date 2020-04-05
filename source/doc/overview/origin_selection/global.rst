Global Space
============

When holding the **Ctrl** key pressed in the 3D View, you access the **Origin selection mode**.
This mode allows you to select an origin point which is used to displace the object during alignment.
You can select an origin point from common places like the **bounding boxes** of objects, the **location** of objects, the origin of the **world**, the **cursor** and any individual mesh **vertex** that you may have defined.

To select the origin interactively, hold the **Ctrl** key while you move the mouse cursor.
Below it, a small rounded box with a legend appears, to let you know what selection mode you are in. In this case, it shows the word ‘Origin’.

.. figure:: /images/2.8/origin_selection_start.jpg
   :align: center

While you hold the key, you can see all the available points from where you can select the Origin point.
In this selection mode, the points in the **corners** of bounding boxes are **rounded**, while any **midpoint** of the bound box is a **square point**.
All other points are also rounded, like the one from the origin of the **world**, the **cursor**, the **location** of objects and **vertex origins**.

There are two kind of points that you may select for bound boxes:

* **White** points appear in the bounds of the **Active** object and are related to the **individual** alignment of objects, projecting all selected objects, one by one against the alignment Plane.
  The origin point is **unique** for every object.
  This is the equivalent of having disabled the option **All selected** in the **Origin point** panel from the Sidebar (**N**).
* **Black** points appear in a generated bound box that surrounds your current **Selection** of objects and are related to a **grouped** alignment of objects, projecting all objects against the alignment Plane like if they were just one single object.
  The origin point is **common** for every object.
  This is the equivalent of having enabled the option **All selected** in the **Origin point** panel from the Sidebar.
    
.. figure:: /images/2.8/origin_selection_active.jpg
   :align: center
   
   Selecting the Origin point from the Active object.

.. figure:: /images/2.8/origin_selection_selection.jpg
   :align: center
   
   Selecting the Origin point from the current Selection of objects.

.. figure:: /images/2.8/origin_selection_cursor.jpg
   :align: center
   
   Selecting the Origin point from the cursor.


When you pass close to a selectable point, it highlights in **yellow**, indicating that you can select it.

The bound box also highlights when you are close to one of its points, to help you understand what kind of origin point are you selecting.
The bound box is drawn **white** when referring to project objects **individually**, and **black** when referring to project them **grouped** as a whole.

If you are over a clickable point and do **left click** while you still hold the **Ctrl** key, the Origin point is selected.
If you check the **Origin point** subpanel in the Sidebar (**N**), you can see that your actions get reflected there, from where you can change the settings at any time and select another Origin point.

To show the bound box of all the selected objects and appreciate what Origin point is being used for every one of them, enable the little **bounding box button** next to the **Origin point** panel.

.. figure:: /images/2.8/start_origin_panel.jpg
   :align: center
   :width: 40%
   
   The bounding box button enabled.


The bounding boxes get drawn only when they are being used to take an Origin point.
When you use the origin of the world, the cursor or the location of objects, there is no bound box to draw.

.. figure:: /images/2.8/origin_selection_boxes.jpg
   :align: center
   
   The bound boxes being drawn.

