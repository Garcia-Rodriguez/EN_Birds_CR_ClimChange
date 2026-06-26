# EN_Birds_CR_ClimChange

Codes and data used in the main analyses presented in: Villegas-Retana et al. Current and future areas of conservation relevance for six endangered bird species in Costa Rica.

The repository contains three R code files:

1_Data_Prep_SDMs.R which processes the input data for the SDMs including occurrence records, calibration areas and background points

2_SDMs.R which runs the model calibration for each species. This code also includes model selection, projections to 36 future climatic scenarios and binarization of optimal models for posterior estimations of suitable area

3_MOP.R to test for non-analogous climates in the future scenarios used here for projection.

The data needed to run the above codes is also available here and includes:

A. Data/Occs.csv --> The occurrence records for all species

B. A folder (Spp_shps) with the IUCN distribution range polygons for each species

Code 2 uses as input the outputs generated in Code 1 from the available files. Code 3 also uses the IUCN ranges for the definition of areas to be compared among time frames.

