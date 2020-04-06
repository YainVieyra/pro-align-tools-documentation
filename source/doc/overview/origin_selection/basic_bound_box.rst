Picking the *Origin point* from the basic bound box
===================================================

You can use a more basic approximation for alignment by using a **global bounding box** surrounding the local bounds of the object.
This bounding box ignores the object's geometry, which usually means that it will not exactly touch the *projection Plane* when aligned.

To use this bounding box, you can disable the button **Use geometry** in the Origin point panel, or by using the shortcut **Ctrl** + **G**.

The local bounding box will also be drawn in this mode, so that you can see the relationship between the two boxes.

.. figure:: /images/2.79/origin_point_picking_world.jpg
   :align: center
   
   Picking an origin point from the global bounding box, while local bounds are drawn.

