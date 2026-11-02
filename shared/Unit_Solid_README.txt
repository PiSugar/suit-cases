SolidWorks editable solid models

Files: Unit_Joystick2_Solid.SLDPRT / .step
       Unit_Scroll_Solid.SLDPRT / .step

Units: millimetres. Original assembly positions are retained.
The exploded duplicate parts in the original STL files are excluded.
Joystick2 has 4 solid bodies; Scroll has 5 solid bodies.
Original STL and original SLDPRT files were not overwritten.

These are standard BREP solids, not graphics bodies or mesh BREP.
SolidWorks 2025 SP5 body checks report zero faults for all bodies.
See unit-solid-validation.txt for the final checks and export status.

You can add sketches, extrusions and cuts, and use direct face editing.
STL contains no original sketches or dimensions, so the original
parametric feature tree is not recovered. Curved regions still contain
faceted planar faces. Coplanar faces were merged where possible for
Joystick2; local faulty faces were patched in SolidWorks. Scroll uses
standard faceted BREP geometry with repaired shell faces. The models
are suitable for assembly reference and further solid modelling, but
are not a full smooth-surface or parametric reverse engineering.
