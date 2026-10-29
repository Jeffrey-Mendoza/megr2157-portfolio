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

![My Image](PVvalues1.png)

![My Image](1-4thjournalbearing.png)

![My Image](1-8thjournalbearing.png)

## Housing Sketch

![My Image](sketchgear1.png)

## CAD Model

![My Image](parametricgear.png)

![My Image](basehousing.png)

![My Image](bottomhousing.png)

![My Image](gearwitbottomhousing.png)

![My Image](tophousing.png)

![My Image](screws.png)

![My Image](sectionview.png)


 
 
 
 
 
 
 
 

## Decide


## Communicate

