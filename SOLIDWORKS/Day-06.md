<img width="1920" height="1080" alt="Screenshot (6)" src="https://github.com/user-attachments/assets/82fdef90-4cb0-483a-a5aa-01788b6a3233" />

<img width="1920" height="1080" alt="Screenshot (8)" src="https://github.com/user-attachments/assets/a2f8f28e-3c55-4059-b66e-ae2362ef0643" />

<img width="1920" height="1080" alt="Screenshot (7)" src="https://github.com/user-attachments/assets/5ddee81b-0fe4-4dee-b3ef-95142ce370bb" />

Step 1: Sketch (Base Rectangle)
Start a new part and select the Top Plane
Create a rectangle to define the base of the model
Dimensions used: (as per your sketch – rectangular base, proportional to final model)
Fully define the sketch
Plane: Top Plane

Step 2: Boss-Extrude (Base Block)
Go to Features → Extruded Boss/Base
Extrude the rectangle to create the base solid
Dimensions used: Base thickness (uniform height across model)
This forms the main platform

Step 3: Sketch (Top Raised Block)
Select the top face of the base
Create a smaller rectangle toward the back side
Dimensions used: Width and length smaller than base, positioned near rear edge
Fully define the sketch
Plane: Top face of base

Step 4: Boss-Extrude (Upper Block)
Extrude the rectangle upward
Dimensions used: Height of the top block
This creates the rear raised feature

Step 5: Sketch (Front Raised Block)
Select the top face of the base
Draw another rectangle at the front side
Dimensions used: Smaller rectangular profile
Positioned opposite to rear block
Plane: Top face

Step 6: Boss-Extrude (Front Block)
Extrude this sketch upward
Dimensions used: Height of front block (same or different as rear)
Now you have two raised features on base

Step 7: Sketch (Cut Profile – Middle Slot)
Select the top face of the base
Draw a rectangular slot between the two raised blocks
Shape matches the internal cut visible
Dimensions used: Width and depth of slot

Step 8: Extruded Cut (Remove Material)
Go to Features → Extruded Cut
Cut the slot downward into the base
End condition: Blind or Through All (based on depth in your model)
This creates the central cavity

Step 9: Final Adjustments
Ensure all features are aligned and fully defined
Verify feature tree:
Boss-Extrude1 → Base
Boss-Extrude2/3 → Raised blocks
Cut-Extrude → Slot

🔍 Final Summary
The model is created using simple parametric features:
Base created using Boss-Extrude
Raised sections added using additional extrusions
Material removed using Extruded Cut
Key concepts used:
👉 Feature stacking
👉 Sketch-based modeling
👉 Material addition & removal
