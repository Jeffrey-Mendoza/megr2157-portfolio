# A7 – [FEA]

## Objective

Use Finite Element Analysis (FEA) to improve the bracket design from previous assignments.

Ensure high stiffness, strength, and lightweight optimization through iterative design.

Conduct multiple FEA simulations, refining geometry based on results.

Perform static stress analysis, including constraints, loading, and meshing selection.

Interpret data by identifying max stress, displacement, and safety factors.

Optimize the design by modifying geometry to enhance performance.

Document the entire process with images, calculations, and insights.

Reflect on key engineering lessons learned and time spent.

Task is simply to create a high stiff, high strength, and lightweight component. Use Finite Element analysis to drive decision making process throughout the design. Each step of the analysis and before a geometric change is made make sure the component’s results (stress/displacement/Safety Factor) converge on a 7% difference. Achieve this by modifying the number of elements. If after three attempts to converge use the stiffness and stress from the finer mesh size use the finest mesh size and proceed through the process.

##Bracket Design

![My Image](bracketdesign.png) 

## Bracket FEA

![My Image](FEAforce.png)

Firstly, the orginal design was tested to see how it performs with the expected load.

| Design 1| Test 1 (Coarse  Mesh) | Test 2 (Default  Mesh) | Test 3 (Fine Mesh)|
|  :--- | :--- | :--- | :---|
| Max Stress    | 3.306e+09N/m^2 | 3.619e+09N/m^2 | 4.360e+09N/m^2 |
| Max Stress Location | ![My Image](originalstresscoarsemesh.png) | ![My Image](originalstressdefmesh.png)| ![My Image](originalstressfinemesh.png)|
| Max Displacement | 3.848e+01mm | 3.892e+01mm | 3.928e+01mm|
| Max Displacement Location| ![My Image](originaldeflectioncoarsemesh.png) | ![My Image](originaldeflectiondefmesh.png) | ![My Image](originaldelfectionfinemesh.png) |
| Mass(lbs.) | 0.77 | 0.77 | 0.77 |
|Min Factor of Safety| 7.561e-02 | 6.908e-02 | 5.734e-02 |
|FOS location| ![My Image](originalfoscoarsemesh.png) | ![My Image](originalfosdefmesh.png) | ![My Image](originalfosfinemesh.png) |
| Number of Elements| 1533 | 8391 | 52197 |
|Convergence Stress| NA | 9.47% | 20.48% |
|Convergence Deflection| NA | 1.14% | 0.92% |
|Convergence Safety Factor| NA | 8.64% | 17% |

For this design I had though some ribs connected to the sides of the clyinder could help the load to distribute up on the bracket.

| Design 2| Test 1 | Test 2 | Test 3|
|  :--- | :--- | :--- | :---|
| Max Stress    | 1.953e+08N/m^2 | 2.690e+08N/m^2 | 6.799e+08N/m^2|
| Max Stress Location | ![My Image](design2stresscoarsemesh.png) | ![My Image](design2stressdefmesh.png) | ![My Image](design2stressfinemesh.png) |
| Max Displacement | 1.442e-01mm | 1.506e-01mm| 1.529e-01mm |
| Max Displacement Location| ![My Image](design2deflectioncoarsemesh.png) |  ![My Image](design2deflectiondefmesh.png) |  ![My Image](design2deflectionfinemesh.png) |
| Mass (lbs) | 0.86  | 0.86 | 0.86 |
|Min Factor of Safety| 1.280e+00 | 9.293e-01 | 3.677e-01 |
|FOS location| ![My Image](design2foscoarsemesh.png) | ![My Image](design2fosdefmesh.png) | ![My Image](design2fosfinemesh.png) |
| Number of Elements| 1670 | 8361 | 56807 |
|Convergence Stress| NA | 37.74% | 152.75% |
|Convergence Deflection| NA | 4.44% | 1.53% |
|Convergence Safety Factor| NA | 27.4% | 60.43% |

For the last design I made an immense number of changes, I made a lot of cutout sections with fillets intending to reduce mass while increasing safety factor. Additionally, I made tapered ribs for load distribution, increased the width of the bracket sides

| Design 3| Test 1 | Test 2 | Test 3|
|  :--- | :--- | :--- | :---|
| Max Stress    | 1.752e+08N/m^2 | 1.797e+08N/m^2 | 1.404e+08N/m^2 |
| Max Stress Location | ![My Image](design3stresscoarsemesh.png) | ![My Image](design3stressdefmesh.png) | ![My Image](design3stressfinemesh.png) |
| Max Displacement | 3.757e-02mm | 3.780e-02mm | 3.831e-02mm |
| Max Displacement Location| ![My Image](design3deflectioncoarsemesh.png) | ![My Image](design3deflectiondefmesh.png) | ![My Image](design3deflectionfinemesh.png) |
| Mass(lbs) | 1.31  | 1.31 | 1.31 |
|Min Factor of Safety| 1.427e+00 | 1.391e+00 | 1.780e+00 |
|FOS location| ![My Image](design3foscoarsemesh.png) | ![My Image](design3fosdefmesh.png) | ![My Image](design3fosfinemesh.png) |
| Number of Elements| 8702 | 15537 | 61250 |
|Convergence Stress| NA | 2.57% | 21.87% |
|Convergence Deflection| NA | 0.61%% | 1.35% |
|Convergence Safety Factor| NA | 2.52% | 27.97% |

