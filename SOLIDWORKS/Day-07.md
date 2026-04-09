<img width="1920" height="1080" alt="Screenshot (22)" src="https://github.com/user-attachments/assets/08fd2a5c-9c30-47ac-83e9-70b8838c3204" />
<img width="1920" height="1080" alt="Screenshot (24)" src="https://github.com/user-attachments/assets/8d10b388-84f0-4033-a4a2-c8ae664a8149" />
<img width="1920" height="1080" alt="Screenshot (23)" src="https://github.com/user-attachments/assets/cf5ed933-10e1-422c-be6c-f744a7508122" />

Step 1: Sketch (Base Rectangle)
Start a new part and select the Top Plane
Draw a rectangular base profile using the Rectangle tool
Fully define the sketch using given proportions
Dimensions used: Overall base length and width (as per model)
Plane: Top Plane

Step 2: Boss-Extrude (Base Block)
Go to Features → Extruded Boss/Base
Extrude the base sketch to create the first solid block
Dimensions used: Base thickness (uniform height)
This forms the lowest level of the model

Step 3: Sketch (Second Level Platform)
Select the top face of the base
Draw a smaller rectangle positioned towards the back/right side
Dimensions used: Reduced length and width compared to base
Ensure proper alignment with edges
Plane: Top face of base

Step 4: Boss-Extrude (Second Level)
Extrude this sketch upward
Dimensions used: Height of second step
This creates the middle raised platform

Step 5: Sketch (Top Level Block)
Select the top face of the second level
Draw another rectangle on top
Dimensions used: Smaller footprint than second level
Plane: Top face of second level

Step 6: Boss-Extrude (Top Level)
Extrude upward to create the third level (highest block)
Dimensions used: Height of top block

Step 7: Sketch (Slot Profile)
Select the top face of the base or second level (depending on design intent)
Draw a rectangular slot along the length of the model
Position it centrally between side walls
Dimensions used: Slot width and length

Step 8: Extruded Cut (Slot Creation)
Go to Features → Extruded Cut
Remove material to form the slot
End condition: Blind or Through All
This creates the linear recessed feature

Step 9: Final Adjustments
Verify all features:
Boss-Extrude1 → Base
Boss-Extrude2 → Second level
Boss-Extrude3 → Top level
Ensure the model is properly aligned and complete
🔍 Final Summary
The model is created using a multi-level extrusion approach:
Base block → Second step → Top step
A slot is created using extruded cut
Key concepts used:
👉 Feature stacking
👉 Sketch-based extrusion
👉 Material removal

⚡ Key Learning
Understanding hierarchical feature building
Using multiple sketch planes (top faces)
Combining Boss-Extrude + Cut-Extrude efficiently
