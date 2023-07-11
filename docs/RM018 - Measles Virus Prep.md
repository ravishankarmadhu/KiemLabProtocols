# Measles Virus Prep
### Created by Ravishankar Madhu
Last updated: 2023-07-10

## Description
This protocol describes how to create measles pseudo typed lentivirus vector who's targeting can be controlled depending on mutations to the ΔH plasmid. This protocol uses 4 plasmids for the creation of a viral particle. 
- ΔF: This plasmid is important for the measles virus to exist. It remains unchanged within our system.
- ΔH: This plasmid is edited and changed depending on what targeting moiety we want to target or not target. 
- GeneMarked Plasmid: This introduces a GFP, mCherry, or mScarlet gene marking. Changes depending on the needs of an experiment. 
- p22: A necessary plasmid for the creation of a complete infectious particle. Remains unchanged. 

## Reagents and Materials 
- Plasmids
	- ΔF
	- ΔH
	- Gene Marked Plasmid
	- p22
- [[RM034 - List of Commonly Used Lab Buffers#DMEM++ Buffer|DMEM++ Buffer]]
- Serum Free DMEM
- HEK 293T Adherent Cells
- Trypsin
- [[RM034 - List of Commonly Used Lab Buffers#0.1% Gelatin|0.1% Gelatin]]
- IMDM Media
- 150 mm Plates
- 50mL Centrifuge Tubes
- High Speed Ultra Centrifuge
- [[RM034 - List of Commonly Used Lab Buffers#LV-Max Production Media|LV-Max Production Media]]

## Things to Note before starting
### Estimated Timing
This protocol takes a week from plating the cells on gelatin coated dishes to resuspending the virus. The protocol assumes you have a stock of HEK293 cells on the first day to plate on gelatin coated plates. 


## Procedure
### Day +0 (Monday)
1. Warm the [[RM034 - List of Commonly Used Lab Buffers#0.1% Gelatin|Gelatin Solution]] in the hot water bath to ensure the gelatin particles are suspended.
2. Determine how many plates of virus you will generate. The normal range for virus production ranges from 4 plates to 20 plates. 
3. Coat 150mm plates with 10mL of the [[RM034 - List of Commonly Used Lab Buffers#0.1% Gelatin|Gelatin Solution]]. 
4. Swirl the 150mm plate to ensure the [[RM034 - List of Commonly Used Lab Buffers#0.1% Gelatin|Gelatin Solution]] covers the entire surface of the plate.
5. Take up the [[RM034 - List of Commonly Used Lab Buffers#0.1% Gelatin|Gelatin Solution]] using a serological pipette, a thin layer of [[RM034 - List of Commonly Used Lab Buffers#0.1% Gelatin|Gelatin Solution]] should remain on the surface of the plate. 
6. Collect the HEK293 cells that you grew over the weekend and count to determine the total number of cells you have. 
7. Plate 6.5e6 - 10e6 HEK293 cells in 25mL of [[RM034 - List of Commonly Used Lab Buffers#DMEM++ Buffer|DMEM++ Buffer]] per plate. [^1]
8. Label plates and place them in the 37C Incubator Overnight. 

### Day +1 (Tuesday)
1. Take the plates out of the incubator and look at the cells under the microscope to ensure the plate is confluent. If the plate is not 80-90% confluent, delay the virus prep for an additional day to allow the cells to grow. 
2. Determine the ratio of plasmids per Plate. Our ratio for the Measles Virus is the following:
	- 10ug of the ΔH plasmid
	- 10ug of the ΔF plasmid
	- 27ug of the Gene Marked Vector
	- 17.5ug of p22
3. Create a Transfection Solution with the ratio of plasmids in 2mL of Serum Free DMEM with 3uL of 1ug/uL PEI per 1ug of DNA. [^2]
4. Vortex the transfection solution and let the solution incubate for 10-15 minutes at room temperature.
5. Aliquot solution dropwise onto the plates.

### Day +2 (Wednesday)
1. Approximately 17 hours after adding the transfection solution, aspirate off the transfection media. 
2. Add 20mL of [[RM034 - List of Commonly Used Lab Buffers#LV-Max Production Media|LV-Max Production Media]] to each plate
3. Return plates to the 37C Incubator

### Day 4 (Friday)
1. Filter the supernatant of the plates through a 0.45um vacuum filter. 
2. Transfer the virus containing supernatant to 50mL centrifuge tubes.
3. Spin them down at 5000 rpm in an ultracentrifuge at 4C overnight. Ensure the samples are balanced properly. 

### Day 5 (Saturday)
1. Take the samples out of the ultracentrifuge, a very small pellet should be at the bottom of the tube. (Do not be worried if you cannot see a pellet)
2. Aspirate off supernatant, being careful not to disrupt the pellet a the bottom. 
3. Place the tubes upside down over a paper towel to allow for any liquid to drain off.
4. Resuspend the "pellet" in 100-400 uL of IMDM media. [^3]
5. Pipette up and down vigorously to break up the pellet.
6. Place in the fridge for 30-60 minutes to loosen the pellet.
7. Aliquot virus into smaller 200uL tubes at 25-50uL / tube. 

## Next Steps
The produced virus can be Tittered (quantify the infectious potential). After they have been Tittered, they can be used in ex-vivo and in-vitro experiments. 


## Appendix

### Related Protocols
- [[RM021 - Plasmid MiniPrep - Qiagen]]
- [[RM022 - MaxiPrep Protocol]]

### Recipe's for Buffers
#### DMEM++ Buffer

This buffer mix is used for culturing HEK293 T Cells. Specifically for use in virus prep. This should be stored in the TC Room Fridge.

- 500mL DMEM Media
- 50mL Heat Inactivated Cosmic Calf Serum
- 5.5mL of PenStrep
- 5.5mL of Sodium Pyruvate (100X)
- 5.5mL of Non-Essential Amino Acids (100X)
- 5.5mL of L-Glutamine (100X)
- Sterilized by filtering through a 0.22um Vacuum Filter

#### 0.1% Gelatin

This reagent is used to coat the plates during a viral transfection. It should be stored in the TC Room Fridge but should be warmed in the hot bath prior to use to ensure all the gelatin has dissolved properly.

- 50mg of Gelatin
- Dissolved in 50mL of DI-H20
- Solution should be left in the hot water bath and vortexed periodically to allow for the gelatin to completely dissolve


### Footnotes
[^1]: Divide the total number of HEK293 cells you have by the number of Virus Plates you are generating to determine how many cells / plate you can do at maximum. If that number is larger than 10e6 then plate a maximum of 10e6 cells. You can plate less than 6.5e6 cells, but that might delay the cells from being confluent by the next day. 

[^2]: This is best calculated by using a spreadsheet.  

[^3]: Ask before hand to determine how much to resuspend the virus in. A rule of thumb is that it should be 1/100th of the volume of the virus containing supernatant that was spun down. 