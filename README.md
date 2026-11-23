# Ex.No.-1.1-Design and Draft the given 2D Sketches in modelling software.

## AIM

To sketch the given drawing with dimensions using fusion 360 tool.

## REQUIREMENTS

  1. Autodesk fusion 360
  2. Windows 10
  3. 16 GB of RAM (integrated graphics recommend 2 GB or more)
  4. 2.5 Mbps or faster download; 500 Kbps or faster upload 
  
## PROCEDURE

STEP 1: Start a new design. 
1. Open Fusion 360 and click File > New > Part Design. 
2. Click create new. 
3. Check that the workspace (top left) shows DESIGN. 
4. Ensure that you have set the units to mm in the browser panel.
   
<img width="1920" height="1080" alt="Screenshot 2026-10-11 203641" src="https://github.com/user-attachments/assets/58168679-52e4-4688-ab9d-d49e0ae3a5e9" />


STEP 2: Create a sketch and select the plane 
1. Go to SOLID > CREATE > Create Sketch. 
2. Click the Front (XY) plane in the viewport. The view rotates to face the plane. 
3. The origin will be the centre of the part

<img width="1920" height="1080" alt="Screenshot 2026-10-11 204032" src="https://github.com/user-attachments/assets/82024b27-6478-4e4b-8dc5-99fd9a7491cf" />

   
STEP 3 : Draw the centre lines 
1. Choose Line (L). Draw a vertical line through the origin and a horizontal line through 
the origin. 
2. Select both lines and tick Construction in the Sketch Palette (or press X) so they 
become dashed lines

<img width="1920" height="1080" alt="Screenshot 2026-10-11 204647" src="https://github.com/user-attachments/assets/f6e59dc3-cb4e-4087-92e3-9f7da0400dea" />


STEP 4: Draw the circles 
Select CREATE > Circle > Center Diameter Circle (C) and draw the circle 
1. Top: hole Ø20 and outer boss Ø32. 
2. Left and right: small holes (radius R7) with outer rings R10. 
3. Bottom: hole Ø10 with outer boss Ø20. 
4. Centre: circle Ø40 on the origin and Type each value in the dimension box and press 
Enter.

<img width="1920" height="1080" alt="Screenshot 2026-10-11 205823" src="https://github.com/user-attachments/assets/ce55d4d9-713f-4d98-8f7e-5b1f7fd27299" />


STEP 5 : Locate the hole centres 
Using Point and Sketch Dimension (D), fix the centres of the four hole positions from 
the origin: 
• Top hole centre: 65 mm above the horizontal centre line, on the vertical axis. 
• Side hole centres: 47 mm left and 47 mm right of the vertical axis, 26 mm below the 
horizontal centre line. 
• Bottom hole centre: 24 mm below the side holes (50 mm below the horizontal centre 
line), on the vertical axis.

<img width="1920" height="1080" alt="Screenshot 2026-10-11 210632" src="https://github.com/user-attachments/assets/bfe2d925-3298-45da-bf03-9ec73a3f4403" />

 
STEP 6 : Draw the large side arcs (R64) 
1. Use CREATE > Arc > Tangent Arc or 3-Point Arc to draw the sweeping curves running 
from the top boss down toward the side lobes. 
2. Make each arc tangent to the top boss circle (Ø32) and dimension it R64. 
3. Repeat on the other side so the shape is symmetric about the vertical axis. You can 
also draw one side and use the option.

<img width="948" height="833" alt="Screenshot (9)" src="https://github.com/user-attachments/assets/f7dcd2ab-273b-4e7d-b308-af3840d92e3b" />

 
STEP 7: Join the side lobes and bottom boss 
1. Draw the concave blend arcs between the large arcs and the side lobes (R20), 
keeping them tangent to the R10 outer rings. 
2. Draw the blend between the side lobes and the bottom boss (R20 and R10 as shown 
in the figure). 
3. Use tangent constraints at every joint so the outline is smooth.

<img width="1048" height="481" alt="WhatsApp Image 2026-11-23 at 18 30 17" src="https://github.com/user-attachments/assets/d70cd2e8-5b83-4c05-a82f-fb24e97e20d4" />

   
STEP 8: Make the star-shaped centre cut-out 
1. On the Ø40 circle, draw one small R6 circle at one notch position. 
2. Use CREATE > Circular Pattern with the origin as the centre, choose the R6 circle as 
the object, and set the quantity to match the figure. 
3. Use Trim (T) to remove the arc portions of the Ø40 circle inside the notches so that 
only the star outline remains.

<img width="882" height="813" alt="Screenshot (11)" src="https://github.com/user-attachments/assets/a8e5ba84-835b-4c90-a780-2a6387378c55" />


STEP 9: Edit and clean up the sketch 
1. Use MODIFY > Trim to delete extra line segments and overlaps. 
2. Use Mirror for any feature drawn on one side only. 
3. Add missing Sketch Dimensions (D) until all lines turn dark blue / fully constrained.

 <img width="1040" height="588" alt="Screenshot (12)" src="https://github.com/user-attachments/assets/69f3ed51-f0ef-43a6-94a0-f2fe2a41b207" />


STEP 10: Finish the sketch 
Click FINISH SKETCH in the toolbar to finalise it. Save the file with Ctrl + S. 

<img width="496" height="983" alt="Screenshot (14)" src="https://github.com/user-attachments/assets/c47defb6-32cc-4943-b13a-400ff743ff37" />


STEP 11 : Extrude the sketch 
1. Click CREATE > Extrude (or press E). 
2. Click inside the closed sketch profile. The area between the outer outline and the 
holes/star cut-out turns blue, and the holes stay empty. 
3. In the Distance box, type the thickness of the part (for example 20 mm) and press 
Enter. Drag the arrow only if you need to preview it. 
4. Click OK to create the 3D solid.

<img width="737" height="753" alt="WhatsApp Image 2026-11-23 at 18 31 17" src="https://github.com/user-attachments/assets/3383d9fd-6d41-4c4f-b916-ce8e1e2a0741" />

    
STEP 12: Create the drawing (ISO) 
1. Click the workspace drop-down (DESIGN) and choose DRAWING > FROM DESIGN. 
2. In the Create Drawing dialog set , choose manual. 
3.set the scale value(for eg: 1:0.9) 
4. Click OK. 
5. Place the view on the sheet, then add the dimensions and centre marks. 
6. Save the drawing.
   
<img width="1920" height="1080" alt="Screenshot (16)" src="https://github.com/user-attachments/assets/08dbf576-b405-4d28-9ce6-aeca50148bc6" />


## OUTPUT

<img width="700" height="602" alt="Screenshot 2026-10-11 200246" src="https://github.com/user-attachments/assets/b3c050fd-14f7-4627-823a-5b877bac4fe1" />


## RESULT
Thus the given sketch is drawn and drafted using fusion 360 tool.
