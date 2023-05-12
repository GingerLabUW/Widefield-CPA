# Widefield-CPA

Purpose: Do change point fitting to time series data with fixed time-binwidths and gaussian noise

Adapted From: Li and Yang, J Phys Chem B, 123, 689-701 (2019) https://pubs.acs.org/doi/full/10.1021/acs.jpcb.8b10561

Written By: Jessica Kline

Functions:
- create synthetic camera style blinking data
- analyze real and synthetic camera-style blinking data using change point analysis

1_Find_QDs: takes PL videos of QDs blinking and selected the QDs from the video and extracts the blinking traces
2_Gaussian_CPA_Fittings: takes extracted blinking traces and fits them using change point analysis
3_Widefield_Post_CPA_Individual_Batch_Processing: crunches the numbers from step 2 and outputs the statistics of the blinking in an individual batch
4_Widefield_Batch_Comparison: compiles and plots the results of 3 run across multiple batches
