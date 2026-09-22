# A5 – [Topic]

## Objective

Conduct stress analysis to determine appropriate dimensions for structural features.

Generate free body diagrams (FBDs) to visualize forces and constraints for each feature.\

Identify and document known and unknown variables, assumptions, and algebraic models for stress calculations.

Perform stiffness analysis to establish minimum required dimensions based on deflection constraints.

Compare stress and stiffness analyses to ensure structural integrity and compliance with given constraints.

Create detailed multiview sketches illustrating dimensions derived from both stress and stiffness analyses.

Reflect on and document key engineering lessons learned throughout the process.

### Description:

Detail design a bracket, using the concept design in Appendix B, to hold a horizontal force applied symmetrically by a strap outline in resource #1. The bracket’s dimensions are designed with different fit classes. Each dimension of the T beam is part of the fit:

“a” intention for use where accuracy is not essential
“b” is about the closest fits that can be expected to run freely
“c” is where accurate location and minimum play is desired

Design using a safety factor of 4 and applied load in between 500 lbf < F < 800 lbf. Choose one of three metals, aluminum 6061 T6, Steel (ASTM A36), or Titanium (Ti-6Al-V4). Furthermore, state assumptions and approximations about the design in order to use fundamental strength of materials analysis. For example, use the proper stress analysis and deflection analysis where appropriate. Assume no failure due to direct shear stress. 

Note: If the bracket is designed symmetrically a lot of work would be cut.

<img width="323" height="238" alt="image" src="https://github.com/user-attachments/assets/d2cdd8a9-1710-4e6f-8410-4a12b540402f" />

### Global Values (Stress/Stiffness)

<img width="1157" height="974" alt="IMG_0001" src="https://github.com/user-attachments/assets/8e7d072a-b4e5-4546-ac76-8e21ae34e2f0" />

<img width="977" height="862" alt="IMG_0007" src="https://github.com/user-attachments/assets/433830aa-db69-4c8e-937b-0adee92d8696" />

## Calculating Dimensions from Stress Analysis

### Feature A

First, I calculated the dimensions of this object utilizing stress analysis. I first started with feature A and went through the knowns and unknowns and the assumptions that I had about the actual object itself. I started off with finding the moment the feature experienced from the 650 force at the end. With this moment, I could utilize this in the stress max equation to then be manipulated. And with plugging in what inertia was for a cylinder, I was then able to manipulate the equation to figure out what the diameter of this piece would be.

<img width="1071" height="1135" alt="IMG_0002 (1)" src="https://github.com/user-attachments/assets/1f8eab3d-32f1-47b5-a409-ee4b09c4c8ba" />

### Feature B

For feature B, we ended up assuming the force on this object was double that due to the pulley pulling downwards. And we also take into account the factor of safety and the stress allowed for all of these equations. I then listed the unknowns and the assumptions we had about this, trying to solve for the thickness of feature B. From our knowns that we know thus far, we know the pressure as well as the stress that's allowed. With some manipulation, we are able to then solve for area. In this case, area is equal to the width times the thickness. Because we know the width value from our assumptions previously, we get our thickness value for feature B.

<img width="1149" height="796" alt="IMG_0003 (1)" src="https://github.com/user-attachments/assets/df0d87c1-f10f-4af7-92c0-86ea94449bca" />

### Feature C

For feature C, we have the direct force of 650 pounds force acting downwards and our known length of 3.5 inches, as well as our width, assumed to be 1.25 inches, the same stress allowed. We are trying to figure out the minimum thickness feature C can withstand with these values and assume uniform cross-sectional area as well as the force. I then figure out the moment acting on this object to then be plugged into the stress formula and be manipulated with the inertia formula. After doing so and plugging in inertia and manipulating, I end up getting a thickness of 0.6 inches.

<img width="1509" height="893" alt="IMG_0004 (1)" src="https://github.com/user-attachments/assets/ab49a15b-74aa-448b-a791-16ec48f26a30" />

### Feature D

Moving on to feature D, we assume for each part in reference to this has half of the force acting on it. We assume a width of 0.625 inches and have the same stress allowed. We're trying to solve for the minimum thickness this object can have with the assumptions as follows below. I first calculate what the area is utilizing the same formula as previously used and simply manipulate the area equation to figure out the thickness.

<img width="1560" height="954" alt="IMG_0005 (1)" src="https://github.com/user-attachments/assets/174b53e3-0a0d-439f-947d-9f95698b9834" />

### Feature E

