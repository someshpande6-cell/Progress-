<img width="1920" height="1080" alt="Screenshot (25)" src="https://github.com/user-attachments/assets/e16b1a0a-e967-4282-a0be-4c43a007a56c" />
<img width="1920" height="1080" alt="Screenshot (26)" src="https://github.com/user-attachments/assets/038ab59a-f401-44f5-ba26-123c05984fca" />
<img width="1920" height="1080" alt="Screenshot (27)" src="https://github.com/user-attachments/assets/fbc70119-5fa2-46ee-b4ff-e7837949c144" />

Step 1: Sketch (Base Profile)
Start a new part and select the Top Plane
Draw a rectangle with one semicircular end
Use rectangle + arc (or slot tool)
This forms the base outline
Dimensions used: Length, width, and radius of rounded end (as per given drawing)
Plane: Top Plane

Step 2: Boss-Extrude (Base Plate)
Go to Features → Extruded Boss/Base
Extrude the sketch to create the base solid
Dimensions used: Base thickness
This forms the main plate

Step 3: Sketch (Raised Block)
Select the top face of the base (left side)
Draw a rectangle for the raised portion
Dimensions used: Width and length of the block
Positioned at one end of the base
Plane: Top face

Step 4: Boss-Extrude (Raised Feature)
Extrude the rectangle upward
Dimensions used: Height of the raised block
This creates the vertical boss feature

Step 5: Sketch (Slot Profile)
Select the top face of the base
Draw a slot (rectangular with semicircular end)
Use Straight Slot tool or rectangle + arc
Position it centrally along the length
Dimensions used: Slot length and width

Step 6: Extruded Cut (Slot Removal)
Go to Features → Extruded Cut
Cut the slot downward
End condition: Through All
This creates the internal slot feature

Step 7: Final Adjustments
Verify feature tree:
Boss-Extrude1 → Base
Boss-Extrude2 → Raised block
Cut-Extrude → Slot
Ensure geometry is clean and aligned

🔍 Final Summary
The model is created using:
Base extrusion (rounded profile)
Raised boss feature
Slot created using cut-extrude
Key concepts used:
👉 Combination of straight + curved geometry
👉 Feature-based modeling
👉 Material removal using slot

⚡ Key Learning
How to create rounded profiles using arcs
Use of slot tool vs manual sketching
Efficient use of Extrude + Cut features
