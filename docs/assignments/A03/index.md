# A3 – Parametric and FEA

## Introduction

Objectives:
Use axial deflection modeling to design its dimensions
Use parametric design to determine a bars length
Introduce you to FEA (Finite Element Analysis)
Introduce you to linking dimensions to appropriate parameters in CAD.
Compare and contrast the different analysis

Description:
You are to design a bar which has a circular cross section where the values of the criteria given for the material, maximum deflection, and load. Determine the bar’s minimum geometry (ie.. length, diameter, and weight) through parametric design while under direct tension. Then verify the geometry through finite element analysis.

## Design / Calcualtions

<img width="1694" height="1044" alt="IMG_0040" src="https://github.com/user-attachments/assets/d14bc6ef-fe3e-49ea-9f10-773c18b88249" />



In my calculation for the cross-sectional area, I chose a diameter of .25 in, when plugging into the formula I utilized, I got a cross-sectional area of .04909in^2. This value would then later be used in my other calculation to solve for deflection.

<img width="2016" height="886" alt="IMG_0041" src="https://github.com/user-attachments/assets/f8d65364-12bc-4f45-8a6e-0840a1f0d2a2" />



After solving for the beam's cross-sectional area, I then chose some values I would utilize in the beam deflection formula. I chose a force of 400 LBF and a modulus of elasticity of 10,000,000 psi. After plugging in these values, along with the cross-sectional area earlier calculated and the maximum beam deflection, I calculated a beam length of 11.04 in.

## CAD Modeling 

<img width="290" height="265" alt="Screenshot 2026-09-07 143054" src="https://github.com/user-attachments/assets/8a39abac-bbd2-4c43-91b1-28e3d6192d25" /> <img width="1584" height="548" alt="Screenshot 2026-09-07 143252" src="https://github.com/user-attachments/assets/0b1ccfcb-6c21-4190-b778-eee64bc47914" />



I then created the beam with the dimensions that I calculated, as shown in the images above, a diameter of 0.25 in, beam length of 11.04 in.

## Material / Global Equations

<img width="487" height="520" alt="Screenshot 2026-09-07 144206" src="https://github.com/user-attachments/assets/a7d24233-51cf-4146-9920-5062ff4f5b72" />


Previous to selecting a material for this project, I had utilized a value of 10,000,000 psi for the modulus of elasticity in my calculations, as it was the average value of the range given in the project. Because of this, I had to find an aluminum alloy that had a similar value to my calculations. I then found 6061-T6(SS) with an elastic modulus of 10007604 PSI. This being a extremly close value to what I had used in my calculations. 

<img width="797" height="327" alt="Screenshot 2026-09-07 145427" src="https://github.com/user-attachments/assets/005450fb-a354-4833-9014-175ac9b3d393" />


I then created the global equations for the beam to utilize SolidWorks to calculate the length of my beam, given the maximum deflection and diameter that I had chosen. When plugging in values, SolidWorks rounded the values; for example, the maximum deflection as well as the cross-sectional area. Though when plugging in all values into the deflection formula, I got the exact same value I calculated for length: 11.04 in.

