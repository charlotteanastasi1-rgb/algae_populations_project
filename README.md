# algae_populations_project
2026-2027 EDS Certificate Project
An evaluation of algae and phytoplankton populations in the Northern Atlantic Ocean from the 1950's to 2020's. Abundance of algal populations are strong indicators of warming oceans as a symptom of climate change. Algae acting as indicators can allow us to determine global environmental policies pertaining to oceans.
**How can we predict global ocean warming using algae and phytoplankton populations over time?**
## Files
- 0_project_setup.ipynb ; project organization via Google Drive ; source N/A
- 1_data_clean.ipynb ; cleaned data from raw data ; source 765141_v6_cpr-list-taxa.csv https://www.bco-dmo.org/dataset/765141?utm 11/18/26 AND 765141_v6_cpr-plankton-abundance.csv https://www.bco-dmo.org/dataset/765141?utm 11/18/26
## Project Structure
algae_populations_project
│
├── README.md
│
├── 0_project_setup
│   
└── 1_data_clean
## How to Run
Run scripts in numerical order
Note **Mount code requires Python runtime** all other code requires R runtime
## Cleaning steps and known issues
- Cleaned abundance raw data by condensing date and time into one column
- Removed N/A values
- Cleaned taxa raw data by removing columns except ID and Taxa name
- Combined data sets
- Known issue with Taxa identification column stating all values N/A. Need to edit to fix matching IDs
## Status
**INCOMPLETE**
Next steps: modify known issues and add additional folders with analysis
