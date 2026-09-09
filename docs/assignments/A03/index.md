# A3 – [Topic]

## Objective
Design for stiffness by designing a bar using two types of analysis, axial deflection modeling to design its dimensions using parametric design to determine a bars length and get introduced to FEA (Finite Element Analysis). With a max bar axial deflection of 0.009in, material of Aluminum, circular cross-sectional area, and a direct load between 300lbf-500lbf. Get introduced to linking dimensions to appropriate parameters in CAD and compare and contrast the different analysis.

## Analyze

## Parametric Design
![My Image](newwritten.png)

I had the decision to choose the values for the cross-sectional area of the circular bar. Therefore, since it has to be hollow there must be 2 diameters, an inner and outer diameter. That being said the formula for the cross-sectional area is 3.14(diameter outer^2- diameter inner^2)/4. Therefore, I chose the values to be 9in for the outer diameter and 6in for the inner diameter. With these values the cross-sectional area of the hollow circular rod comes out to 35.34in^2. Thickness is the outer diameter minus the inner diameter divided by 2 to give us a thickness of 1.5in. In this assignment it was allowed to choose a force value between 300lbf-500lbf; it is also allowed to choose the modulus of elasticity value within the range of 8.5x10^6-11.5x10^6psi. So, I choose the force value of 400lbf or 1779.289N and the modulus of elasticity to be the lowest, 8.5x10^6psi. Also, being able to choose our area, force, and modulus of elasticity allows for the length required to be found knowing the max axial deflection, modulus of elasticity, force, and area. After inputting values I found that a minimum length of 6758.78in is required to have a maximum deflection of 0.009in, which seems kinda lengthy.

##CAD Parameters

![My Image](newg.png)

The "Equations" feature was used to input "Global Variables" so that each variable can gain a value. Therefore, all the known variables were inputted to use later on throughout the CAD model. Yet, for the value of length we used the same formula previously used to find length. Operations using the global variables was used to find the length on Solid Works. Solid Works computed the value 6758.78in for the length, which is the same value I calcualted.

![My Image](roddiameter.png)

After, I started on the circular cross-sectional area by giving the outer diameter its Global Variable value of 9in. Next was the inner diameter which was given a value of 6in. When inputting these values I made sure it was computed with the value from the Global Variables feature, by adding an equal sign before the diameter value, giving the sigma symbol.


![My Image](newrod.png)

When the diameters of the rod were ready, the circles were extruded using the boss extrude feature, the rod was extended to 6758.78in. This was the determined minimal length required based on the given information and selected dimensions for diameter.

##CAD Fixed Geometry and Force Feature
![My Image](newgeo1.png)

Next up was the use of the fixed geometry feature, I made the left edge or face of the rod fixed so that it wouldn't move when tested.

![My Image](newforce.png)

Afterwards, on the other edge or face of the rod I applied the force of 400lbf using the external loads feature.

![My Image](material.png)

Before testing the circular hollow rod, I made sure to apply the aluminum material so that the calculations would input the material property such as modulus of elasticity. I used Aluminum 1060 Alloy with a value of 69000N/mm^2 for modulus of elasticity which is equal to 10.007x10^6psi. N/mm^2=psi/145.038

##CAD Diagrams
![My Image](newstress.png)

According to the test the maximum stress experienced by the beam is 8.743x10^4N/m^2. This is lower than the strength of aluminum of 40psi or 2.7579x10^8N/m^2 and the strength of the 1060 alloy valued at 2.757x10^7N/m^2. To find the safety of factor the formula is, SF= yield strength/ stress max. So, using the value from outline, SF= 2.7579x10^8N/m^2 / 8.743x10^4N/m^2= a safety factor of 3154.41. Whereas, using the value from SolidWorks SF= 2.757x10^7N/m^2 / 8.743x10^4N/m^2 = a safety factor of 315.44. That being said, the experienced stress is significantly lower than both yield strengths.

![My Image](newdisplace.png)

This graph shows the axial deflection of the bar to be a maximum of 1.969x10^-1mm= 0.1969mm= 0.007752in. Our allowed max axial deflection is no more than 0.009in, meaning the circular rod I created satisfied the condition being under 0.009in axial deflection. 

![My Image](newdeform.png)

This CAD image shows the deformation of the model.

![My Image](Newfos.png)

This calculates the factor of safety and got the same value I had gotten of 315 with slightly different decimals, due to rounding most likely. 

## Decide

From the parametric written calculation, I had used the maximum axial deflection value of 0.009 to find my length. Therefore, 0.009in should've been the max displacement experienced on the rod during the test. Yet, the maximum displacement calculated by SolidWorks during the study is 0.007752in, a lower value then what it should've been.

## Communicate
