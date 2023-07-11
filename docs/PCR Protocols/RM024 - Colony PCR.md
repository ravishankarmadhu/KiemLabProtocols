# Colony PCR
### Created by Ravishankar Madhu
Last updated: 2023-07-10

## Description
This protocol describes how to run PCRs on individual colony's picked from a CFU assay. This protocol already assumes you have the individual colonies stored in QuickExtract Buffer.

## Reagents and Materials 
- Picked single colonies stored in QuickExtract Buffer
- DI-H20 [^1]
- 10X PCR Buffer
- 10mM dNTPs
- 50uM MgCL2
- Taq Polymerase [^2]
- 20uM Forward Primer
- 20uM Reverse Primer

## Things to Note before starting
### Estimated Timing
Colonies have to be lysed before they can go into the PCR. Lysing takes ~30 minutes while the PCR takes ~3 hours. 


## Procedure
1. The individual colonies should be stored in PCR Tubes already containing QuickExtract Buffer. Place the tubes into a Thermocycler with the following program:

| Temp | Time       |
| ---- | ---------- |
| 65C  | 20 Minutes |
| 100C | 10 Minutes |
| 4C   | Hold           |

2. Take out the 10X PCR Buffer, 50uM MgCl<sub>2</sub>, 10mM dNTPs, 20uM Forward Primer,  and 20uM Reverse Primer from the -20C Freezer and let them thaw at room temperature. ==DO NOT TAKE OUT THE TAQ POLYMERASE. ==
3. Assign each colony a number from 1-N. This will reduce the amount of labeling you will have to do. Record your assignment to ensure you to not forget it. 
4. Label new PCR Tubes with the numbers 1-N to correspond to each sample. 
5. Turn on the PCR Thermocycler that you plan to use before creating the Master Mix. [^3]
6. The following is a 1X Recipe for the the Master Mix. Scale up depending on how many samples you have. Always make more master mix than the number of samples you have to account for pipetting error. Add the items in the order in which they appear on the list. Take out the Taq Polymerase out of the -20C Freezer after all  other reagents have already been added to the Master Mix. Return the Taq Polymerase to the -20C immediately after use. Create the Master Mix in a 1.5mL Eppendorf Tube

| Reagent               | Volume  |
| --------------------- | ------- |
| DI-Water              | 15.05uL |
| 10X PCR Buffer        | 2.5uL     |
| 50uM MgCl<sub>2</sub> | 1.0uL   |
| 10mM dNTPs            | 0.5uL     |
| 20uM Forward Primer   | 0.375uL   |
| 20uM Reverse Primer   | 0.375uL   |
| Taq Polymerase        | 0.20uL  |
| TOTAL                 | 20uL        |

7. Mix Master Mix by pipetting up and down with a p1000
8. Move labeled tubes into the PCR Tube Freezer Block
9. Add 20uL of Master Mix to each tube
10. Add 5uL of Extracted Colony to the corresponding PCR Tube
11. Spin down the PCR Tubes using a tabletop PCR Tube centrifuge
12. Take the PCR Tubes to a thermocycler and apply the following program:

- Step 1: 94C for 3 minutes
- Cycling Step: Repeat for **35** Cycles
	- 94C for 30 seconds 
	- ==Annealing Temp== for 30 seconds
	- 72C for 45 seconds
- Step 3: 72C for 5 minutes
- Hold at 4C

To calculate your **annealing temperature**, go to https://tmcalculator.neb.com/#!/main and fill in the brand of polymerase you are using, the concentration of your primers, and your primer sequences.

## Next Steps
After the PCR is complete, the product should be ran on a gel to determine the phenotype of the individual colony. 


## Appendix

### Related Protocols
- [[RM025 - DNA Electrophoresis]]
- [[RM010 - Creating CFCs Plates]]


### Footnotes
[^1]: Rather than using the same bottle of DI-H20, it is customary to create 1mL aliquots of DI-Water in the Hood. Each time you run a PCR use a new aliquot of DI-Water. After the PCR has been run, toss the bottle to prevent any contamination of the water supply. 

[^2]: The particular brand of Taq polymerase you use has slight differences on the PCR Program you eventually run and the composition of the Master Mix. For instance, some brands pre-make the master mix while other brands will provide the individual reagents. For best results, read the documentation provided with your reagents. 

[^3]: Thermocyclers can take some time to turn on. Therefore, turn on the thermocycler before creating the master mix to ensure that as little time is spent at room temperature. 