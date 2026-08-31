# A2 – Truss Stress Analysis

## Objectives

1. Design a lightweight planar truss using A500 steel or an alternative material.
2. Create free body diagrams (FBDs) for joints and critical pins.
3. Calculate the required cross-sectional area of truss elements with a safety factor.
4. Determine pin sizes based on shear forces with a safety factor.
5. Solve equations symbolically and numerically for both truss and pin design.
6. Estimate the total weight of the truss and pins.
7. Create a CAD model with accurate dimensions and connections.
8. Compare CAD weight predictions with hand calculations.
9. Document key engineering lessons learned from the process.

## Documentation

I was tasked with creating a truss system with the parameters as follows.

<img width="317" height="215" alt="image" src="https://github.com/user-attachments/assets/64b394ad-5eb7-4831-9edc-1b44ba3330e7" />

Force P = 20KN a = .4 m, b = .3 m

## Design Geometry

<img width="2360" height="1099" alt="IMG_0035" src="https://github.com/user-attachments/assets/68c246ce-a098-4e90-9d75-5937b51b2f90" />
This image depicts the truss geometry I selected with the assignment's constraints. My intention with this design was to make the truss as simple as possible while being able to carry the required amount, and being as lightweight as possible to reduce the cost of this truss. This design utilizes a limited number of members, and due to its simplistic design, calculations on internal and external forces are much more straightforward.

<img width="2360" height="1279" alt="IMG_0036" src="https://github.com/user-attachments/assets/af7d6af2-1137-481b-8ab9-29bda26c8f18" />
This image shows my process of solving for external supports utilizing the free-body diagram (FBD) I created along with the geometry of this project. I applied static equilibrium to the truss by first taking a moment about pin B and getting the reaction at pin A. I then summed my forces in the y-direction, as I only had one unknown, and found the reaction force at B.

## Internal Forces

<img width="2053" height="1181" alt="IMG_0037" src="https://github.com/user-attachments/assets/e4730f26-a80a-49e4-9718-0922ba8f6285" />
This image shows my work done utilizing the method of joints to solve for the internal forces in each truss member. I analyzed each pin at a time utilizing equilibrium to determine whether the different members were in tension, compression, or a zero-value force. This step allowed me to visualize and see what members were under the most tension or compression and calculate real values to utilize in calculations regarding stress and shear.

## Member Cross Sectional Area / Weight

<img width="2198" height="790" alt="IMG_0038" src="https://github.com/user-attachments/assets/52d1dbed-37c6-4126-8de6-3efd02e1e13a" />
These calculations show how I arrived at the minimum required cross-sectional area for the truss members utilizing the largest internal force experienced in the truss. I utilized an average stress limit of 315MPA for A500 steel in this calculation. I related the normal stress equation to the allowable design stress, utilized 315MPA as my limit stress, and utilized the maximum force experienced by the truss being 16.02KN. After plugging in the values, I obtained a minimum cross-sectional area of 178mm2. 


I then calculated the total weight of the truss, first calculating the total length of the truss to then find the total volume of the truss. Once I had arrived at the volume of the truss, I utilized the density of A500 steel, this being 7850 kg/m3, to find the mass of the system, and then multiplied the mass previously calculated by the acceleration due to gravity to get the total weight of the system.

## Pin Cross Sectional Area / Weight

<img width="1297" height="1297" alt="IMG_0039" src="https://github.com/user-attachments/assets/397df1b0-4262-4968-a331-ea777b6c757d" />

These calculations show my process in finding the minimum cross-sectional area for the pin connections of the truss system. I utilized the shear equation and related it to the allowable design shear equation and manipulated the equation to solve for cross-sectional area. I utilized the maximum internal force experienced being 16.02KN and converted the given 170KSI to MPA to solve in units of mm2, resulting in an answer of 54.7mm2.

I then next calulated the weight of the total pins. I first found the length of the members, then multiplied that by the cross-sectional area to find the volume of an individual pin. I then converted it into in3 to then multiplied that given volume by the provided densicy 0.278ln/in3 to find the mass of a pin. I then multiplied this value by 5, taking into account the total number of pins being used in this design, and finally multiplied this value by the acceleration due to gravity to get a total weight of 0.275N.



## Decide
_Which geometry did you select, and why? This is your first open design choice in the course — defend it._

## Communicate

