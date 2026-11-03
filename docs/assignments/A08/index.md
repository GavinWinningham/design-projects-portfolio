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

<img width="2222" height="959" alt="IMG_0020" src="https://github.com/user-attachments/assets/80990c01-3b19-4bd2-aab1-ab347ded5aad" />


### Diameter Verification

Next, I needed to verify the shaft diameters would function due to the given parameters of the problem. I started off with the equation as follows in the image below. Prior to solving for these individual diameters, I needed to find out the power experienced by these shafts. Due to this being an ideal condition, the power experienced by both the input and output shaft should be equal. In this case, I ended up calculating for the power at the output and ended up getting 0.02182 horsepower. I then plugged this into the diameter equation as listed below for both the input shaft and output shaft. Specifically for the diameter of the input shaft, I got a calculated value of 0.0841 inches, which is significantly less than the 0.125 inches specified in the document, meaning that this passes the test. When concluding the diameter of the output, I calculated a value of 0.091 inches, this being significantly less than the provided value, 0.25 inches. Because of this, both shafts succeed and are able to withstand the forces acting on them.

<img width="2096" height="631" alt="IMG_0021" src="https://github.com/user-attachments/assets/ce4b7366-1720-440f-838c-154a1cef5ff1" />

### Stress Calculations

Next, I needed to calculate the stresses acting on these input and output shafts. I first utilized a free body diagram showing the different forces acting on this object. Next was actually calculating these individual torsional shear stresses acting on them. Previous to actually calculating this, I needed to figure out the maximum pressure these shafts can withstand to see if the calculated torsional shear is within our parameters. I utilized the equation tau max equals 16T divided by pi D cubed. After plugging in my specific values for the input and output shafts, I ended up getting a maximum PSI of 4,000 for the input shaft and a maximum of 8,500 PSI for the output shaft in regards to torsional shear stress. I then utilized the equation below, tau equals Tc over J, manipulating the equation and plugging in the specific values for these specific shafts. After doing so, I got a torsional shear of 1,222.3 PSI for the torsional shear in the input shaft, this also being significantly lower than the 4,000 PSI maximum, meaning that this will succeed and not falter. Next was the torsional shear of the output, after being calculated was 407.4 PSI, significantly less than the 8,500 PSI, meaning this also passes the test.

<img width="2184" height="501" alt="IMG_0022" src="https://github.com/user-attachments/assets/957c85d7-98c8-4173-902e-2e3121385158" />

## Bearings

Prior to starting my calculations for the bearing, I first listed all of the known values that we previously had along with the new calculated values, as well as some assumptions in regards to the bearing itself. Below is depicted a free body diagram, as well as my given values I ended up utilizing in my further calculations, as well as the equation that I used in my free body diagram.

<img width="1396" height="1112" alt="IMG_0023 (1)" src="https://github.com/user-attachments/assets/dc417058-22ba-4a3c-965b-ca2f7fa94c76" />

### Velocity / Pressure / PV Ratio

Next, I then looked to solve for the pressure, velocity, and PV experienced by these bearings. After writing down the equations for these, I noticed the pressure formula needed the radial force experienced by these bearings. I first started with the tangential force, utilizing the formula Ft equals 2T over D. After solving for the bearing input and output, I ended up getting the same value of 2.5 pounds force. Once that had been calculated, I utilized the formula Fr equals Ft tan of theta to get the radial force. After plugging in Ft and utilizing a 20-degree value for theta, I ended up getting a radial force of 0.91 pounds force. Once that had been calculated, I could then utilize that in my pressure equation, F over length times diameter. After plugging in the specific values for the input and output bearings, utilizing their area, I ended up getting a pressure input bearing equal to 29.12 psi. As for pressure output, I ended up getting 9.71 psi. Going further into velocity and utilizing the equation pi D n over 12, I noticed we had everything to solve for this. I then plugged in the values corresponding to the input and output values previously given. Ended up getting a velocity input of 95.9 feet per minute and a velocity output of 71.9 feet per minute.

<img width="2225" height="720" alt="IMG_0024" src="https://github.com/user-attachments/assets/18478caa-5823-4798-8a20-7258937fec68" />

