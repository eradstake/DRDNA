article 		= first author and year of publication
year 			= year of publication
cell line 		= name of cell line as mentioned in article
cell type 		= type of cell, immortalized or primary 
species 		= species from which cells are isolated
cell class		= normal healthy cells or tumor cells
tissue 			= tissue origing of cell collection
cell cycle 		= phase of cell cycle during irradiation. a stands for asynchronized
radio labeled 		= were cells exposed to radioactive agents for purpose of radiolabeling the DNA?
pathway def 		= were cells deficient in a certain repair pathway. WT = wild type, NHEJ = NHEJ deficient, HR = HR deficient
deficiency 		= protein deficiency in case of repair deficient
seeding density 	= confluent or exponentialli dividing (exp) at the time of irradiaton
dish 			= cell culture dish used, as mentioned in article
serum 			= concentration of serum used inside the cell culture medium
technique 		= assay used to quantify DSBs
lysis temp 		= temperature during lysis for PFGE assay
microscope 		= type of microscope used to quantify RIF for ICC assay
ICC marker 		= target protein for detection of RIF for ICC assay
temp irradiation 	= temperature during the irradiation as discrete value (RT = room temperature, ice = radiation performed on ice)
incubation temp 	= temperature of cell incubation
radiation 		= type of radiation exposure
Z 			= atomic number of ion exposure (0 for photon)
photon source 		= type of photon exposure
energy 			= energy of primary beam in MeV/n for ion exposure, or as reported in the article
LET 			= linear energy transfer in keV/µm at point of cells, or as reported in publication
dose 			= total absorbed dose in Gy
dose rate		= absorbed dose per minute
irr time 		= total time of exposure in minutes based on total absorbed dose and dose rate
techn repl 		= number of replicates, or cells scored per condition (nr = not reported)
repeats 		= number of repeats of experiment. 1 for no repeat (nr = not reported)
eu        = experimental unit, unique id number for each independent experiment
time pi 		= time post irradiation in minutes as mentioned in article
time norm 		= time pi subtracted by time of highest absolute number of DSB reported
average_n_per_cell	= absolute value of DSB reported
n_baseline_sub		= absolute value substracted by the baseline (unirradiated) value, if empty absolute values were already baseline subtracted as reported in the publication
baseline_norm		= n_baseline_sub values normalized to the n_baseline_sub value for time_norm = 0
n_plateau_sub		= n_baseline_sub values subtracted by n_baseline_sub value at last time point 
plateau_norm		= n_plateau_sub values normalized to the n_plateau_value for time_norm = 0
