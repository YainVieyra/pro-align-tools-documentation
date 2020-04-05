Picking a custom plane
======================

You can pick any mesh surface for alignment in your scene, which creates a draggable plane oriented to the mesh face normal.
This is very useful to set a fast plane from Object Mode and to align in realtime, with the advantage of using up to 3 depths in relation to the plane;
also with the option of applying an offset to it at any time.

To pick a **custom plane**, select the **Align** Tool and press **Shift** + **P** with the cursor in the 3D View. An eyedropper with a small text legend appears.

If you point to an object and a mesh face is detected, the legend reports the **object’s name** colored in **green** and the **face index** of the mesh face that will be used.
If the eyedropper is not pointing to any object, the legend reports the next action colored in **red**: **Clear**.

.. figure:: /images/2.8/custom_plane_picking.jpg
   :align: center
   
   The custom plane can be picked from an arbitrary mesh face.

.. figure:: /images/2.8/custom_plane_clearing.jpg
   :align: center
   
   The custom plane being cleared.


If you do **left click** with a valid mesh face, a **custom plane** is created, with an axis gizmo oriented to the face normal, showing two blue dots at both sides of the plane.
The axis of the plane is blue, indicating that the normal is actually the Z axis of the mesh’s face.

When passing with the mouse over the dots, an arrow appears, allowing you to select one of the three depths of alignment.
You can also change the depth from the Sidebar (**N**), using the **Alignment depth** buttons.

Drag the **custom plane** at any time as explained above in **Dragging an axis from a gizmo**.

.. figure:: /images/2.8/custom_plane_dragging.jpg
   :align: center
   
   Dragging the custom plane


On the other hand, if no mesh face is detected (including non mesh objects like metaballs, curves, etc.), the **Clear** action clears any **custom plane** that you may be using at the time.

When a custom plane is defined, the **Plane** subpanel in the Sidebar (**N**) updates to reflect this change.
The **Plane target** appears deselected, and below, the text ‘Custom Plane’ followed by an **X** button appears, replacing all other options in that section.

.. figure:: /images/2.8/custom_plane_panel.jpg
   :align: center
   
If you click the **X** button, the custom plane is **cleared**.
You can select any other **Plane target** that you may want from this panel, recovering the settings and ignoring the custom plane.

