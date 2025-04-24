# Project-1-FARS-Fatal-Crash-Analysis
Multi-year analysis of fatal multi-vehicle and alcohol-involved crashes in the U.S. (2015–2023) using FARS data. Includes data engineering, visualization, predictive modeling, and policy simulation. 📊🧠

The original raw FARS CSV files (2015–2023) are too large for GitHub upload limits.

To reproduce the results, please download the full datasets from the official NHTSA FARS website:

🔗 https://www.nhtsa.gov/research-data/fatality-analysis-reporting-system-fars



I uploaded this following files. 
Processed Files Include:
2015_combined.csv – Merged and cleaned data for year 2015

2016_combined.csv – ...

...

2023_combined.csv – ...

multifatal_counts.csv – Year-wise summary of multi-fatal crashes

alcohol_counts.csv – Year-wise summary of alcohol-involved crashes

top_states_highrisk.csv – States with highest combined crash risk

fatality_heatmap_matrix.csv – State-by-year matrix for heatmap

Each file contains cleaned and preprocessed rows with relevant columns such as:

YEAR, STATE, FATALS, IS_NIGHT, ALCOHOL_INVOLVED, MULTI_FATAL, etc.

