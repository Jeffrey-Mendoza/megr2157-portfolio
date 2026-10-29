# A8 – Gears

## Objective

Design a gearbox which can be assembled and disassembled. The spur gears have a gear ratio of 24:9 and are listed in the resource section. The output gear torque and speed are to be 1.25 in-lbf and 1100 rpm relative. The input (pinion,power-transmission) and output (gear, short shaft) shaft diameters are .125 and .25 inches respectively and each have a length of 1 inch. Use the appropriate equations in the Machinery’s Handbook for empirical units. The critical features of the gearbox include the shafts, and the journal bearings.

Assumptions: 

Assume appropriate strength of shafts, use Machinery’s Handbook.
The gear train is ideal.
The moment of the radial force from the gear train is small enough to be ignored.
Note:

The shafts are press fit through the hubs of the gears.
Make sure there is enough clearance between the gears and the gearbox.
Use a running sliding fit for the size of the hole for the shafts.


## Input & Output Shaft Calculation
 First of all, I had to run calculations to make sure the given shaft diameters were sufficient enough to undergo the shear stresses that would be present with the gears.

![My Image](calculations11.png)

![My Image](shaftsufficient1.png)

After calculations it was determined that both shaft diameters were indeed sufficient and wouldn't fail under the shear stresses that would be present.

## Journal Bearings

Next to be able to select a journal bearing material I had to calculate the force, radial force, velocity, pressure, and PV constant using the max velocity and pressure values.

![My Image](journalbearing1.png)

## Journal Bearing Material Selection

By comparing all the max values of pressure and velocity, along with the PV constant, to the material chart I decided to go with nylon. I chose nylon because it would be able to handle the velocity and pressure of the gear assembly. Additionally, it's the cheapest material of the list, making it less expensive to produce. Also, I wanted to consider in safety factor and a PV constant of 3000 for nylon is slightly above a x1.5 safety factor which I was satisfied with.

![My Image](PVvalues1.png)

![My Image](1-4thjournalbearing.png)

![My Image](1-8thjournalbearing.png)

https://www.mcmaster.com/6389K2/

## Housing Sketch

After researching some different gearbox housing designs, I decided to just create a simple box housing for the gear assembly.

![My Image](sketchgear1.png)

## CAD Model

![My Image](parametricgear.png)

![My Image](basehousing.png)

![My Image](bottomhousing.png)

![My Image](gearwitbottomhousing.png)

![My Image](tophousing.png)

To create the top housing all I did was mirror the bottom housing to create an identical housing for the top portion.

![My Image](screws.png)

This image demonstrates the locations of where the tapped holes went. This image was where the screws would go but were too large, but I fixed it before adding the tapped holes into the assembly.

![My Image](sectionview.png)

From this view it is visible that the gears have enough room so they can move freely.

![My Image](assembly.png)

Unfortunately I couldn't add screws and nuts ( which I had intially thought about) because I dont have access to that on my solidworks, and from mcmaster I couldn't download any screw.

## Engineering Lesson

From this assignment I gained additional knowledge on gears and how they are housed. I learned how to know which journal bearing material to choose depending on the pressure, velocity, and the PV constant of the gear assembly.

## 2157 Multiview Drawing

![My Image](1of4shaftdrawing.png)

![My Image](1of8shaftdrawing.png)

![My Image](1of4journalbearingdrawing.png)

![My Image](1of8journalbearingdrawing.png)

![My Image](bottomhousingdrawing.png)

![My Image](tophousingdrawing.png)

![My Image](gearhousingdrawing.png)

## CAD Download

[Download](./A8/)


