# Generic PCR
### Created by Ravishankar Madhu
Last updated: 2023-07-10

## Description
This protocol describes the how to assemble a PCR Master Mix at 50uL Volume and how to create a PCR program on the Thermocycler. It does not describe how to design PCR primers. 

## Reagents and Materials 
- DI-H20 [^1]
- 10X PCR Buffer
- 50uM MgCl<sub>2</sub>
- 10mM dNTPs
- 20uM Forward Primer
- 20uM Reverse Primer
- Taq Polymerase [^2]
- DNA to amplify
- 1.5mL Eppendorf Tube
- PCR Strip Tubes
- PCR Tube Freezer Block

## Things to Note before starting
### DNA Concentration
The concentration of your DNA should range from 50 ng/uL to 200ng/uL. Samples that are too dilute, might fail to amplify due to lack of DNA. Samples that are too concentrated might fail due to an imbalance with the PCR Chemistry. If errors in PCR amplification occur, try adjusting your input DNA concentration. 

### Estimated Timing
Assembling the Master Mix can take up to 30 minutes. The actual PCR program takes ~2 hours to complete. 


## Procedure
### Creating the Master Mix
1. Take out the 10X PCR Buffer, 50uM MgCl<sub>2</sub>, 10mM dNTPs, 20uM Forward Primer,  20uM Reverse Primer, and DNA from the -20C Freezer and let them thaw at room temperature. ==DO NOT TAKE OUT THE TAQ POLYMERASE. ==
2. Assign each DNA Sample a number from 1-N. This will reduce the amount of labeling you will have to do. Record your assignment to ensure you do not forget it. 
3. Label PCR Tubes with the numbers 1-N to correspond to each sample. 
4. Turn on the PCR Thermocycler that you plan to use before creating the Master Mix. [^3]
5. The following is a 1X Recipe for the the Master Mix. Scale up depending on how many samples you have. Always make more master mix than the number of samples you have to account for pipetting error. Add the items in the order in which they appear on the list. Take out the Taq Polymerase from the -20C Freezer when all  other reagents have already been added to the Master Mix and return the Taq Polymerase to the -20C immediately after use. Create the Master Mix in a 1.5mL Eppendorf Tube

| Reagent               | Volume  |
| --------------------- | ------- |
| DI-H20              | 39.25uL |
| 10X PCR Buffer        | 5uL     |
| 50uM MgCl<sub>2</sub> | 1.5uL   |
| 10mM dNTPs            | 1uL     |
| 20uM Forward Primer   | 0.5uL   |
| 20uM Reverse Primer   | 0.5uL   |
| Taq Polymerase        | 0.25uL  |
| TOTAL                 | 48uL        |

3. Mix Master Mix by pipetting up and down with a p1000.
4. Move labeled PCR Tubes onto the PCR Tube Freezer Block.
5. Add 48uL of PCR Master Mix to each PCR Tube.
6. Add 2uL of DNA sample into their corresponding PCR Tube. 
7. Spin down PCR Tubes using a tabletop PCR Tube Centrifuge.
8. Place the samples into the Thermocycler and run the corresponding protocol. 

### Creating the PCR Protocol
Normally, you would place the samples into the Thermocycler and run the corresponding program. However, below, I outline how to generate the PCR program. 

- Step 1: 94C for 3 minutes
- Cycling Step: Repeat for ==X== Cycles
	- 94C for 30 seconds 
	- ==Annealing Temp== for 30 seconds
	- 72C for 45 seconds
- Step 3: 72C for 5 minutes
- Hold at 4C

The **number of cycles** is usually 35. 

To calculate your **annealing temperature**, go to https://tmcalculator.neb.com/#!/main and fill in the brand of polymerase you are using, the concentration of your primers, and your primer sequences.

If issues arise with your PCR, try adjusting your annealing temperature and number of cycles until the problem resolves. If the problem persists, look at the documentation on your Taq Polymerase and see if they have alternative temperatures for Step 1 and Step 3. 

## Next Steps
PCR Products can be stored at 4C for up to 2 months. They can be immediately run on a Gel to asses amplification or can be run through a PCR Clean Up Kit to remove excess PCR Reagents. Amplicons can be sequenced by Sanger Sequencing with the Genomics Core. 


## Appendix

### Related Protocols
- [[RM025 - DNA Electrophoresis]]
- [[RM019 - DNA Extraction - Qiagen]]
- [[RM032 - Quantifying DNA with the NanoDrop]]


### Footnotes
[^1]: Rather than using the same bottle of DI-H20, it is customary to create 1mL aliquots of DI-Water in the Hood. Each time you run a PCR use a new aliquot of DI-Water. After the PCR has been run, toss the bottle to prevent any contamination of the water supply. 

[^2]: The particular brand of Taq polymerase you use has slight differences on the PCR Program you eventually run and the composition of the Master Mix. For instance, some brands pre-make the master mix while other brands will provide the individual reagents. For best results, read the documentation provided with your reagents. 

[^3]: Thermocyclers can take some time to turn on. Therefore, turn on the thermocycler before creating the master mix to ensure that as little time is spent at room temperature. 