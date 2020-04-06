Picking from the basic bounding box
===================================

You can use a more basic approximation to the object's geometry by using a **global bounding box** surrounding the local bounds of the object. This bounding box ignores the object's geometry, which usually means that the *projection Plane* will not exactly touch the object.

To use this bounding box, you can disable the button **Use geometry** in the Plane panel, or by using the shortcut **Shift** + **G**.

The local bounding box will also be drawn in this mode, so that you can see the relationship between the two boxes.

.. figure:: /images/2.79/plane_picking_world.jpg
   :align: center
   
   Picking the projection Plane from the global bounding box, while local bounds are drawn.
