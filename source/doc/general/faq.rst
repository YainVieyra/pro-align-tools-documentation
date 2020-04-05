Frequent Questions
==================

|

When using an older 2.8 version of Pro Align Tools (pro_align_tools_2_8.zip), I can't see the Align tool icon in the Toolbar. What can I do to solve this problem?
##################################################################################################################################################################

The 2.80 version of the script had to copy a special icon in the Blender installation directory.

Sometimes the user don't have permission to copy files into that directory.
This is why, when failing to do so, the icon looks missing with a NONE placeholder icon.

The first time, you should launch Blender with administration rights and do the installation normally.

If you installed the addon previously, it's recommended to first remove the addon and then,
after reinstallation and activation, your icon should appear visible in the toolbar.

Next executions of Blender won't require administration rights, so you can launch normally.

**The most recent versions of Pro Align Tools don't have this problem anymore.**

|

What can I do when I need to select an object behind a gizmo?
#############################################################

You can approach this problem in 3 ways:

* The most obvious is to zoom in/out and avoid the cursor being on top of any gizmo, then selecting your geometry as usual.
* If you prefer to select objects with the **Left Click**, you can temporary use the shortcut **D** in the 3D View to turn off the drawing of gizmos.
  Then you can perform all your actions as usual without worrying about clicking on any gizmo.
  When you are done selecting your objects, you can re-enable the drawing of gizmos by using the same shortcut.
* If you prefer to select objects with the **Right Click**, you can take advantage of the fact that with this workflow, selection and action are bound to different buttons, and this way they never conflict each other.
  The action on gizmos is always on **Left Click** while selection happens on **Right Click**.
