# FreeCAD Macro Export selection to DXF

A FreeCAD marco to speed up the export of selected objects into a DXF file.

**What it does :**

It creates a new TechDraw page with a blank template and adds a view to it which
contains the selected objects. The view is projected along the 3D camera
orientation. Then, the macro opens up a file dialog in order to save this view
as a DXF file.

**How to use :**

- Open the 3D view and place the camera on the wanted projection angle.
- Select some objects from the tree.
- Invoke the macro.

**Why ?**

In order to avoid to manually create a TechDraw page, pick a template and
create a view, set the view to 0;0 position, etc...

All these repetitive steps are now done by the macro, this will speed up the
FreeCAD workflow.

The DXF file is at scale 1:1, it is meant for laser cutting.
