# ODT_database
Database and training/testing 10-fold cv sets linked to the submitted publication 'Puzzle out machine learning model - explaining disintegration process in ODTs'
Please, cite following article:
  
Comma separated files (CSV/TXT)  
  
Filename: **ODT_DT_db_expanded_raw_v10_1.csv**  
Description (cols):  
Col1 - Index - index no of formulations  
Col2 - Col634 - molecular descriptors of an API  
Col635 - Col666 - components [%], process parameters, tablets characteristics  
Col667 - Disintegration_time_sec - disintegration time [s] measured according to the USP and EP  
  
Files in **10cv** dir  
**10cv_ODT_DT_db_v17_39_in_no{x}.txt** - training  
**t-10cv_ODT_DT_db_v17_39_in_no{x}.txt** - testing  
10-fold cv datasets consist of 40 columns:  
Col1-Col39 - Inputs  
API_perc,Mannitol_perc,MCC_perc,Lactose_perc,Calcium_silicate_perc,HPMC_perc,Sodium_bicarbonate_perc,SSG_perc,CC_Na_perc,Crospovidone_perc,L_HPC_perc,Pregelatinized_starch_perc,Sodium_carboxymethyl_starch_perc,Mg_stearate_perc,Aerosil_perc,Sodium_stearyl_fumarate_perc,Colloidal_silicon_dioxide_perc,Talc_perc,X2HP_bCD_perc,bCD_perc,CD_methacrylate_perc,Amberlite_IRP_64_69_perc,Eudragit_EPO_perc,Poloxamer_188_perc,PVP_perc,SLS_perc,PVA_perc,Camphor_perc,Hardness_N,GATS7i,Thickness_mm,GGI7,MATS4p,MIC2,Punch_mm,nT12Ring,XLogP,GATS7p,nF8HeteroRing  
Col40 - Output - Disintegration_time_sec  
  
**In order to make predictions based on the model please use above column names.  **
