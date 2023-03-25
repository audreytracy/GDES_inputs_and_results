# GDES_inputs_and_results
[FINAL_DATA](https://github.com/audreytracy/GDES_inputs_and_results/tree/master/FINAL_DATA) contains final input files training the network using the following approaches:
   - Three different fact_orientations:  
     - fact_orientation_1: **SP02 + Perf , NBP_Sys + NBP_Dia**  
     - fact_orientation_2: **SP02 + NBP_Sys, Perf + NBP_Dia**  
     - fact_orientation_3: **SP02 + NBP_Dia, NBP_Sys + Perf**  
   - Four different PR approaches for each fact_orientation  
   - 50 trials for each PR approach:  
     - 1-10: default value 000.500  
     - 11-20: default value 000.500, isolated  
     - 21-30: default value 000.600  
     - 31-40: default value 000.700  
     - 41-50: default value 000.550  

[FINAL_RESULTS](https://github.com/audreytracy/GDES_inputs_and_results/tree/master/FINAL_RESULTS) contains the network's output values when each corresponding input file was run  

The results are summarized in tables in [results_summary_tables.xlsx](https://github.com/audreytracy/GDES_inputs_and_results/blob/master/results_summary_tables.xlsx)
