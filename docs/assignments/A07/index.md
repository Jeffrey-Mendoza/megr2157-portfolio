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

## Analyze


![My Image](FEAforce.png)
![My Image](defmesh.png)
![My Image](FEAforce.png)

| Design 1| Test 1 (Coarse  Mesh) | Test 2 (Default  Mesh) | Test 3 (Fine Mesh)|
|  :--- | :--- | :--- | :---|
| Max Stress    | 3.306e+09N/m^2 | 3.619e+09N/m^2 | 4.360e+09N/m^2 |
| Max Stress Location | ![My Image](originalstresscoarsemesh.png) | ![My Image](originalstressdefmesh.png)| ![My Image](originalstressfinemesh.png)|
| Max Displacement | 3.848e+01mm | 3.892e+01mm | 3.928e+01mm|
| Max Displacement Location| ![My Image](originaldeflectioncoarsemesh.png) | ![My Image](originaldeflectiondefmesh.png) | ![My Image](originaldelfectionfinemesh.png) |
| Mass(lbs.) | 0.77 | 0.77 | 0.77 |
|Min Factor of Safety| 7.561e-02 | 6.908e-02 | 5.734e-02 |
|FOS location| ![My Image](originalfoscoarsemesh.png) | ![My Image](originalfosdefmesh.png) | ![My Image](originalfosfinemesh.png) |
| Number of Elements| --- | --- | --- |
|Convergence Stress| --- | --- | --- |
|Convergence Deflection| --- | --- | --- |
|Convergence Safety Factor| --- | --- | --- |

| Design 2| Test 1 | Test 2 | Test 3|
|  :--- | :--- | :--- | :---|
| Max Stress    | --- | ---| ---|
| Max Stress Location | --- | ---| ---|
| Max Displacement | ---| ---| ---|
| Max Displacement Location| --- | --- | --- |
| Mass | ---  | --- | --- |
|Min Factor of Safety| --- | --- | --- |
|FOS location| --- | --- | ---|
| Number of Elements| --- | --- | --- |
|Convergence Stress| --- | --- | --- |
|Convergence Deflection| --- | --- | --- |
|Convergence Safety Factor| --- | --- | --- |

| Design 3| Test 1 | Test 2 | Test 3|
|  :--- | :--- | :--- | :---|
| Max Stress    | --- | ---| ---|
| Max Stress Location | --- | ---| ---|
| Max Displacement | ---| ---| ---|
| Max Displacement Location| --- | --- | --- |
| Mass | ---  | --- | --- |
|Min Factor of Safety| --- | --- | --- |
|FOS location| --- | --- | ---|
| Number of Elements| --- | --- | --- |
|Convergence Stress| --- | --- | --- |
|Convergence Deflection| --- | --- | --- |
|Convergence Safety Factor| --- | --- | --- |

## Decide


## Communicate

