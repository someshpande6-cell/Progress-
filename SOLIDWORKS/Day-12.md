<img width="1920" height="1080" alt="Screenshot (38)" src="https://github.com/user-attachments/assets/89627e90-fd1f-4a67-bb0d-1d6d763d208a" />

Step 1: Base Circle (Sketch)
Select the Top Plane.
Draw a center circle at the origin.
Set diameter to Ø55 mm.
This forms the main hub of the model.
Step 2: Outer Circle (Sketch)
Draw another concentric circle.
Set diameter to Ø90 mm.
This creates the outer boundary of the main body.
Step 3: Inner Slot / Keyway (Sketch)
Draw a horizontal slot (rectangle) passing through the center.
Width of slot = 4 mm.
Align it symmetrically about the centerline.
Step 4: Radial Slots (Sketch Pattern)
Sketch one inclined rectangular slot between inner and outer circles.
Use angular constraints to position it.
Apply Circular Sketch Pattern:
Number of instances = 6
Equal spacing around the center
These form radial cut features.
Step 5: Small Bolt Circles (Sketch)
Draw one small circle above the main body.
Inner diameter = Ø20 mm
Outer diameter = Ø36 mm
Position it using center distance from origin.
Step 6: Pattern Small Circles
Use Circular Pattern:
Number of instances = 4
This creates four equally spaced bolt holes with bosses.
Step 7: Outer Connecting Profile (Sketch)
Use arcs and tangent lines to connect the outer small circles.
Add smooth curves between them.
Apply given dimensions:
Arc radius ~ 28 mm
Distance between centers = 60 mm
Ensure tangency relations for smooth flow.
Step 8: Fully Define Sketch
Add all missing dimensions and relations.
Ensure sketch status becomes Fully Defined (Black).
Step 9: Boss-Extrude
Exit sketch.
Apply Boss-Extrude to the entire profile.
Set thickness as required (not shown, assume standard).
Step 10: Cut Features
Use Cut-Extrude for:
Central bore (Ø55 region if hollow)
Radial slots
Keyway slot (4 mm)
Ensure cuts go Through All.
Summary

This model is created using a radial symmetry approach:

Start with concentric circles (hub + outer body)
Add functional features (slots, keyway)
Create bolt patterns using circular pattern
Use tangent arcs for smooth outer geometry

Overall workflow:
Sketch → Pattern → Constrain → Extrude → Cut → Finalize
