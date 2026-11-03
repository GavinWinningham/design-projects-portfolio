# A8 – Gears

## Objective

1. Design a gearbox that can be assembled and disassembled.
2. Analyze and size input and output shafts for strength.
3. Design journal bearings to support shafts.
4. Create a gearbox housing with proper clearance and fastening.
5. Use parametric CAD modeling to generate a final design.
6. Document calculations, sketches, and lessons learned.

The documentation’s intent is to capture your work and learning process from the time you read through the assignment all the way until you turn in your work. Your work may include but not limited to your thoughts, your insights, your mistakes, your drawings, your calculations etc. Document each step in the process, no step is too small.

Document the process which includes many pictures with overviews of images
Detailed lessons learned throughout the process
Detail any mistakes throughout the process
Actual time it took from start to finish
Failure to put a link for downloading your CAD file will result in a 15% deduction to your final grade.


Failure to input headers in your assignment will result in a 15% deduction to your final grade.

Description:
Design a gearbox which can be assembled and disassembled. The spur gears have a gear ratio of 24:9 and are listed in the resource section. The output gear torque and speed are to be 1.25 in-lbf and 1100 rpm relative. The input (pinion,power-transmission) and output (gear, short shaft) shaft diameters are .125 and .25 inches respectively and each have a length of 1 inch. Use the appropriate equations in the Machinery’s Handbook for empirical units. The critical features of the gearbox include the shafts, and the journal bearings.

Assumptions: 

Assume appropriate strength of shafts, use Machinery’s Handbook.
The gear train is ideal.
The moment of the radial force from the gear train is small enough to be ignored.
Note:

The shafts are press fit through the hubs of the gears.
Make sure there is enough clearance between the gears and the gearbox.
Use a running sliding fit for the size of the hole for the shafts.

<img width="624" height="440" alt="image" src="https://github.com/user-attachments/assets/bc5d9387-32db-4c3b-9a7e-d199ebf89e11" />

## Shaft

I first started with what was given, as depicted in the image below. Going further, we are given the output speed and torque, as well as the gear ratio for the following gears. I then utilized the gear ratio relationship to then solve for the input RPM, as well as input torque, also as seen in the image depicted below.

<img width="624" height="440" alt="image" src="https://github.com/user-attachments/assets/e931c96b-5308-41d2-abc7-fe50df769255" />

### Diameter Verification

Next, I needed to verify the shaft diameters would function due to the given parameters of the problem. I started off with the equation as follows in the image below. Prior to solving for these individual diameters, I needed to find out the power experienced by these shafts. Due to this being an ideal condition, the power experienced by both the input and output shaft should be equal. In this case, I ended up calculating for the power at the output and ended up getting 0.02182 horsepower. I then plugged this into the diameter equation as listed below for both the input shaft and output shaft. Specifically for the diameter of the input shaft, I got a calculated value of 0.0841 inches, which is significantly less than the 0.125 inches specified in the document, meaning that this passes the test. When concluding the diameter of the output, I calculated a value of 0.091 inches, this being significantly less than the provided value, 0.25 inches. Because of this, both shafts succeed and are able to withstand the forces acting on them.

<img width="2096" height="631" alt="IMG_0021" src="https://github.com/user-attachments/assets/ce4b7366-1720-440f-838c-154a1cef5ff1" />

### Stress Calculations

Next, I needed to calculate the stresses acting on these input and output shafts. I first utilized a free body diagram showing the different forces acting on this object. Next was actually calculating these individual torsional shear stresses acting on them. Previous to actually calculating this, I needed to figure out the maximum pressure these shafts can withstand to see if the calculated torsional shear is within our parameters. I utilized the equation tau max equals 16T divided by pi D cubed. After plugging in my specific values for the input and output shafts, I ended up getting a maximum PSI of 4,000 for the input shaft and a maximum of 8,500 PSI for the output shaft in regards to torsional shear stress. I then utilized the equation below, tau equals Tc over J, manipulating the equation and plugging in the specific values for these specific shafts. After doing so, I got a torsional shear of 1,222.3 PSI for the torsional shear in the input shaft, this also being significantly lower than the 4,000 PSI maximum, meaning that this will succeed and not falter. Next was the torsional shear of the output, after being calculated was 407.4 PSI, significantly less than the 8,500 PSI, meaning this also passes the test.

<img width="2184" height="501" alt="IMG_0022" src="https://github.com/user-attachments/assets/957c85d7-98c8-4173-902e-2e3121385158" />





## Decide


## Communicate

