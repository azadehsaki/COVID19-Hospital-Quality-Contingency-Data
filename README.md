# COVID-19 Hospital Quality and Fatality Contingency Dataset

This repository contains the secondary aggregated dataset and analytical R code for the study:
"Quality control of hospitals and its effect on the in-hospital fatality rate of COVID-19 in Iran".

## Repository Structure
- `data/`: Contains the 7-way contingency table (`.dat` or `.csv`) with 256 strata.
- `R/`: Analysis scripts for Poisson/Binomial GLM and attribute control charts.

## Variable Descriptions
- `Peak`: Epidemic peaks (1 to 4)
- `Quality_Status`: Hospital quality accreditation (QC vs NQC)
- `Age_Group`: Age category (>30-60 vs >=60)
- `Diabetes`: Presence of diabetes (Yes/No)
- `SaO2`: Oxygen saturation (<=93% vs >93%)
- `ARDS`: Acute Respiratory Distress Syndrome (Yes/No)
- `ICU`: Intensive care unit admission (Yes/No)
- `Total_Patients`: Total hospitalized cohort per stratum
- `Fatality_Count`: In-hospital death count per stratum

## Citation
If you use this dataset or code, please cite our original article in *Scientific Reports* (DOI: 10.1038/s41598-025-89658-x).
