# A6 – Bracket Drawing

## Parametric Design

Below is a 3D schematic created in SolidWorks utilizing the dimensions calculated in the previous assignment A5. Dimensions utilized were taken from the greatest values calculated from both the stress and stiffness calculations done so in A5.

<img width="959" height="1132" alt="Screenshot 2026-09-23 220116" src="https://github.com/user-attachments/assets/be5cd27d-de0d-4ef1-96cf-e1c5497bff41" />

Depicted below is the calculations I got for feature A being utilized and the dimension and drawing with my specific length and diameter calculated previously and utilized in my global variables within SolidWorks.

<img width="1071" height="735" alt="Screenshot 2026-09-26 134027" src="https://github.com/user-attachments/assets/aa8e2de5-4f7a-41b0-8d7f-3dc548dbade7" />

Next is feature B, displaying the thickness I calculated as well as my assumed value of 1.75 inches for feature B, displayed in SolidWorks and shows the conjoining between feature A and feature C in the image depicted below.

<img width="612" height="600" alt="Screenshot 2026-09-26 134149" src="https://github.com/user-attachments/assets/97db1ecc-e401-4e02-99ed-dfb8f0c41a1b" />

Next was my values I calculated for feature C, with a total length of 3.5 and a width of 1.25, all being assumed from my discretion, and utilized in my stress calculation, I got a thickness of 0.6, as depicted on the drawing, and shows the connection C has to the other parts within this design.

<img width="982" height="661" alt="Screenshot 2026-09-26 134219" src="https://github.com/user-attachments/assets/241e7c29-53eb-4a88-bb95-ef22dfbb5215" />

Next is feature D with the depicted calculated value being 0.06 inches. Next is the value of 1.23 inches as I designed it to start from the base of C to go all the way up until when it will mate at E. Because of this, I ended up having to account for the height of C plus the length of D, which was depicted in the initial drawing. Because of this, the correct value that should be technically displayed of the 1.23 is 0.625 for the width of feature D, taking into account the height of feature C, gives a total height of the 1.23 depicted in the image below.

<img width="450" height="576" alt="Screenshot 2026-09-26 134313" src="https://github.com/user-attachments/assets/ca4102cf-4c16-4152-8fd6-0f93c70f975a" />

Next and finally is Part E. Within the image you can see my calculated value for the height of feature E being 0.8 inches, as well as my assumed values of the width of feature E being 1.75 inches, by its length, which is not depicted in the image, this being 1.25 inches. All of this being calculated from the stress equation.

<img width="1404" height="604" alt="Screenshot 2026-09-26 134343" src="https://github.com/user-attachments/assets/b899d509-4a09-4a23-88ca-bae8ca4314d8" />

<img width="398" height="164" alt="image" src="https://github.com/user-attachments/assets/c2cb8c78-1035-418a-aaf1-37e252013d75" />


## Multiview CAD Drawing

Below is the dimentioned 3D drawing of my bracket deisgn with calculated values. In the tollerences chosen were based on the ammount of decimals following utilized in my calculations. 

<img width="1575" height="1218" alt="Screenshot 2026-09-26 155859" src="https://github.com/user-attachments/assets/d35b41f6-1ef4-4cac-b212-33606cd66903" />

## Reflections

A. For feature A, I drove it utilizing the stress equation for a cantilever beam. Utilizing the equations tab, I calculated the allowable stress by dividing it by its material yield, safety factor, and utilized the resulting value in the equation. Rather than just simply entering the value I calculated previously, I put all this into my global variables in SolidWorks and applied it to the actual applied load. After doing so and putting this all into SolidWorks, I got an approximate value of 1.3 inches, very similar to the value I ended up calculating. As for if my calculation changed later in the assignment, it did not specifically alter that piece, though I did change my calculation slightly for part E, as I had some conflicting beliefs as to how thin the actual part was and its calculations. So I redid it utilizing a different value and solved from there.

B. When referring to the tolerances I utilized in my drawing, I ended up using a looser tolerance for the diameter of the object for Feature A. I did this mainly because my calculation resulted to a two-decimal value. Though in the reality of things, I believe that I should be using a tighter tolerance for most of the things I calculated, as they were specifically calculated with a specific safety factor and things in mind. All of the other safety factors and tolerances that I included within my design, I tried to keep within 0.01, as every calculated value I got going forward for things like the thickness of B and C resulted in multi-decimal place values past three decimals. I simply ended up rounding to two to make the tolerance feasible. Though in the grand scheme of things, it's best to make these tolerances as close to one another as possible due to the calculated values. As for function and assembly, with having to include tolerances, I believe that Feature A would have to have a tighter tolerance than what I put because it mates to Feature B, as well as there should be a tolerance that I include on the width of B to account for this. As for everything else, I believe my tolerances are okay where they are, and I didn't include tolerances in dimensions I assumed, this being the 1.75 utilized for my height of Feature B, as well as my length of Feature E, and other similar values like my length of 2.75 for Feature A. These are my justifications for my tolerances for the different features within this design.

## CAD FILE

https://drive.google.com/file/d/1bws2UspjIYuACCmTtm-HtcLVbqdKRe-N/view?usp=sharing
