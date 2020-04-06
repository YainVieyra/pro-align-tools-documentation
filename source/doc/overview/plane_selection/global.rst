Global Space
============

Picking the *projection Plane* directly from the 3D view
--------------------------------------------------------

You can pick the *projection Plane* from the 3D view if you are in interactive mode.

To pick interactively, hold the **Shift** key while you move the mouse cursor.
A small rounded box with a legend, will appear below the mouse cursor, to let you know what kind of element you are selecting.
In this case, it shows the word "Plane".

While you hold the key, you can see all the available points from where you can pick a *projection Plane*.
They appear as white rounded dots in the corners only.
The midpoints are only shown when you are near them.

You can pick a *projection Plane* from the origin of the world, the cursor, some plane of the bounding box of the selected objects and from their location (their origin pivot point).

When you pass near a pickable point, a yellow dot will appear, indicating that you can select it.
Along with the point, a colored line will be drawn, this is the **normal** of the plane, indicating the axis that will be taken as *projection Plane*.

The colors of the normal lines are codified, meaning, **light red** as the X axis *Plane*, **light green** as the Y axis *Plane*, and **light blue** as the Z axis *Plane*.

.. figure:: /images/2.79/plane_picking.jpg
   :align: center
   
   Picking the projection Plane interactively.


If you click with the **Left mouse button** while you still hold the **Shift** key, the point and normal will be selected as the *projection Plane*.

If you check the **Plane panel**, you will see that your actions get updated in the User Interface, from where you can change settings and pick the *Plane*, its **Axis** and its **Depth**.

You can also note that your object highlights while you are near some of the points.
This helps to understand what are you picking up, since you can also select the *projection Plane* of a group of objects instead.

|

To show the bounding box used by the *projection Plane*, enable the little **bounding box button** next to the Plane **panel**.

.. figure:: /images/2.79/plane_box.jpg
   :align: center
   :width: 40%
   
   Enabling the drawing of the bound box for the current Plane.

|

The bounding box for the *projection Plane* will only appear when you use the bounds of an object or group of objects.
When you use the origin of the world, cursor or location of an object, there will be no bounding box drawn.
The bounding box will be colored with the current axis Plane in use.

.. figure:: /images/2.79/plane_picking_geometry.jpg
   :align: center
   
   Picking a projection Plane while the bounding box is drawn.

