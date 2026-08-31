# A2 – Truss Stress Analysis

## Objective
## Analyze
For this assignment I got tasked to create and 3D model a truss with the given constraints. 

![My Image](trusscontraints.png)

I'm given that point A is a pin and point B is a roller. Also, I'm given that the length of a is 0.4m and length of b is 0.3m. I was given the choice to choose the value of the external forces of the truss, a value between 20-30kN. I decided to use the value 27 for this assignment. Furthermore, our truss needs to be lightweight, its material has to be A500 steel or a similar alternative.

![My Image](WIN_20260825_23_37_29_Pro.png)

Since our truss has to be light weight, I want to minimize the quantity of beams connected to the truss. Yet, I need to ensure that the truss will be able to support the load. Therefore, to maximize the strength of the truss I designed triangular geometry shape within the truss. 

![My Image](trussdimensions.png)

This is how the truss now looks like with its given dimensions added and choice of force. The next step will be to determine the reaction forces at point A and B, before finding the forces for each member within the truss. For each force I'll draw an arrow for the direction I assume the is. If the calculation of the value, I find is negative I'll flip the arrow so that the calculation can be positive. Also, by doing this the arrow will be pointing in the correct direction whether the point is experiencing compression or tension from the beam. It is also important to keep in mind that the rotation when finding the moment about a point determines the operation sign; counterclockwise rotation gives a positive value while a clockwise rotation gives a negative value.

![My Image](trussreactionforces.png)

Therefore, I start calculating the reaction forces at point A and B, there are 3 reaction forces I need to solve for. Point A is a pin; therefore, it has two unknown reaction forces, one on the x-axis and another in the y-axis, this is because it can't move in the x direction nor the y direction. Applying the same concept at point B means there is only one unknown reaction force at this point, in the y direction. The quantity and direction of reaction forces are determined by imagining on what axis the support can't freely move; there'll be a reaction force in that same direction the support can't freely move. For example, point B has a roller which can move freely in the x direction, therefore, it must have a reaction force on the y-axis since movement on the y-axis is prevented. Ideally when finding 3 reaction forces with 2 supports it would be best to take the moment of the support with the 2 unknown reaction forces. This way the 2 unknown forces at that one support would cancel out, leaving only 1 unknown reaction force to solve for. To calculate moment the formula is the sum of Force*Distance (perpendicular to the force) for each force. By taking the moment about point A the distance is equal to 0, so the values will be 0. Therefore, I was able to calculate By, then to calculate Ax and Ay I summed up the forces in the x and y direction separately to find Ax and Ay.

![My Image](trussinternalfoces.png)

This section includes all the member force calculations with acknowledgment whether the point experiences compression or tension from each member. Also, since I designed the truss, I had to find the angles by using inverse tangent. Fortunately, length and height remained constant throughout the truss meaning isosceles triangles split into right triangles. Therefore, the angle will remain constant at the opposite ends of the isosceles triangle. For the left portion of the truss there isn't an isosceles triangle but there still are right triangles of the same length and height, so the angles can be found by comparing to the previous calculated right triangles. It was best to start by finding the forces at point A first, since there was only one unknown in the y-axis which could be calculated straight forward. After calculating point A I calculated point F since there was only 1 unknown in each the x and y direction. Then, I had decided to calculate for point D just to realize midway that it would be better to calculate point B and C first due to fewer unknowns. This way I would also have less unknown to solve for at point D, because solving internal forces for point C would let me find force in member CD, only 1 unknown at point D.

![My Image](beamcrosssecarea.png)

Knowing the forces that act upon the members of the truss I had to find a minimum cross-sectional area that would be able to withstand the loads. Therefore, to calculate the minimum cross-sectional area required I used the stress formula (stress= Force/Area) and symbolically solved for the area to get the minimum cross-sectional area is equal to the force divided by the stress. Given I chose ASTM A36 steel, since there isn't A500 steel in SolidWorks and it's the most similar, I know the yield strength of the material thanks to this data table. https://ficientdesign.com/a36-steel-properties/ The force used in the calculation was the largest force the truss experienced on a beam. The reason the largest force was chosen is to assure that the other members can 

![My Image](steelthickness.png)

![My Image](weightoftruss.png)

![My Image](pincrosssecarea.png)

![My Image](weightofpins.png)



## Decide
_Which geometry did you select, and why? This is your first open design choice in the course — defend it._

## Communicate

