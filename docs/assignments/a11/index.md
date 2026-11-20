# A11 – Motor Selection

## Objective

Develop the motorized drive and structural integration for the 2 kN tensile tester, focusing on motor selection, mounting, frame stability, and clamp design. This phase will ensure that the crosshead moves smoothly under controlled torque and speed while maintaining precise load alignment and secure specimen gripping.

## Motor Selection- Jeffrey

![My Image](Motorselection.png)

The Nema 23- 76in-oz Maximum Holding Torque was chosen as it is several times above the max torque. Additionally, according to the speed vs torque graph the motor can withstand both the max speed and the max torque. Also, this one was selected compared to the Nema 23 73in-oz because it is half the price due to more wiring, but it is sturdier. 

<img width="1050" height="811" alt="image" src="https://github.com/user-attachments/assets/753fe89f-acc5-49d4-942c-9feb700ced29" />

<img width="1007" height="763" alt="image" src="https://github.com/user-attachments/assets/44508c53-061c-4501-8c39-9b7fe3a07671" />


## Motor Mount Bracket- Jeffrey

![My Image](motormount.png)

After designing for the thickness of the motor mount I went to McMaster to look for a motor mount for the frame size of Nema 23, but there was none. Therefore, after further research I found some nema 23 motor mounts on Amazon sold by the [STEPPERONLINESTORE](https://www.amazon.com/stores/STEPPERONLINE/page/CC42C048-C998-462F-9C8C-189225C4412C?lp_asin=B00Q6GIO5K&ref_=ast_bln&store_ref=bl_ast_dp_brandlogo_sto).

<img width="679" height="756" alt="image" src="https://github.com/user-attachments/assets/c1850e39-4a7d-402b-837e-53935863996b" />


## Coupler Design/Selection- Jeffrey

![My Image](Coupler.png)

A rigid shaft coupling was selected because compared to flexible shaft couplings the rigid shaft coupling can handle higher torques, the catch though is the shafts, must be aligned.

<img width="1050" height="811" alt="image" src="https://github.com/user-attachments/assets/79e63e66-271b-46c7-b61a-658051378901" />


## Analyze and Design Frame Connector- Jeffrey

![My Image](frame.png)

First, I looked at corner brackets on McMaster to find one that would fit the width of the rails, I only found one with a length of 4.5in there it would cover almost the whole length of the tensile tester with 2 brackets on each long side. Afterwards I checked that it would be safe to use and it was several, several times higher than the forces.

<img width="1050" height="811" alt="image" src="https://github.com/user-attachments/assets/4d89356b-48cf-4058-958a-aaae5dda046a" />


## FEA Top Frame

## FEA Vertical Components

## Design Floating Bearing Mount

## Bills of Materials and Labor Costs

| Item Number | Quantity | Name | Cost/Item | Total Cost | Purchase Link |
|  :--- | :--- | :--- | :---| :--- | :---|
| 1 |  2 | Set Screw shaft coupling | $13.60 | $27.20 | [Product](https://www.mcmaster.com/2424K11/) | 
| 2 | 8 | Black Flush 90 degreee bracket for 1.5" High Rail T-Slotted framing | $23.43 | $187.44 | [Product](https://www.mcmaster.com/47065T791/) |
| 3 | 2 | Stepper Motor | $64.79 | $129.58 | [Product](https://www.mcmaster.com/6627T611/) |
| 4 | 1 | T-slot Framing | $264.97 | $264.97 | [Product](https://www.grainger.com/product/80-20-T-Slot-Framing-System-Rectangle-804T48) |
| 5 | 2 | Alloy Steel Acme Lead Screw | $57.73 | $115.46 | [Product](https://www.mcmaster.com/93410A111/) |
| 6 | 2 | 932 Bearing Bronze Acme Flange Nut, Right Hand, 3/8"-12 Thread Size | $111.78 | $223.56 | [Product](https://www.mcmaster.com/95120A592/) |
| 7 | 1 | Multipurpose 6061 Aluminum Bar, 3" Thick x 3" Wide x 1 Foot Long (Crosshead) | $136.42 | $136.42 | [Product](https://www.mcmaster.com/9008K62-9008K621/?s=rectangular+bar) |
| 8 | 2 | STEPPERONLINE NEMA 23 Stepper Motor (Economy Geared Stepper Motor) Alloy Steel Mounting Bracket ST-M2 | $7.87  | $15.84 | [Product](https://www.amazon.com/STEPPERONLINE-Stepper-Economy-Mounting-ST-M2/dp/B00Q6GIO5K/ref=sr_1_5?dib=eyJ2IjoiMSJ9.iS38cgRotT5SeegZRPZilBOPG1-Ao-fGY91I_yUoH8lJ1ZQFkW4nh-8DEm9HpFokYm3X2FzScOnFb8zop1fn_IeXPxTjaFfs5oavwk8BTV4R1AGs9n_a1U51-4Y7v6C4TE7Zm5ArvQsW-i_0GnoPhPlQff8kT6QAXVX46woMEbaxZK9NwsVf6lQmMfI55YhwOhhBoJY6Lz8zZ40J-PoqwDHsHdSPacI_KxuTeuAPrCM.lIo6LBEiNI6sbf9kdVXQv882PcXcZiVX9ly28rWIKxo&dib_tag=se&keywords=nema+23+mount&qid=1795061247&sr=8-5) |


Material Cost: $1630.31

| Name | Total Hours | Rate | 
|  :--- | :--- | :--- |
| Jonathan Suarez | 7 | $35 |
| Jeffrey Mendoza | 10 | $35 |
| Landyn Sherill | 15 | $35 |

Labor Cost: 

Total Cost: 

## Engineering Lesson

Jeffrey- From my sections for this assignment I learned how to select a motor based on the minimum and maximum speed, as well as the max torque. Additionally, I learned more about the components in a tensile tester, like the shaft coupler. I learned how to approximately select a shaft coupler similar to selecting a motor, based on speed and torque. The time it took to complete my sections for this assignment took me approximately 6 hours including reading and documentation.

Jonathan- This section taught me how to calculate the costs of a project. I also learned how to make an assembly drawing with a bill of materials list. This section took me about 3 hours


## 2157

![myimage](A11crosshead.png)
![myimage](A11assembley.png)

### CAD

[Individual parts](https://1drv.ms/f/c/3f1fcb01952d5efb/IgBbZ_eFpj1eQLZSCEd0bIP8AcsQWQcFh7Pm_f8MQ_e-BLU?e=dq3HUh)

[Assembly and drawings](https://1drv.ms/f/c/3f1fcb01952d5efb/IgAyMsc5PbrDTaHPiDHUyfcsARXFC63HeprnS3U8AbTyAx8?e=aPseXD)