Moving on to feature E, we assume a force of 650 acting on this part of the object, with an assumed length of 1.75 inches and width of 1.25, with the same stress allowed. We try to solve for the minimum beam height with the constraints. I first solve for the moment acting on this object, plugging into the same stress formula that we utilize, and then manipulate the equation to solve for h and get my answer.

<img width="1064" height="909" alt="IMG_0006 (1)" src="https://github.com/user-attachments/assets/783e1716-7144-404a-8743-9e9d14736e2c" />

## Calculating Dimensions from Stiffness Analysis

### Feature A

For Figure A, there's a force of 650 pounds force with a length of 2.75 and the material values given in the general global values. We are trying to determine the diameter with these new limiting factors. First we start off with the deflection formula, noting that we know almost everything within the formula except for inertia. We then figure out what inertia is and plug in that value in. After doing some simple manipulation and trying to get the diameter by itself, we're able to then plug in all the values and get your diameter is equal to 1.164 inches.

<img width="1479" height="1163" alt="IMG_0008 (1)" src="https://github.com/user-attachments/assets/cfc78d59-6a99-4b1d-a6a5-bf6f4ff12d67" />

### Feature B

Moving on to Figure B, we have the same dimensions as previously stated and shown below, assuming the same factors. This time we say the deflection value and then solve for the area utilizing deflection. Once we do this, we know area is just equal to the width times the thickness. Because of this, we're trying to solve for the thickness of this object, so we separate everything and solve for T and plug in our values and get a value, as all shown below.

<img width="1965" height="1130" alt="IMG_0009" src="https://github.com/user-attachments/assets/c741ff70-0036-4aa9-afcb-a429866cfbc9" />

### Feature C

See we're utilizing the exact same dimensions as in stress as with the rest of these problems, trying to figure out the minimum thickness, utilizing the deflection formula for this and plugging in the value we have for inertia and breaking it up. We can then separate everything and solve for t and get a value, this being 0.481 inches.

<img width="2028" height="1100" alt="IMG_0010" src="https://github.com/user-attachments/assets/fd8bab64-e367-48eb-af0a-a4ee88962cf2" />

### Feature D

For D, we ended up using a P-value of F over 2 due to the 2 being separated on either side, taking into account either part, utilizing the same dimensions, trying to find the minimum thickness. We relate this first to the deflection, then solve for the area. Saying that area is equal to the width times the thickness, we can then separate everything and solve for the thickness, plug in, and find our value.

<img width="1800" height="927" alt="IMG_0011" src="https://github.com/user-attachments/assets/dcad38ac-7dad-4067-9cbb-b4d6c1487862" />

### Feature E

E, we have the exact same dimensions and force as shown in Figure E4 stress. We first start off with the deflection formula, noting that we do not know inertia. So we find out what inertia is, plug that into our deflection formula. Once that is done so, we know all values except for h. We can separate h and solve and end up getting a height of 0.606 inches.

<img width="1592" height="1048" alt="IMG_0012" src="https://github.com/user-attachments/assets/79040e74-e0f4-4de6-9612-b34c3bd6e88c" />

## Multiview Sketches

### Stress

<img width="1633" height="982" alt="IMG_0013" src="https://github.com/user-attachments/assets/ff0646b9-2a95-48e9-bb87-f0dd033ef855" />

### Stiffness

<img width="1649" height="945" alt="IMG_0014" src="https://github.com/user-attachments/assets/2ab78177-f358-47e9-8cc8-4e54d4f2fb1e" />

## Lessons Learned

1. For feature one, the difference between the stiffness and stress was slightly notable. For stress, I got 1.30 inches, where stiffness I got 1.164 inches. This slight difference of about 0.1 inches in diameter shows the importance of taking into account the deflection and strength of this material.
2. One value that was carried into later on throughout the entire process was the force value of 650 lbf. Different features utilized this value differently, where Feature B utilized double the force, while D had used half of it. Prior to doing these calculations with the load, I analyzed them to make sure the symmetry of the load distribution applied consistently to these features, so it wouldn't cause an error downstream in my calculations.
3. One assumption that I made was to utilize aluminum in this case, with a specific yield strength of 35,000 psi and a Young's modulus of 10 million psi. If a lower strength alloy or material were used, the allowable stress would significantly decrease, and the final dimensions would have to increase to account for this. Material selection is extremely important in this regard because, depending on the properties, it will adjust the dimensions of my product significantly, whether it's a weaker or stronger material. Also including the safety factor.


