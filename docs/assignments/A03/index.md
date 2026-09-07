# A3 – Parametric and FEA

## Introduction

Objectives:
1. Use axial deflection modeling to design its dimensions
2. Use parametric design to determine a bars length
3. Introduce you to FEA (Finite Element Analysis)
4. Introduce you to linking dimensions to appropriate parameters in CAD.
5. Compare and contrast the different analysis

Description:

You are to design a bar which has a circular cross section where the values of the criteria given for the material, maximum deflection, and load. Determine the bar’s minimum geometry (ie.. length, diameter, and weight) through parametric design while under direct tension. Then verify the geometry through finite element analysis.

## Design / Calcualtions

<img width="1694" height="1044" alt="IMG_0040" src="https://github.com/user-attachments/assets/d14bc6ef-fe3e-49ea-9f10-773c18b88249" />



In my calculation for the cross-sectional area, I chose a diameter of .25 in, when plugging into the formula I utilized, I got a cross-sectional area of .04909in^2. This value would then later be used in my other calculation to solve for deflection.

<img width="2016" height="886" alt="IMG_0041" src="https://github.com/user-attachments/assets/f8d65364-12bc-4f45-8a6e-0840a1f0d2a2" />



After solving for the beam's cross-sectional area, I then chose some values I would utilize in the beam deflection formula. I chose a force of 400 LBF and a modulus of elasticity of 10,000,000 psi. After plugging in these values, along with the cross-sectional area earlier calculated and the maximum beam deflection, I calculated a beam length of 11.04 in.

## CAD Modeling 

<img width="290" height="265" alt="Screenshot 2026-09-07 143054" src="https://github.com/user-attachments/assets/8a39abac-bbd2-4c43-91b1-28e3d6192d25" /> <img width="1584" height="548" alt="Screenshot 2026-09-07 143252" src="https://github.com/user-attachments/assets/0b1ccfcb-6c21-4190-b778-eee64bc47914" />



Utilizing SolidWorks for my CAD Model, I then created the beam with dimensions I calculated, as shown in the image above, a diameter of 0.25 in, beam length of 11.04 in.

## Material / Global Equations

<img width="487" height="520" alt="Screenshot 2026-09-07 144206" src="https://github.com/user-attachments/assets/a7d24233-51cf-4146-9920-5062ff4f5b72" />


Previous to selecting a material for this project, I had utilized a value of 10,000,000 psi for the modulus of elasticity in my calculations, as it was the average value of the range given in the project. Because of this, I had to find an aluminum alloy that had a similar value to my calculations. I then found 6061-T6(SS) with an elastic modulus of 10007604 PSI. This being a extremly close value to what I had used in my calculations. 

<img width="797" height="327" alt="Screenshot 2026-09-07 145427" src="https://github.com/user-attachments/assets/005450fb-a354-4833-9014-175ac9b3d393" />


I then created the global equations for the beam to utilize SolidWorks to calculate the length of my beam, given the maximum deflection and diameter that I had chosen. When plugging in values, SolidWorks rounded the values; for example, the maximum deflection as well as the cross-sectional area. Though when plugging in all values into the deflection formula, I got the exact same value I calculated for length: 11.04 in.

## Simulation / Safety Factor

<img width="1573" height="482" alt="Screenshot 2026-09-07 150205" src="https://github.com/user-attachments/assets/0e73add0-a21e-448a-a595-f8be40d0f808" />

Prior to starting the simulation, I fixed the left side of my beam to a wall and applied the force I chose being 400 LBF. Though SolidWorks simulation works in newtons, I converted this value and calculated 1779 Newtons.

<img width="1378" height="522" alt="Screenshot 2026-09-07 151140" src="https://github.com/user-attachments/assets/fe8c2a07-fd76-4341-be91-4a85fcea660a" />

I then ran the test, depicted above is the deflection map in the FEA. The maximum deflection this beam experiences during loading is 0.008984 in. The maximum deflection this beam could experience from our calculation was 0.009 in, the simulated deflection is less than the calculated value, so the beam is within the range of deflection.

<img width="1383" height="441" alt="Screenshot 2026-09-07 151011" src="https://github.com/user-attachments/assets/439ee221-e55f-46cb-9984-43cfcc56e249" />

Following the simulation, I then inspected the von Mises Stress map, as depicted above. This simulation concluded that my beam experiences a maximum stress of 8,725 PSI. When comparing this value to the maximum strength of your standard aluminum alloy, this being 40 KSI, my value is significantly under thus, my beam is within the stress it should be experiencing.

<img width="1934" height="832" alt="IMG_0042" src="https://github.com/user-attachments/assets/17827e4a-f31a-4c59-be61-cd61a3137bf1" />

Utilizing the value of 8,725 PSI gathered from my simulation, I then solved for the factor of safety of my beam utilizing the strength of aluminum value provided in the project description. As depicted above in my calculation, I got a FOS of 4.58.

## Design Reflection

A. 
My initial deflection utilized in my hand calculations was 0.009 in, whereas in the FEA simulation I got a value of 0.008984 in. When plugged into the percent difference formula, I got a value of 0.18%. These two values are extremely close to one another;  I think this is partly due to the fact that the design and calculations were very simple. I think if I were to have utilized the exact same value for the modulus of elasticity that the SolidWorks simulation used, this percent difference would be even lower. I think that overall the SolidWorks simulation is more accurate than my hand calculations, as it utilizes more precise numbers than my calculations. 

B.
When taking into account a hole placed on my object, I utilized the equation Stress Peak = Kt * Stress Norm. After looking up the stress concentration factor for a hole in tension, this being Kt = 2.17, I then plugged in the stress I got from the simulation and got a peak stress of 18,900 PSI. When plugged into the FOS equation, utilizing the strength of aluminum value given in the project of 40,000 PSI, I got an FOS of 2.12. This passes the test and allows for some 


## CAD FILE

https://drive.google.com/file/d/14Te_msGYk0CEWIfUVdR_-ymeXZena7MR/view?usp=sharing








