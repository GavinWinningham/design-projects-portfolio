# A9 – Pulleys

## Objective

Design a pulley system to transfer power between two parallel axes separated by a center distance of 4–6 inches. The system must meet the following requirements:

Pulley Diameter: Both pulleys shall have a diameter of 3 inches.
Rotational Speed: Select an operating speed between 1000–2000 rpm.
Belt Tension (Static): Select a belt tension between 4–6 lbf under stationary conditions.
Material: Pulleys may be made from aluminum, ABS, or steel, and may include a groove and shaft diameter of your choosing (within reasonable manufacturing limits).
Safety Factor: The design must satisfy a minimum safety factor of 3.
Assume the belt is made from polyurethane rubber, with a yield strength of 3.25 MPa (471 psi) at 20% strain, based on: Wanga, Chena, Wua, Zhangb, Suna, “Strain-induced Structural and Dynamic Changes in Segmented Polyurethane Elastomers.”

<img width="295" height="100" alt="image" src="https://github.com/user-attachments/assets/21fa319d-c5d0-4cf6-8af4-ecc9583d5b0b" />

## Belt Design

I first started this project by selecting my known values I could select, as well as any other given in the problem. It was selected that my design would utilize two 3-inch diameter pulleys with a 5-inch center distance operating at 1,500 RPM. A tension between the pulleys was a value of 5 lbf was selected along with the required minimum safety factor of 3. The rubber that was utilized had a yield strength of 471 psi. The coefficient of friction utilized in this was 1. I then created a free body diagram utilizing sum of forces to be able to figure out what the force of 1 and 2 acting on this pulley are in relation to the force that opposes them.

<img width="1262" height="943" alt="IMG_0026" src="https://github.com/user-attachments/assets/b30169b4-1c1d-4898-b3cf-4463915ae5dd" />

I then needed to figure out what the forces acting on the pulley are. We know from our sum equation that they have to equal 10 lbf. Utilizing the equation F1 over F2 equals e to the mu times pi, I ended up manipulating our original equation given from the free body diagram and plugging in for F1. This in turn gives us only one variable to solve for, this being F2, and thus I was able to solve for F2. After getting the value of F2, I then utilized the simple free body diagram formula I had created and subtracted 10 from the initial value and got my value for F1.

<img width="764" height="637" alt="IMG_0027" src="https://github.com/user-attachments/assets/5e76ffeb-3bd6-4e97-bb98-24d3d962cb9a" />

Next, I then looked at solving for the diameter of this object. I first started with the formula, area equals pi D squared over 4, noticing that I need to figure out what the area of this thing is prior to figuring out what the diameter is in this case. I then recalled the equation for stress and relating that to the safety factor. In doing so, you can solve for area by multiplying the force times the safety factor over the yield strength. I ended up getting the area for that with the specified values. I then plugged the area into the equation, getting a diameter of 0.279 inches. I then also calculated the diameter utilizing, in this case, both the stress and yield strength equations as follows below. After doing so, the 0.279 inches was significantly larger than our other calculated value. After going to the website specified to find the correct pulley, I noticed there was no value of my specific value. I ended up rounding to 5/16, which is significantly close to the value I had calculated. After doing so, I wanted to ensure that this band would fit within our safety factor, specifically for the lower diameter. I ended up taking the maximum force over the minimum area to calculate what the maximum PSI this object may encounter, this being 125 PSI. Utilizing my factor of safety, we can see that my stress allowed for this object is about 157 PSI, meaning that this object will pass and will not break under the conditions.

<img width="1354" height="929" alt="IMG_0028" src="https://github.com/user-attachments/assets/6328749d-0571-41bc-9e64-31543857b9d1" />

Next, I needed to calculate the circumference. Utilizing everything we just calculated, as well as what was given in the formula, I ended up getting a calculated circumference of 20.41 inches. After looking at the website and selecting my diameter of 5/16, I noticed that there is no outer circumference that fits this value. The smallest outer circumference I could utilize for a 5/16 diameter pulley was 24.25 inches. Due to the constraints within the website itself, I will choose that.

<img width="770" height="374" alt="IMG_0029" src="https://github.com/user-attachments/assets/dff9921d-1084-4b35-ba45-a6a2324f10e2" />

## Shaft Design

I first started with the knowns, specifically what was given in the project as well as the things I previously calculated. I ended up choosing the stated material, 1060 hardened steel, specifically with a yield strength of 70300 psi, in this case also requiring a safety factor of 3, depicted as well as my free-body diagram of the shaft and forces acting on it.

<img width="712" height="489" alt="IMG_0030" src="https://github.com/user-attachments/assets/d9a894d5-2168-4381-b312-c3020bd2a413" />

I then needed to try to find the diameter of the shaft. I first noted that I could utilize the circular shaft torsion equation. After manipulating, I ended up getting D is equal to the cube root of 16M times the safety factor, all divided by pi times the yield strength. In this case, I needed to figure out the transmitted torque onto the actual shaft itself. I first started with the power it was experiencing, utilizing the equation P equals R in parentheses F1 minus F2 times the frequency. After doing so, I ended up getting a power of 2,161.1. After taking the power and dividing it by the angular velocity, I ended up getting 13.578 inches per lbf. After plugging these values calculated into the equation, I ended up getting a diameter of 0.144 inches for the shaft.

<img width="1493" height="468" alt="IMG_0031" src="https://github.com/user-attachments/assets/1e204b21-a996-446a-b325-514cae0df153" />

## Bearing Design

I first started with what was given: my previous calculations for F1 and F2, the inner diameter for the bearing, my RPMs, as well as the chosen length. I first started off with finding the pressure this bearing would sustain, simply utilizing the equation force over area. Utilizing the previous calculations as well as the new assumed value, I ended up taking the inner diameter being 0.1875 times the new length and setting that equal to the area. I then took this and took 10 divided by that area and solved for the pressure. Going further, the shaft velocity was then calculated utilizing the speed of 1,500 RPM. After being plugged into the equation, I ended up getting 73.63 feet per minute. Following this, I then calculated the pressure velocity rating, simply multiplying the two together. I ended up getting a value of 3,927 psi feet per minute. I then looked at the table within our McHenry's Handbook and noted that the main limiting factor for the material was the PV value. I had initially looked at some values, specifically the acetal bearing material, and noted it was too small. I then moved up one more to graphite, in parentheses dry. This material fits all of the calculated values I had just calculated and will be the material that this bearing is now made out of.

<img width="1855" height="524" alt="IMG_0032" src="https://github.com/user-attachments/assets/9227f3e7-8c6d-406a-ba60-ed3e2dd3e652" />

### System Frame

<img width="1476" height="958" alt="IMG_0033" src="https://github.com/user-attachments/assets/418a1960-9adf-4208-bfe5-4b5554e0e4b5" />

## Reflection

During the creation of this assignment, I learned quite a lot on the calculation for forces within pulley assemblies. I had previously never done calculations within these types of assemblies, so getting to get some hands-on experience in regards to it and relating it to real-life materials and products was very helpful to visualize the process as well as learn it.





