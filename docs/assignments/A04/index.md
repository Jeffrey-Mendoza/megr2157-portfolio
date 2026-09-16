# A4 – [Motor Mount]

## Objective
This assignment requires us to design a motor mount using the (Brushed 24V DC Gear Motor 3.6Kg.cm/46RPM w/ 99.5:1 Planetary Gearbox) which attaches to the rigid wall A. For both features, first design for yield strength and then design for a maximum deflection of .30 mm at the free end. ABS, PETG,  or PLA may be selected as a motor mount material. When designing the motor mount take into account a safety factor of 3 and neglect the weight of the motor. For steps 1 and 2 draw a FBD of the forces and a concept of the design. Research the design of different motor mounts and place the links in an appendix on the page. Make justifiable approximations in the design to simplify the analysis. (ie. use the beam calculations) Follow Appendix B for the initial approach to set up the design analysis.

![My Image](motorm.png)

Figure 1: Shows motor, the rigid wall and the force received on the shaft of the motor, where P = 300 N

Appendix A:

![My Image](Motord.png)

Appendix B:

![My Image](apendb.png)

## Feature 1

![My Image](feature1.png)

First, I listed all my knowns and unknowns. I decided to use ABS material and chose the lowest stress yield and modulus of elasticity within the range given for the material. Stress yield=29.6 N/mm^2 and modulus of elasticity=1790N/mm^2. Then I decided the length and base of feature one to be 35mm both sides, to create a nice, squared shape. After, I needed to find the bending moment at point A of feature one by multiplying the force times the distance from A perpendicular to the force, 300N times the 18mm. Using the stress maximum formula, I substituted for known variables and rearranged to solve for the height. I made sure to convert all my values so I could get an accurate answer. After testing for the minimum height required for yield strength and maximum deflection, I found my value for the height of feature 1 to be 12.83mm. Since the height minimum for the maximum deflection design is higher than the design for yield strength, I need to use the height calculated for maximum deflection. That way the motor mount won't fail to satisfy both the yield strength and the max deflection.

![My Image](Asec1.png)

To find the area of the rectangle I multiplied it's base times the height value calculated. The area is 449.05mm^2.

## Feature 2

![My Image](feature2.png)

To create my second feature the process was identical to create feature 1. I chose the same material, ABS, with the same yield strength and modulus of elasticity. Initially I had chosen a length of 60mm to cover most of the motor, but later on I changed that to reduce the height for feature 2. I didn't want to have a high value for height because that would make the motor mount look unappealing. Therefore, I went with a length of 40mm by a base of 35mm. I was stumbled upon my second moment due to being confused the location of point A. After figuring it out I calculated moment 2 to be 300N multiplied by (40mm+18mm) which is the perpendicular distance from point A to the force. Like previous the design for yield stress had an output for a lower minimum diameter required of 17.39mm. While the design for maximum deflection had a height value of 20.71mm. Like previously the higher height value was chosen to prevent permanent deformation and elongation past 0.30mm. The area for feature 2 came out to be 724.98mm^2 using the height calculated for feature 2.

## Sketch

![My Image](isodraw.png)

This is the 3D sketch of how my design on SolidWorks will look like, with the dimensions.

## CAD Model

![My Image](a4global.png)

![My Image](feature2sketch.png)

![My Image](feature1sketch.png)

![My Image](f1extrude.png)

![My Image](6diameter.png)

![My Image](cut.png)

![My Image](feature1inner.png)

![My Image](f2hole.png)

![My Image](a4final.png)

[View A4 Multiview Drawing](A4%20Multiview%20drawing.pdf)


## Decide


## Communicate

