# GDES_inputs_and_results
FINAL_DATA contains final input files training the network for:
  - three different fact_orientations:
      1. SP02 + Perf , NBP_Sys + NBP_Dia
      2. SP02 + NBP_Sys, Perf + NBP_Dia
      3. SP02 + NBP_Dia, NBP_Sys + Perf
  - four different PR approaches for each fact_orientation
  - 50 trials for each PR approach:
      1-10: default value 000.500
      11-20: default value 000.500, isolated
      21-30: default value 000.600
      31-40: default value 000.700
      41-50: default value 000.550
FINAL_RESULTS contains the network's output values when each corresponding input file was run
the results are summarized in tables in results_summary_tables.xlsx
