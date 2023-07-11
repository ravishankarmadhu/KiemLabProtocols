# NHP Ex-Vivo Transplant
### Created by Ravishankar Madhu
Last updated: 2023-07-10

## Description
This protocol will detail the entire process to preform an NHP Ex-Vivo Transplant. While there are different ways to perform the gene editing, this protocol will describe the process for a retrovirus transduction of the Stem Cells - but other editing strategies are possible. Additionally, this protocol will detail the entire process, which will involve linking to several other protocols. 

## Reagents and Materials 
These are reagents that are only used during the Ex-Vivo Transplant. For the reagents used by linked aspects, see their original protocol. 

- [[RM034 - List of Commonly Used Lab Buffers#Stem Cell Media|Stem Cell Media]]
- Retronectin Plated glassware
- non-TC Treated Glassware
- Protamine Sulfate
- Reterovirus for gene therapy (with known Titer)
- Hanks Buffer
- 10mM PGE2

## Things to Note before starting
### Estimated Timing
The protocol can be separated into multiple phases. Phase 1 is collecting the animals baseline details. Phase 2 is the Day -1 (Monday) which is the CD34+ enrichment. Phase 3 is D0 (Tuesday) where the HSCs are gene edited. Phase 4 is D1 (Wednesday) in which the infusion product is made. For each phase, it is important that this task is your full responsibility for that day. 


## Procedure
### Phase 1 - Preparation for the Transplant. 
1. Before the animal is treated with any mobilization, take a baseline PB time point. During this time, also ask for Serum. 

Baseline PB can be processed using the following protocols:
- [[RM001 - PB or BM Lyse for WBC Isolation]]
- [[RM006 - Staining Cells for Flow]]
- [[RM007a - NHP Lineage Panel]]
- [[RM007b - NHP HSC Panel]]

The Serum can be processed using the following protocol:
- [[RM005 - Isolating NHP Serum and Plasma]]

2. If you will be editing the HSCs with a retrovirus, then you have to create retronectin coated plates. Use the following protocol. 
	- [[RM017 - Coating Plates with Retronectin]]

3. Make the following buffers
	- [[RM034 - List of Commonly Used Lab Buffers#Hemolytic Buffer|Hemolytic Buffer]]
	- [[RM034 - List of Commonly Used Lab Buffers#MACS Buffer|MACS Buffer]]
	- [[RM034 - List of Commonly Used Lab Buffers#Stem Cell Media|Stem Cell Media]]

### Phase 2 - Day(-1) - CD34+ Enrichment
1. Record how much BM you received. 
2. Ensure you collect aliquots of the following conditions to [[RM006 - Staining Cells for Flow|analyze via Flow]]: BM WBCs before enrichment, CD34+ Cells, and CD34 Neg Cells. 

3. Lyse BM in accordance with [[RM001 - PB or BM Lyse for WBC Isolation]].
4. Complete the CD34+ Enrichment in accordance with [[RM002 - CD34+ Enrichment]].


5. Stain the CD34 Neg, pre-enriched BM, and an aliquot of the CD34+ with the [[RM007b - NHP HSC Panel|HSC Panel]] for analysis.
6. Stain the rest of the CD34+ with the [[RM007b - NHP HSC Panel|HSC Panel]] to sort for the CD34+CD90+ Cells. 
7. Provide Stefan with aliquots of the [[RM034 - List of Commonly Used Lab Buffers#Stem Cell Media|Stem Cell Media]] in 15mL Centrifuge Tubes so that he can collect the sorted Stem Cells.  
8. Collect the sorted CD34+CD90+ cells and the CD34+CD90- from Stefan. 
9. Count both fractions using the [[RM030 - Counting with the Countess|Countess]]. 
10. Plate the cells in non-TC treated glassware at a concentration of 1e6 / mL. 

### Phase 2 - D(0) - Gene Editing
This portion of the protocol will change depending on how you plan to preform the Edit. Editing via Cas9, vs Base Editor, vs Virus will all have their different peculiarities. This protocol will give the instructions for a retrovirus. Speak with Emily or Greta for protocols for Base Editing / Electroporation / Nanoparticles. 

1. Before you begin, speak with Stefan regarding how you want to dose your cells with Virus. 
To do this we need to establish what MOI of Virus we will use. The MOI is the ratio of number of infectious particles to number of cells. The virus that we use will have a Titer (amount of infectious particles per mL of virus solution). So if we want to have an MOI of 10 for 2e6 cells - we need to use 20e6 infectious particles of virus. 

2. Look at the cells you cultured overnight and ensure they are still alive.
3. Harvest the cells using [[RM034 - List of Commonly Used Lab Buffers#Stem Cell Media|Stem Cell Media]] and then wash with Hanks Buffer into a 50mL / 15mL Centrifuge tube. [^1]
4. Spin the cells down at 800 x g for 5 minutes. Aspirate to the pellet.
5. Resuspend the cells in 1mL of [[RM034 - List of Commonly Used Lab Buffers#Stem Cell Media|Stem Cell Media]]. [^2]
6. Count the cells with the [[RM030 - Counting with the Countess|Countess]].
7. Dilute the cells with [[RM034 - List of Commonly Used Lab Buffers#Stem Cell Media|Stem Cell Media]] so that the cellular concentration is 1e6 / mL. [^3]
8. Add Protamine Sulfate at a concentration of 4 ug / mL. [^4]
9. Add virus at the appropriate MOI that you calculated. [^5]
10. Culture the cells in the appropriate retronectin coated glassware. 

### Phase 3 - D(1) - Creating the Infusion Product
1. Look at the cultured edited cells under the microscope to ensure they are alive and well. 
2. Harvest cells using [[RM034 - List of Commonly Used Lab Buffers#Stem Cell Media|Stem Cell Media]] and then wash with Hanks Buffer to ensure all cells are collected into a 50mL / 15mL Centrifuge tube. [^1]
3. Spin the cells down at 800 x g for 5 minutes. Aspirate to the pellet. 
4. Resuspend the cells 1mL of [[RM034 - List of Commonly Used Lab Buffers#Stem Cell Media|Stem Cell Media]]. 
5. Count the cells with the [[RM030 - Counting with the Countess|Countess]].
6. If there are more than 5e6 cells, dilute the solution to a concentration of 5e6 cells / mL with Stem Cell Culture Media. 
7. Add 1uL of 10mM PGE2 per 1mL of cells. 
8. Incubate the cells on ice for 2 hours, making sure to vortex the solution every 30 minutes at the lowest setting. [^6]
9. During the incubation time, Heat Inactivate an aliquot of serum from the baseline serum draw by placing it in a 56C incubator for 30 minutes. 
10. Create a 2% Autoserum solution by combining 500uL of heat inactivated serum with 24.5mL of Hanks Buffer. 
11. After the incubation, wash the cells with Hanks Buffer and spin down at 800 x g for 5 minutes. Aspirate to the pellet. 
12. Based on the previous cell count, resuspend the cells in the appropriate volume of Hanks buffer so that the concentration will be 1e6 per 1mL.
13. Count the cells with the [[RM030 - Counting with the Countess|Countess]].
14. Take small aliquots of each fraction (~50uL) for flow analysis with the [[RM007b - NHP HSC Panel|HSC Panel]]
15. Pool the cells.
16. Wash the cells with Hanks Buffer and spin down at 800 x g for 5 minutes. Aspirate to the pellet. 
17. Resuspend cells in 10mL of 2% Autoserum solution. 
18. Draw up the cells into a 20mL Syringe with a 16G Needle. 
19. Wash the tube with 10mL of Hanks Buffer, draw that up into the 20mL Syringe.
20. Cap the Infusion product needle. 
21. Place inside a Styrofoam box with ice. 
22. Bring to the Primate Center. 


## Next Steps
There are some other steps that occur in parallel while the Transplant is occurring that contribute to the overall data. 
- On D-1 after the CD34+ Enrichment and sorting cells:
	- make sure you collect data from the Bulk BM PreEnrichment, CD34+ BM, and CD34Neg BM all stained with the [[RM007b - NHP HSC Panel|HSC Panel]]
	- [[RM010 - Creating CFCs Plates|Creating CFC Plates]] - for CD34+, CD34-, CD90+, and CD45RA
- On D1 after making the Infusion Product
	- Run the aliquots of CD90+ and CD90- with the [[RM007b - NHP HSC Panel|HSC Panel]] to characterize their purity
	-  [[RM010 - Creating CFCs Plates|Creating CFC Plates]] - from the aliquots of the infusion product. 


## Appendix

### Related Protocols
- [[RM001 - PB or BM Lyse for WBC Isolation]]
- [[RM002 - CD34+ Enrichment]]
- [[RM006 - Staining Cells for Flow]]
- [[RM007b - NHP HSC Panel]]
- [[RM007a - NHP Lineage Panel]]
- [[RM005 - Isolating NHP Serum and Plasma]]
- [[RM017 - Coating Plates with Retronectin]]
- [[RM010 - Creating CFCs Plates]]
- [[RM030 - Counting with the Countess]]

### Recipe's for Buffers
#### Hemolytic Buffer

This reagent is used to lyse the RBCs from a sample of PB or BM to isolate only the WBCs. This should be stored in either the cold room, or in the TC Room Fridge if being used.

- 32.1 g of Ammonium Chloride
- 4.03 g of Sodium Bicarbonate
- 0.8 mL of 500mM EDTA
- 4L of Water
- Sterilized by filtering with a 0.22um Vacuum Filter

The recipe can be scaled down depending on the volume of Hemolytic Buffer you need. Most commonly, this recipe is made in 1L (Divide everything by 4) or in 500mL (Divide everything by 8).

#### MACS Buffer

This reagent is used to keep cells undergoing a CD34+ Enrichment stable and happy. This should be stored in either the cold room, or in the TC Room Fridge if being used.

- 2.5g of Bovine Serum Albumin
- 2mL of 0.5M EDTA
- 500mL PBS
- Sterilized by filtering with a 0.22um Vacuum Filter

#### Stem Cell Media

This buffer is used to culture stem cells collected after a CD34+ Enrichment. The buffer should stored in the TC Room Fridge and is stable for up to 1 month.

- 50mL SFEMII Media
- 500uL of PenStrep
- 50uL of TPO Cytokine
- 50uL of SCF Cytokine
- 50uL of FLCT3 Cytokine
- Sterilized by filtering through a 0.22um SteriFlip Filter


### Footnotes
[^1]: Use 50mL if you have a lot of culture from the overnight. Use 15mL if the harvest + the wash will fit in it. 

[^2]: Usually the cell counts for CD90+ and CD90- are very low (less than 20e6) so resuspending them in 1mL provides good resolution for counting on the Countess, but feel free to resuspend the pellet in less or more buffer depending on your cell count. 

[^3]: If there are less than 1e6 cells, keep the volume at 1mL. 

[^4]: This is the step of retrovirus transduction that I am least comfortable with. I would double check this number with Stefan or Anne-Sophie. 

[^5]: Usually you add the virus in 2 batches. Adding half the MOI during this step. Then adding another half MOI of virus directly into the culture 7 hours later. 

[^6]: Make sure to set a timer for 30 minutes. It is important to ensure the PGE2 is pulsed consistently. 

