# MaxiPrep Protocol
### Created by Ravishankar Madhu
Last updated: 2023-07-10

## Description
This protocol describes how to take a bacterial culture of a large size(up to 500mL), and collect  plasmid DNA by using the Purelink HiPure Filter MaxiPrep Kit from Invitrogen. (https://www.thermofisher.com/order/catalog/product/K210017). 

## Things to Note before starting
### Kit Choice
Please ensure you are using the Filter version of the Invitrogen MaxiPrep kit. The non-filter version might be cheaper, but the procedure is harder. There are also 2 variants of this protocol based on whether you want the plasmid DNA on the same day or the next day. The same day protocol, as the name implies, will give you the product on the day you start the procedure, but at a cost of DNA yield. The next day variant increases DNA yield, but at the cost of a delay in time.

### Estimated Timing
The steps involving the column take about 2 hours. There is an additional 2 hours of centrifuging. Overall, the entire procedure from bacterial culture to plasmid can take about 6-8 hours. 

## Reagents
- The Purelink HiPure Filter MaxiPrep Kit
		- R3 (Resuspension Buffer)
			- contains RNAse
	- L7 (Lysis Buffer)
	- N3 (Neutralization and Precipitation Buffer)
	- W8 (Wash Buffer)
	- EQ1 (Equilibration Buffer)
	- E4 (Elution Buffer)
	- MaxiPrep Filter Columns
	- TE Buffer (the final elution step)
- MaxiPrep Column Holder with Collection Tray
- 50mL tubes
- Isopropyl Alcohol (100%)
- ETOH (70%)


## Procedure
### Phase 1: Pelleting the Bacterial Culture
1. Take the bacterial culture and pour into 500mL cylindrical bottles that would fit inside an ultracentrifuge. 
2. Ensure that the samples are appropriately balanced. Use DI-H20 to increase the mass of some samples to ensure balance is achieved. 
3. Place samples into an ultracentrifuge
4. Spin samples at 4C for 20 minutes at 4,500rpm
5. Pour off the supernatant into a bleach containing waste container. A pellet should be visible at the bottom of the bottle. 
6. **The bottles containing the pellet can be frozen down at -20C and stored for up to 2 months. Consider doing this if you are not going to continue with the protocol today. 

### Phase 2: Resuspending the Bacterial Pellet
1. Resuspend the bacterial pellet in 10mL of R3 Buffer. [^1]
2. Place the resuspended pellet into a 50mL tube. 
3. Add 10mL of L7 Buffer to each sample. Mix by inverting the tube. Let the samples incubate for ~4 minutes. [^2]
4. Add 10mL of N3 Buffer to each sample. Mix by inverting the tube. A precipitate should have formed within the tube. 

### Phase 3: The MaxiPrep Columns
1. Add 30mL of EQ1 Buffer to each column. Let the columns sit until the EQ1 buffer stops dripping. The columns are now ready for the samples. [^3]
2. Pour the sample from the 50mL tube (the tube should contain ~30mL of volume) into the column. [^4]
3. Add 10mL of W8 Wash Buffer to the column.
4. Remove the filter and place it in the Biohazard waste container (the big cylinder)
5. Add 60mL of W8 Wash Buffer to each column.
6. After the Wash Buffer has gone through each column, remove the collection tray, and place 50mL Centrifuge tubes underneath each column to catch the elution. 
7. Add 15mL of E4 Elution buffer to each column.
8. Add 10.5mL of IPA to each sample. Mix by inverting the tube. 

### Phase 4a: The One day protocol
1. Take the sample to the tabletop ultracentrifuge (by the Nanodrop) and spin at Max Speed for 99 minutes at 4C. 
2. A white pellet should be seen at the bottom of the tube. 
3. Decant the supernatant, taking care to not disrupt the pellet at the bottom of the tube. 
4. Add 5mL of 70% ETOH. ==DO NOT RESUSPEND THE PELLET==. 
5. Spin at Max Speed, for 15 minutes, at 4C, in the same centrifuge as before. 
6. Decant the supernatant, taking care to not disrupt the pellet at the bottom of the tube. 
7. Place the tube upside down over absorbent Kimwipes to collect any excess ETOH in the tubes.
8. Resuspend the pellet in TE buffer. The amount of TE buffer that you add is dependent on how much volume / how concentrated you want your plasmid concentration to be. [^5]
9. Place in a 37C warm water bath to help the pellet resuspend
10. Transfer into a 1.5mL Eppendorf tube. 

### Phase 4b: The Next Day Protocol
1. ==Leave the sample with IPA in a -20C freezer overnight. ==
2. Take the sample to the tabletop ultracentrifuge (by the Nanodrop) and spin at Max Speed for 99 minutes at 4C. 
2. After the spin a white pellet should be seen at the bottom. 
3. Decant the supernatant, taking care to not disrupt the pellet at the bottom of the tube. 
4. Add 5mL of 70% ETOH. ==DO NOT RESUSPEND THE PELLET==. 
5. Spin at Max Speed, for 15 minutes, at 4C, in the same centrifuge as before. 
6. Decant the supernatant, taking care to not disrupt the pellet at the bottom of the tube. 
7. Place the tube upside down over absorbent Kimwipes to collect any excess ETOH in the tubes.
8. Resuspend the pellet in TE buffer. The amount of TE buffer that you add is dependent on how much volume / how concentrated you want your plasmid concentration to be. [^5]
9. Place in a 37C warm water bath to help the pellet resuspend
10. Transfer into an Eppendorf tube. 

## Next Steps
Plasmid DNA should be quantified by [[RM032 - Quantifying DNA with the NanoDrop|the NanoDrop]]. They can be used a variety of different applications such as [[RM018 - Measles Virus Prep|virus production]] or Gibson Assembly. 


## Appendix

### Related Protocols
- [[RM032 - Quantifying DNA with the NanoDrop]]
- [[RM018 - Measles Virus Prep]]
- [[RM021 - Plasmid MiniPrep - Qiagen]]


### Footnotes
[^1]: If the pellet was collected earlier and was previously stored in -20C, the pellet might be difficult to resuspend. I recommend leaving the pellet soaking in the R3 buffer for 10 minutes to have the pellet soften.

[^2]: Do not let the lysis buffer incubate for more than 5 minutes!

[^3]: I recommend adding the EQ1 Buffer to the columns after resuspending the pellets in R3 Buffer and before adding the L7 Buffer. That should be enough time for the column to equilibrate. 

[^4]: Invert the sample before pouring into the column. After addition of N3, the precipitate tends to float on top of the liquid. Ensure that this is homogenously distributed before adding to the column by inverting it a few times. 

[^5]: I would recommend always asking the person you are running the MaxiPrep for their desired plasmid concentration. When I ran these for Kurt, he wanted them in ~400uL. However, Eman wanted them to be much more concentrated at ~100uL. Either way the minimum elution should be 100uL and the maximum should be 500uL. 