# DNA Extraction - Epicentre
### Created by Ravishankar Madhu
Last updated: 2023-07-10

## Description
This protocol describes how to extract DNA from cells and tissues using the MasterPure Complete DNA & RNA Purification Kit. This kit is best used when the input number of cells is less than 1e6 cells. 

## Reagents and Materials 
- Cell Pellets to be extracted
- Lucigen MasterPure DNA Extraction Kit
	- Tissue Cell Lysis Solution
	- Proteinase K
	- RNase A
	- MPC Protein Precipitation Reagent
	- TE Buffer
- Isopropyl Alcohol
- 70% ETOH
- Ice
- 1.5mL Eppendorf Tubes (2 sets per sample)
- Tabletop Centrifuge that can be temperature controlled
- Tabletop incubator and shaker 

## Things to Note before starting
### Handling the Kit
The proteinase K and the RNase A must be stored at -20C. The other buffers can be kept at room temperature. 

### Amount of Cells
This kit is best used when the amount of cells you have is less than 1e6. If you have more than 1e6 cells, use the [[RM019 - DNA Extraction - Qiagen]] protocol. This kit can handle inputs as low as 1e4, but your likelihood of extracting functional genomic DNA decreases with the cell input. 

### Estimated Timing
This protocol is substantially longer than the [[RM019 - DNA Extraction - Qiagen]] protocol due to the several long incubation steps. Therefore, it is expected to complete in 3-4 hours. 


## Procedure
1. Vortex the the tubes containing the cell pellets and any leftover media
2. Create a master mix with the following ratio: 300uL Tissue Cell Lysis Solution and 1uL Proteinase K. You should make 120% of the required Master Mix to account for pipetting errors. (ie for 8 samples, make a Master Mix for 10 samples, for 16 samples make a Master Mix for 20 samples, etc.) [^1]
3. Add 300uL of master mix into each tube and vortex. 
4. Incubate the samples for 15 minutes at 65C and 900rpm [^2]
5. Place the samples on ice for 2 minutes to reduce the temperature down to ~37C 
6. Add 1uL of RNase A to each tube
7. Incubate the samples at 37C for 30 minutes [^3]
8. While the samples are incubating at 37C, set the temperature of a tabletop centrifuge to 4C and seal it up. Then press the Fast Temp button to cool down the centrifuge. When the 30 minute incubation is over, the centrifuge should have reached 4C. 
9. After the incubation, place the samples on ice for 3-5 minutes. 
10. Add 175uL of MPC Protein Precipitation Reagent to each sample. 
11. Invert the samples 40-50 times. As you invert the samples, a milky white precipitate should form. [^4]
12. Spin the samples at Max Speed at 4C for 10 minutes.
13. Using a p1000 pipette, carefully transfer the ==supernatant== from the tube into a new 1.5mL Eppendorf tube without disturbing the pellet. Toss the tube containing the pellet. 
16. Add 500uL of IPA to each sample.
17. Invert the sample 40-50 times. [^4]
18. Spin the samples at Max Speed at 4C for 10 minutes.
19. Aspirate off the supernatant, making sure to not disturb the faint white pellet at the bottom of the tube. 
20. Add 350uL of 70% ETOH to each tube. DO NOT DISRUPT THE PELLET. DO NOT RESUSPEND THE PELLET.
21. Remove 325uL of 70% ETOH from each tube. DO NOT DISRUPT THE PELLET. DO NOT RESUSPEND THE PELLET.
22. Add 325uL of 70% ETOH to each tube. DO NOT DISRUPT THE PELLET. DO NOT RESUSPEND THE PELLET.
23. Remove 325uL of 70% ETOH from each tube. DO NOT DISRUPT THE PELLET. DO NOT RESUSPEND THE PELLET.
24. Using a p200, remove the extra 70% ETOH from each tube without disrupting the pellet. There might still be some ETOH at the bottom. If the pellet gets taken up by the pipette, re-dispense the ETOH and reposition the p200 and try again. 
25. Using a p20, place the pipette at the bottom of the tube (not on the pellet), and take up as much ETOH as possible. 
26. Open the cap to each tube and let the pellets air dry for 10-15 minutes. If the cell pellets are still wet with ETOH, they will appear a solid white color. If the pellet is dry, it will change to be translucent
27. Resuspend the pellet in 20-50uL of TE Buffer. [^5]

## Next Steps
The DNA can be quantified using the [[RM032 - Quantifying DNA with the NanoDrop|NanoDrop]]. They can then be stored in the -20C Freezer until needed. 


## Appendix

### Related Protocols
- [[RM019 - DNA Extraction - Qiagen]]
- [[RM032 - Quantifying DNA with the NanoDrop]]
- [[RM023 - Generic PCR]]


### Footnotes
[^1]: Always make a minimum of 2 extra aliquots of master mix even if that is greater than 20%. For instance, If you are working with 3 samples, make a master mix for 5 samples even though 20% would only be 0.6. 

[^2]: There are tabletop incubators / shakers located in the TC Room by the microscope and in the PCR room by the centrifuge. Heating up the Incubator takes a few minutes but getting the incubator to cool down will take a while. Always turn off the incubator when you are down to allow it to cool  for the next person. 

[^3]: You will have to use a different tabletop incubator than the one you used for the 65C incubation step as it will not have cooled enough to be ready. If all the incubators are being used, you can incubate the samples in the Warm Room. 

[^4]: The best technique to invert them is to place the samples tightly together in a tube rack (leave no empty spots in-between the samples) and place another tube rack above them. While holding the two tube racks tightly, invert the racks, causing the samples to be inverted

[^5]: The amount you resuspend in depends on how concentrated you want the samples to be and how much volume you want to work with. I recommend resuspending them at 20uL as diluting concentrated samples is easier than concentrating a dilute sample. 