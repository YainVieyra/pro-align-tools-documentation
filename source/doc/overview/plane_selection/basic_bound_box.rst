Selecting a Plane from the basic bound box
==========================================

You can use a more basic approximation to the object's geometry by using a **global** bound box that surrounds the **local** bounds of the object.
This bound box ignores the object's geometry, which usually means that the projection Plane will not always exactly touch the object’s surface.

To use this bound box, use the shortcut **Shift** + **G** or by disabling the **Use geometry** button in the **Plane** panel from the Sidebar (**N**), when the plane **Target** is set to use the **Object Bounds**.

Both **global** and **local** bound boxes are drawn simultaneously in this mode.

.. figure:: /images/2.8/plane_selection_active_basic.jpg
   :align: center
   
   Selecting a Plane from the global bound box, while local bounds are also drawn.

