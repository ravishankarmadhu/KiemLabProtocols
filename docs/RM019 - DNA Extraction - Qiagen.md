# DNA Extraction - Qiagen
### Created by Ravishankar Madhu
Last updated: 2023-07-10

## Description
This protocol describes how to extract DNA from White Blood Cells using the Qiagen Kit
## Reagents and Materials 
- QIAMP DNA Blood Mini Kit (250)
	- Contains the following:
		- Qiagen Protease
		- AL Buffer
		- AW1 Buffer
		- AW2 Buffer
		- AE Buffer
		- QIAmp Mini Spin Columns with collection tube
- PBS
- White Blood Cell Pellets 
- 100% ETOH
- 1.5mL Eppendorf Tubes 
- Tube Incubator  / Shaker set to 56C

## Things to Note before starting
### Stocking the Kit
Some of the buffers supplied by the kit (AW1 and AW2) require you to add ETOH to the bottles before use. Follow these instructions and label the bottle appropriately before using the buffers. 

### Amount of Cells
This kit is best used on cell pellets between 1e6 and 20e6. For cell counts smaller than 1e6 - use the [[RM020 - DNA Extraction - Epicentre]] protocol. For cell counts larger than 20e6, split the pellet into smaller aliquots before running this protocol. 

### Estimated Timing
The procedure is most efficient with 8 samples, but can be scaled up to process 24 samples at once. The procedure takes around 1 hour to complete. 


## Procedure
1. Resuspend the cell pellet in 200uL of PBS
2. Create a Master Mix with the following ratio: 20uL Qiagen Protease + 200uL AL Buffer. You should make 120% of the required Master Mix to account for pipetting errors. (ie for 8 samples, make a Master Mix for 10 samples, for 16 samples make a Master Mix for 20 samples, etc.) [^1]
3. Aliquot 220uL of the Master Mix into each sample.
4. Vortex samples to mix.
5. Incubate the sample at 56C for 10 minutes. [^2]
6. Briefly Centrifuge the samples (~10 seconds). [^3]
7. Add 200uL of 100% ETOH to each sample.
8. Pipette up and down to mix the sample. 
9. Pipette the mixture into the QIAamp Mini Spin Column.
10. Centrifuge at 13,000 rcf for 1 minute.
11. Discard the flow through. [^4]
12. Add 500uL of AW1 Buffer to each column.
13. Centrifuge at 13,000 rcf for 1 minute.
14. Discard the flow through.
15. Add 500uL of AW2 to each column.
16. Centrifuge at 13,000 rcf for 1 minute.
17. Discard the flow through.
18. Centrifuge the empty column at 13,000 rcf for 3 minutes.
19. Place the column into a clean 1.5mL Eppendorf Tube.
20. Add 30-150uL of AE Buffer [^5]
21. Let it incubate at room temperature for 5 minutes.
22. Centrifuge at 13,000 rcf for 1 minute.
23. Discard the column.
24. Label Tubes with all the sample information (Animal ID, Date, Cell Source, etc).

## Next Steps
The DNA can be quantified by using the [[RM032 - Quantifying DNA with the NanoDrop|NanoDrop]] and can be stored in the -20C Freezers for further use. 


## Appendix

### Related Protocols
- [[RM032 - Quantifying DNA with the NanoDrop]]
- [[RM023 - Generic PCR]]


### Footnotes
[^1]: Always make a minimum of 2 extra aliquots of master mix even if that is greater than 20%. For instance, If you are working with 3 samples, make a master mix for 5 samples even though 20% would only be 0.6. 

[^2]: There are tabletop incubators / shakers located in the TC Room by the microscope, in the PCR room by the centrifuge, and by the Weigh Station. Heating up the Incubator takes a few minutes but getting the incubator to cool down will takes a while. Always make sure you turn off the incubator when you are done to allow it to cool for the next person. 

[^3]: Press the SPIN button on the centrifuge to get them to spin briefly. 

[^4]: The flow through can be stored in a glass bottle and stockpiled with the flow through from other DNA extractions. Once the bottle is full, the flow through is safe to toss down the sink. 

[^5]: The exact volume of AE Buffer you elute depends on your desired concentration and downstream processes. If you are unsure, ask what volume the samples should be eluted in. I would recommend 50uL of AE buffer for an average sample. 

