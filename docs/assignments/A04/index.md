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


