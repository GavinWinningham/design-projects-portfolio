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










## Decide


## Communicate