##2157 Link

The original link design was tested to see how well it does without any modifications to the design.

| Design 1| Test 1 (Coarse Mesh) | Test 2 (Default Mesh) | Test 3 (Fine Mesh)|
|  :--- | :--- | :--- | :---|
| Max Stress    | 2.138e+08N/m^2 | 2.177e+08N/m^2 | 2.182e+08N/m^2 |
| Max Stress Location | ![My Image](link1stresscoarsemesh.png) | ![My Image](link1stressdefmesh.png) | ![My Image](link1stressfinemesh.png) |
| Max Displacement | 3.620e-02mm | 3.637e-02mm | 3.639e-02mm |
| Max Displacement Location|  |![My Image](link1deflectioncoarsemesh.png) | ![My Image](link1deflectiondefmesh.png) | ![My Image](link1deflectionfinemesh.png) |
| Mass(lbs) | 0.14  | 0.14 | 0.14 |
|Min Factor of Safety| 1.169e+00 | 1.148e+00 | 1.146e+00 |
|FOS location| ![My Image](linkfoscoarsemesh.png) | ![My Image](link1fosdefmesh.png) | ![My Image](link1fosfinemesh.png) |
| Number of Elements| 1236 | 7179 | 56321 |
|Convergence Stress| NA | 1.82% | 0.23% |
|Convergence Deflection| NA | 0.47% | 0.06% |
|Convergence Safety Factor| NA | 1.79% | 0.17% |

In attempt to reduce stress concentration I added a layer for distribution where the load was located.

| Design 2| Test 1 | Test 2 | Test 3|
|  :--- | :--- | :--- | :---|
| Max Stress    | 2.236e+08N/m^2 | 2.312e+08N/m^2 | 2.346e+08N/m^2 |
| Max Stress Location | ![My Image](link2stresscoarsemesh.png) | ![My Image](link2stressdefmesh.png) | ![My Image](link2stressfinemesh.png) |
| Max Displacement | 3.827e-02mm | 3.848e-02mm | 3.842e-02mm |
| Max Displacement Location|  |![My Image](link2deflectioncoarsemesh.png) | ![My Image](link2deflectiondefmesh.png) | ![My Image](link2deflectionfinemesh.png) |
| Mass(lbs) | 0.14  | 0.14 | 0.14 |
|Min Factor of Safety| 1.118e+00 | 1.081e+00 | 1.066e+00 |
|FOS location| ![My Image](link2deflectionfosmesh.png) | ![My Image](link2fosdefmesh.png) | ![My Image](link2fosfinemesh.png) |
| Number of Elements| 1425 | 7431 | 52900 |
|Convergence Stress| NA | 3.40% | 1.47% |
|Convergence Deflection| NA | 0.55% | 0.16% |
|Convergence Safety Factor| NA | 3.31% | 1.39% |

Afterwards, I realized that just makes the deflect in the x direction as well now. So, I added another layer on the other side with a thicker part in the center to prevent bending. Additionally, I added some oval holes with fillets where there was no stress to remove mass where it isn't needed.

| Design 3| Test 1 | Test 2 | Test 3|
|  :--- | :--- | :--- | :---|
| Max Stress    | 2.423e+08N/m^2 | 1.898e+08N/m^2 | 1.916e+08N/m^2 |
| Max Stress Location | ![My Image](3stresscoarse.png) | ![My Image](3stressdefmesh.png) | ![My Image](3stressfine.png) |
| Max Displacement | 3.625e-02mm | 3.662e-02mm | 3.674e-02mm |
| Max Displacement Location|  |![My Image](3deflectcoarse.png) | ![My Image](3deflecdefmesh.png) | ![My Image](3deflecfine.png) |
| Mass(lbs) | 0.22  | 0.22 | 0.22 |
|Min Factor of Safety| 1.032e+00 | 1.317e+00 | 1.305e+00 |
|FOS location| ![My Image](3deflectcoarse.png) | ![My Image](3fosdefmesh.png) | ![My Image](3fosfine.png) |
| Number of Elements| 2495 | 9065| 57949 |
|Convergence Stress| NA | 21.67% | 0.95% |
|Convergence Deflection| NA | 1.02% | 0.33% |
|Convergence Safety Factor| NA | 27.62% | 0.91% |

## Engineering Lesson

Throughout this assignment I discovered and learned how to do static analysis on CAD models that I create to approximate how well it could function in the real world. Additional I learned about the different type of meshes, there are three types: coarse, default, and fine mesh. Finer mesh just breaks the CAD model into smaller geometric shapes; therefore, fine mesh allows for accurate reading especially around complex shapes. Yet more geometric shapes mean it'll take the system to proceed the static analysis. Whereas coarse mesh are bigger geometric shapes, so it is less likely to pick up small high stress sections, so less precise. Also, the computer processes coarse mesh quicker compared to fine mesh. Lastly default mesh is simply a mix of both coarse and fine mesh. Also, I learned tapered ribs and fillets help reduce stress concentrations; therefore, it was added to the design attempting to increase safety factor. Analyzing models is something that is exciting to do, I desire to improve at reducing weigh will maintaining stiffness. This assignment took me approximately 5 hours to do.

## SolidWorks Download

[Download Bracket](A6%20bracket.SLDPRT)

[Download Link](Link.SLDPRT)





