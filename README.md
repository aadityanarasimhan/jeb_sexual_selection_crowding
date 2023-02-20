=============== README ===============

Dataset for: Narasimhan A., Jigisha J., Kapila R., Meena A., Santhosh S., Prasad N. G. Consequences of adaptation to larval crowding on sexual and fecundity selection in Drosophila melanogaster", 2022. Journal of Evolutionary Biology


Abstract: Sexual selection is a major force influencing the evolution of sexually reproducing species. Environ-mental factors such as larval density can manipulate adult condition and influence the direction and strength of sexual selection. While most studies on the influence of larval crowding on sexual selec-tion are either correlational or single-generation manipulations, it is unclear how evolution under chronic larval crowding affects sexual selection. To answer this, we measured the strength of sexual selection of male and female Drosophila melanogaster that had evolved under chronic larval crowd-ing for over 250 generations in the laboratory, along with their controls which had never experienced crowding, in a common garden high-density environment. We measured selection coefficients on male mating success and sex-specific reproductive success, as separate estimates allowed dissection of sex-specific effects. We show that experimental evolution under chronic larval crowding decreases the strength of sexual and fecundity selection in males but not in females, relative to populations experi-encing crowding for the first time. The effect of larval crowding in reducing reproductive success is almost twice in females than in males. Our study highlights the importance of studying how evolution in a novel, stressful environment can shape adult fitness in organisms. 

=============== CONTACT ===============

Aaditya Narasimhan (first author): aaditya.narasimhan@unibas.ch
N. G. Prasad (corresponding author): prasad@iisermohali.ac.in

=============== FILES ===============

The .zip file contains the following files which were used in the analysis, along with a description of variables used

-------------------

MB fem diff.csv: Dataset containing reproductive success of control females. The main dependent variable to be used is Prop1, which is essentially observed - expected proportion of progeny. 

Variable description: 
1. Block		: replicate populations of the selection lines (levels: 1, 2, 3, 4) 
2. Population   : selection lines; MB or control populations and PJB, the common competitor 
3. CageID       : cage number (numeric)
4. Red          : total number of red-eyed progeny (numeric)
5. White        : total number of white-eyed progeny (numeric)
6. Total        : total number of progeny (numeric)
7. Prop_red     : proportion of red-eyed progeny (numeric)
8. Prop1        : mean centered (0) and variance scaled (1) Prop_red (numeric)

--------------------

MB male diff.csv: Dataset containing reproductive success of control males. The main dependent variable to be used is Prop1, which is essentially observed - expected proportion of progeny. 

Variable description: 
1. Block		: replicate populations of the selection lines (levels: 1, 2, 3, 4) 
2. Pop          : selection lines; MB or control populations and PJB, the common competitor 
3. CageID       : cage number (numeric)
4. Total Red    : total number of red-eyed progeny (numeric)
5. Total White  : total number of white-eyed progeny (numeric)
6. PropRed      : proportion of red-eyed progeny (numeric)
7. Prop1        : mean centered (0) and variance scaled (1) Prop_red (numeric)

--------------------

MB matsuc.csv: Dataset containing mating success of control males. The main dependent variable to be used is Prop1, which is essentially observed - expected proportion of matings. 

Variable description: 
1. Block		: replicate populations of the selection lines (levels: 1, 2, 3, 4) 
2. Selection    : selection lines; MB or control populations and PJB, the common competitor 
3. CageID       : cage number (numeric)
4. Red          : total number of matings by red-eyed males (numeric)
5. White        : total number of matings by white-eyed males (numeric)
6. Prop_red     : proportion of matings by red-eyed males (numeric)
7. Prop1        : mean centered (0) and variance scaled (1) Prop_red (numeric)

--------------------

MCU fem diff.csv: Dataset containing reproductive success of crowded females. The main dependent variable to be used is Prop1, which is essentially observed - expected proportion of progeny. 

Variable description: 
1. Block		: replicate populations of the selection lines (levels: 1, 2, 3, 4) 
2. Population   : selection lines; MCU or crowded populations and PJB, the common competitor 
3. CageID       : cage number (numeric)
4. Red          : total number of red-eyed progeny (numeric)
5. White        : total number of white-eyed progeny (numeric)
6. Total        : total number of progeny (numeric)
7. Prop_red     : proportion of red-eyed progeny (numeric)
8. Prop1        : mean centered (0) and variance scaled (1) Prop_red (numeric)

--------------------

MCU male diff.csv: Dataset containing reproductive success of crowded males. The main dependent variable to be used is Prop1, which is essentially observed - expected proportion of progeny. 

Variable description: 
1. Block		: replicate populations of the selection lines (levels: 1, 2, 3, 4) 
2. Pop          : selection lines; MCU or crowded populations and PJB, the common competitor 
3. CageID       : cage number (numeric)
4. Total Red    : total number of red-eyed progeny (numeric)
5. Total White  : total number of white-eyed progeny (numeric)
6. PropRed      : proportion of red-eyed progeny (numeric)
7. Prop1        : mean centered (0) and variance scaled (1) Prop_red (numeric)

--------------------

MCU matsuc.csv: Dataset containing mating success of crowded males. The main dependent variable to be used is Prop1, which is essentially observed - expected proportion of matings. 

Variable description: 
1. Block		: replicate populations of the selection lines (levels: 1, 2, 3, 4) 
2. Selection    : selection lines; MCU or crowded populations and PJB, the common competitor 
3. CageID       : cage number (numeric)
4. Red          : total number of matings by red-eyed males (numeric)
5. White        : total number of matings by white-eyed males (numeric)
6. Prop_red     : proportion of matings by red-eyed males (numeric)
7. Prop1        : mean centered (0) and variance scaled (1) Prop_red (numeric)

--------------------

mcu-mb_body_size.csv: Dataset containing the thorax and wing lengths of males and females from crowded and control populations. The flies were grown under same larval conditions as in the main assay, but were a different set of flies, however all flies used were from similar generations. Lengths are all in millimetres. 
Contains some representative accompanying images from "Block 1". Images were clicked using a digital camera attached to a microscope and analysed via imageJ. 

Variable description: 
1. ID 			: sample ID
				  Format: e.g. CHfF1 - 
				  			a. CH or MH (crowded or control)
				  			b. f or m (female or male)
				  			c. F1 (sample ID)
				  			d. The number corresponds to image IDs. 
				  			e. Image IDs: instead of "F1" at the end, will contain "T" for thorax and "LW" and "RW" for left and right wings along 
				  			   with the same number as in the csv file. 				  			
2. Block		: replicate populations of the selection lines (levels: 1, 2, 3, 4) 
2. Selection    : selection lines; CU or crowded populations and MB, the control population
3. Sex          : Male or Female
4. LW           : left wing straight-line length from the anterior cross vein to the end of the second longitudinal vein (numeric)
5. RW           : right wing straight-line length from the anterior cross vein to the end of the second longitudinal vein (numeric)
6. Thorax       : thorax length i.e., where the neck meets the pronotum to the posterior tip of the scutellum  (numeric)
7. Wings        : average of LW and RW (numeric)

--------------------