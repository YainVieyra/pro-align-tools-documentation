Selecting a Custom Origin from Edit mode
========================================

If you have a mesh object and enter **Edit mode**, selecting the Align tool from the Toolbar, displays different options in the Sidebar (**N**).
From here you can **Set** and **Remove** a **custom origin point**.

.. figure:: /images/2.8/custom_origin_panel_edit.jpg
   :align: center
   :width: 40%
   
   The Set Custom Origin button shown in Edit mode.


You can use this as a **singular** origin for all your selected objects.
All of them will start moving from this point.
The origin is linked to the object, so moving or transforming it will make the origin follow the mesh.

When pressing the button **Set Custom Origin**, the vertex used is the active one, no matter if you have selected several of them.
Once you have set the origin, the **Remove** button becomes available.
Now the selected origin is drawn in the 3D view as a **green** colored point.

If you can’t see the green point in Edit mode when you have already **set** the origin, it could be that you need to enable the **Show Gizmo** button in the 3D view.
You can easily toggle that option with the shortcut **D**.

.. figure:: /images/2.8/custom_origin.jpg
   :align: center
   
   At the top: Selecting a Custom Origin point in Edit mode.
   
   At the middle: The alignment preview from the Custom Origin point in Object mode.
   
   At the bottom: Alignment is performed.


Using a **custom origin** for all your selected objects is different than using the option **All selected**, since if you use a **Local Direction** for displacement, you could project objects individually, moving them on their own axes, every one starting from the same point, but reaching to a different location.

You can reselect your custom origin point at any time from **Object mode** while you are in **Origin select mode** holding **Ctrl**.

.. figure:: /images/2.8/custom_origin_reselecting.jpg
   :align: center
   
   Reselecting the custom origin point in Object mode.


When you have set a custom origin, you can find a new text line ‘Vertex in:’ with the name of the origin Object in the **Origin point** panel found in the Sidebar (**N**), replacing the origin options for **Objects**.
From here you can also **remove** the custom origin at any time by pressing the little **X** button.

.. figure:: /images/2.8/custom_origin_panel_object.jpg
   :align: center
   :width: 40%

The custom origin is also lost when you get out of the Align tool both in **Object** and **Edit** modes.
This is by design.