I then looked to get the PV rating with the values that have since been calculated. After multiplying to solve for PVin, I ended up getting a value of 2,795 psi feet per minute. Next for PVout, I ended up getting 699 psi per feet over minute. Utilizing those values as well as the previous values, I ended up going to the table and concluding that we'd use porous bronze for my further calculations. Specifically, porous bronze has a load capacity of 4,500 psi as well as a maximum surface speed of 1,500 feet per minute and a PV limit of 50,000 psi per foot over a minute. This is significantly above anything that my object may face, ensuring no failure occurs.

<img width="1068" height="570" alt="IMG_0025" src="https://github.com/user-attachments/assets/60b35824-d744-41ff-b231-dea78d8af372" />

### Thickness / Component Name

I then solved for the theoretical thickness of the bearings due to the forces acting on them. I first started off with the pressure formula, manipulated it, and ended up getting the radial force over two times the thickness times the length. After manipulating that equation, I ended up getting the thickness is equal to the radial force over two times the pressure times the length. In this case, utilizing the specific bearing chosen, a maximum pressure of 4500 PSI, and previous values calculated, I end up getting a theoretical thickness of 0.000404 inches. This value is extremely small and makes sense due to the very small radial force this object is receiving. Due to the small value and being extremely small for manufacturing, I will utilize a much better and more fitting value in my 3D schematic.

I ended up selecting an oil-embedded SAE 841 bronze sleeve bearing from the MC Master website due to its suitability for low radial gear loads and shaft speeds in this gearbox. The input shaft in this vehicle will use a Part 6391K753 oil-embedded 841 bronze sleeve bearing for a 1/8 inch shaft. The output shaft in this case utilizes a Part 7634N11, an oil-embedded 841 bronze sleeve bearing with a 1/4 inch shaft.

## CAD

Below is a full depiction of my full step-by-step process in my CADing of this project. I first started with creating the bearings of the shafts, first starting with the input shaft and the output shaft. Then follows the actual creation of both the input and output shaft, followed by the assembly creation, first starting off with the mating of the two gears, then incorporating the shafts, then adding on the bearings, and then the full creation of my housing, followed by the housing actually being built onto the full assembly.

<img width="796" height="679" alt="Screenshot 2026-11-02 195211" src="https://github.com/user-attachments/assets/167506c4-af47-4333-942c-5a7ab3f51e94" />

<img width="1074" height="758" alt="Screenshot 2026-11-02 195633" src="https://github.com/user-attachments/assets/95ade630-617a-4220-8cf0-611f9420cddf" />

<img width="742" height="951" alt="Screenshot 2026-11-02 221828" src="https://github.com/user-attachments/assets/68da35c7-0ce7-42ef-8444-779053611555" />

<img width="753" height="664" alt="Screenshot 2026-11-02 221942" src="https://github.com/user-attachments/assets/9b534a51-f686-41ec-aca5-38b0d8135e68" />

<img width="970" height="715" alt="Screenshot 2026-11-02 221454" src="https://github.com/user-attachments/assets/59cc4566-2f8c-4e19-836b-a95aff60b108" />

<img width="698" height="747" alt="Screenshot 2026-11-02 222348" src="https://github.com/user-attachments/assets/ff95319d-d718-47ac-b56f-13955d6a6a1b" />

<img width="681" height="794" alt="Screenshot 2026-11-02 222436" src="https://github.com/user-attachments/assets/01b3d358-0ed9-44e4-9d72-6ef325b7906c" />

<img width="1304" height="1010" alt="Screenshot 2026-11-02 224118" src="https://github.com/user-attachments/assets/48e3fb85-28dc-4237-b600-25ff7252828c" />

<img width="1501" height="1062" alt="Screenshot 2026-11-02 224727" src="https://github.com/user-attachments/assets/b63d3ca7-5647-40db-bb0e-b4f3ac0c52b7" />

<img width="896" height="888" alt="Screenshot 2026-11-02 225943" src="https://github.com/user-attachments/assets/e3f5e480-5303-44da-b1ea-27a127d88cea" />

## CAD FILE

https://drive.google.com/file/d/10rSOy8nVUzPw2bM5HlEmkRjz3UMLaR3S/view?usp=sharing

