# A4 – Motor Mount

## Objective / Description

Design a motor mount using the (Brushed 24V DC Gear Motor 3.6Kg.cm/46RPM w/ 99.5:1 Planetary Gearbox) HERE which attaches to the rigid wall A. For both features, first design for yield strength and then design for a maximum deflection of .30 mm at the free end. You may select ABS, PETG,  or PLA as a motor mount material.  When designing the motor mount take into account a safety factor of 3 and neglect the weight of the motor. For steps 1 and 2 draw a FBD of the forces and a concept of your design. Research the design of different motor mounts and place the links in an appendix on your page. Make justifiable approximations in your design to simplify your analysis. (ie. use the beam calculations) Follow Appendix B for the initial approach to set up the design analysis.

<img width="123" height="99" alt="image" src="https://github.com/user-attachments/assets/78d8356f-c92d-4128-923e-5a9d8c4cd0bd" />

Figure 1: Shows the motor, the rigid wall, and the force received on the shaft of the motor, where P = 300 N

### Physical Specification

Motor Size: Φ27.7 x 38mm

Gearbox Size: Φ28 x 36.6mm

Shaft Diameter: Φ6mm

Shaft Length: 18mm

D-cut Length: 12mm

### Material Specification 

Within these calculations, I made a design choice to utilize an ABS material; the specifications for this material is as follows.

<img width="711" height="366" alt="image" src="https://github.com/user-attachments/assets/e09ee971-2f51-4593-ad3d-18e19958fce8" />


## Feature 1 

I first started with the design of feature one, specifically with the overall width and length of the piece. The motor had a face diameter of about 28 millimeters. I wanted to ensure enough contact area and enough material for forces acting on the mount, and ended up going with 36mm. With these chosen design specifications, I then solved for the force acting on feature 1 due to the moment created by the 300N force utilizing a FBD. I included this value along with the lowest Young's modulus of ABS to account for errors in the material and included the yield strength for ABS. The rest of the values utilized in calculations are given through my dementions or the assignment details.

<img width="2574" height="1939" alt="IMG_3920" src="https://github.com/user-attachments/assets/a96358c2-d0c7-4bbd-bce6-e3881693820f" />

I then needed to solve for the other dimensions of feature 1, utilizing the constraints given to me within the problem, this being a max deflection of 0.3mm and a safety factor of 3. Because of this, I have to compare the thicknesses calculated in both my deflection formula as well as my stress formula, though after writing down both equations, I noticed I was missing inertia. Due to this object being a box, I know the equation of inertia and was able to plug it into each formula to solve for the actual thickness of the object. Once I had solved for the thickness utilizing deflection, I ended up getting a value of 12.95mm . I then next needed to solve, taking into consideration stress and relating it to safety factor. After doing so and manipulating the inertia value to solve for thickness, I ended up getting a thickness of 9.49mm. I then took the larger value of thickness, as that would account for both the stress and deflection without failing.

<img width="2261" height="2220" alt="IMG_3921" src="https://github.com/user-attachments/assets/d76feefa-9686-488e-ab17-f0ef3e6378d3" />

## Feature 2

Next for feature 2 I ended up choosing a dimension of 36mm for the width to stay consistent with feature 1. Next I had to geometrically calculate the length, I simply took the toal length of the motor, added it to the thickness calculated for feature 1, being 12.95mm to get a total length of feature 2 87.6mm. After creating a FBD and solving for the total length, I calculated the moment acting on feature 2, also taking into account the 18mm overhang by the motor shaft. getting a moment value of 31,680N/mm. I then listed all of my knowns and unknowns, all being mostly the same besides the length of the new feature.

<img width="2305" height="2174" alt="IMG_3922" src="https://github.com/user-attachments/assets/6b0dad7b-6bf2-40b4-b66e-7b9885ef793d" />

Very similar to my feature 1 calculation, I first started with my deflection formula, manipulating it to solve for inertia. Once I had solved for inertia, I then manipulated the formula to solve for thickness, getting a value of 42.26mm when taking deflection into account for this part. I next utilized the stress formula relating it to the safety factor given in the problem. I then manipulated inertia as well as the variable C to solve for the thickness. Once calculated, I got a value of 22.98mm. When comparing the two 42.26mm was the larger value that will take into account both limiting factors in this design.

<img width="2522" height="1648" alt="IMG_3923" src="https://github.com/user-attachments/assets/2fdffe28-6294-4aca-8131-8e62ea269d4c" />

## Isometric Sketch

As depicted below is my isometric sketch, fully dimensioned with both chosen and calculated dimension values. 

<img width="2574" height="2168" alt="IMG_3919" src="https://github.com/user-attachments/assets/fb9e2d96-9bfb-45c4-9d64-9277069160f4" />

## CAD Model / Parametric Modeling

Prior to starting my 3D model I created global variables for the different features, specifying them to the calculated and chosen dimensions I had utilized in my previous calculations. The image depicted below is all of the values I utilized in this 3D drawing.

<img width="796" height="325" alt="Screenshot 2026-09-14 175105" src="https://github.com/user-attachments/assets/3fa87142-d4ab-4f93-a66a-f330ccb92ec6" />

Next created the overall dimensions of the motor mount, including both feature 1 and feature 2 as depicted in the image below. I utilized the values I had chosen as well as calculated thicknesses for both features 1 and 2, as depicted in the image.

<img width="1438" height="1101" alt="Screenshot 2026-09-14 162211" src="https://github.com/user-attachments/assets/64097c52-2eba-4cfb-b38d-155f450756d8" />

I then created the bolt holes as well as the shaft hole for the front-facing edge of the motor for the motor mount. I ensured that the center hole for the axle was 6mm, as well as the bolt holes were 3.4mm in diameter, as specified in the project description. Though I had some issues with placing the actual bolt holes for the connection of the motor, as the design specifications on the actual product website did not list the actual separation of the bolt holes, as well as its pattern. I had to estimate where they were located. After determining the dimensions of the outside as well as the inside edge of the brushless motor, I concluded it was about 9.45 millimeters from the center point of the driving shaft of the motor, as depicted in the dimensions and the image below.

<img width="964" height="770" alt="Screenshot 2026-09-14 165253" src="https://github.com/user-attachments/assets/f05b8647-e655-4692-ba57-8bf461690279" />

Once again for the bolt holes on feature 2 they were not necessarily specified at their location. So I ensured that they were far enough away from the outer edges to ensure the material would sustain the forces, while maintaining their separation distance as well as their size of 3.4mm, as depicted in the image below.

<img width="2015" height="926" alt="Screenshot 2026-09-14 171714" src="https://github.com/user-attachments/assets/2443eedb-1f10-4a3f-a0ea-06988727c149" />

## Design Feature

This assignment then wanted me to utilize a design feature that would minimize deflection in the object. I included supports holding the two features to one another to help resist the moment and other forces that this object may experience during loading.

<img width="647" height="641" alt="Screenshot 2026-09-14 172556" src="https://github.com/user-attachments/assets/9ea9c91a-01f8-4b39-90a9-8f694d4ded5d" />

# Finished Product

<img width="703" height="942" alt="Screenshot 2026-09-14 175350" src="https://github.com/user-attachments/assets/edd055bd-4d38-434e-9594-fafad2744f5a" />

## CAD FILE

https://drive.google.com/file/d/1Eo0gTCwCbzcqhDuGfihEtWFVkEG3U8e3/view?usp=sharing







