
# A6 – [Bracket Drawing]

## Objective

This week's assignment is a continuation from last week designing the bracket by taking the modeling from last week to create a parametric model and a detailed engineering drawing. As part of this assignment, I will need to generate a comprehensive solid model and a multi-view engineering drawing that accurately represents the designed bracket, incorporating all features to ensure both strength and stiffness requirements are met.

<img width="323" height="238" alt="image" src="https://github.com/user-attachments/assets/80380ced-5200-493e-80d9-730bc15f2751" />

## Parametric Design
From last week the goal was to find a dimension that would satisfy a deflection under 0.005in and a dimension that wouldn't fail under stress by using the yield stress of the material. Below are the multiview drawings of both the Stress and Stiffness Analysis, the greater value for each feature is the dimension that will be used in the CAD model design to assure satisfaction to both conditions. Also, since the goal is to satisfy both the stress and deflection condition the final design will contain dimensions from both the Stress Analysis and the Stiffness Analysis.

![My Image](stressmulti.png)

![My Image](deflectdraw.png)

## Final Parametric Design Selection

![My Image](finalpara.png)

After analyzing both the dimension values from the stress and stiffness analyzing 4 of the 5 calculated dimensions came from the stress analysis, always choosing the greater value.

## Bracket CAD Model

![My Image](globalbd.png)

Then, I launched SolidWorks to input the assumed dimensions and calculated dimensions into the global variable feature.

![My Image](parametricbd.png)

After finishing creating the global variables, I was ready to model the design using the global variables to input the dimensions of the design.

![My Image](ginputbd.png)

I had extruded the entire design 1 in, the length of feature top bracket. Therefore, I had to then to add another 0.875 to the length of feature A and B so the length of A+B could be 1.0875. 

![My Image](bdcutnextrude.png)

For feature B I cut extruded 1 in so feature B width could be 0.0875

![My Image](finalbd.png)

The final CAD model of the bracket design.

## Bracket Multiview Drawing

![My Image](bdmulti.png)

The multiview drawing of the bracket design. Also, since feature A has a link, I had chosen an RC4 fit so it could fit pretty smoothly. Therefore, the shaft (cylinder) for feature A has a tolerance of -0.008 to -0.016. Additionally, I added tolerances to 3 other tolerances, for the t design.

## Bracket Reflection

Since the only feature in which stiffness governed was feature E there was only one stiffness calculation used for the final design. This specific dimension calculated for feature E controlled the width of the feature. All the calculated dimensions using the stiffness and stress analysis in the final design was inputted into SolidWorks expressed as an equation using the "equation" feature. The CAD calculation and the handwritten calculation were identical. For the bracket design 4 tolerances were applied, feature A diameter has a sliding fit of RC4, so it had a tolerance of -0.008 to -0.016. On the other hand, the height of feature C had a tighter fit, due to accuracy being necessary, so the tolerance is +0.005 to 0.000. Since feature C is the only dimension that needs high accuracy, this was the only on with a tight tolerance. If I would've added additional tight tolerances the price to manufacture would increase. This assignment took me approximately 6 hours to complete starting from the time I read the instructions.

## 2157 Link

![My Image](globallink.png)

For the CAD model of the link the procedure was similar. I created global variables using the "equations" feature which I later used to set the dimensions of the link model. After doing the calculations for the link dimension from the previous week it was determined that the stress analysis valued governed over the stiffness value. Therefore, the stress analysis value was the width of the link.

## Link CAD Model

![My Image](linkextrude.png)

I used the straight slot feature to create the whole base design of the link and just added the circles and dimensions using the global variables.

![My Image](linkfinal.png)

Afterwards, the geometry was extruded the calculated value of 0.15in to finish up with the CAD model.

## Link Multiview Drawing

![My Image](linkmulti.png)

For this linkage part I had put two custom tolerances for the two desired fits.

## Linkage Reflection

From this extra part of adding a link to the bracket I was able to learn about the importance of tolerance for fitting different parts together. It made me realize that 2 different parts that go together can't be of the same size, one has to be bigger (hole) and the other part needs to be slightly smaller (shaft). The positive tolerance on the hole ensures that the hole will remain bigger than the shaft after manufacture. By inputting alphanumeric tolerance designations for the manufacturer to know what it is that I desire on my part.

[SolidWorks Download](https://1drv.ms/f/c/a88588ba91baf92a/IgD6FAQw-FsYRpZENr3aiTwrAQUuqCoko4gQsBDbDYxFrYI?e=QeQji2)

