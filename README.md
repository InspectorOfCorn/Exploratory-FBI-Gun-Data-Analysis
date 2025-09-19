# Fbi Gun Data Analysis (2017 Dataset)

[![View Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://nbviewer.org/github/InspectorOfCorn/Exploratory-FBI-Gun-Data-Analysis/blob/main/InspectorGadget.ipynb)


## Overview
This project explores firearm background checks and ownership trends in the United States using **FBI NICS data** combined with **U.S. Census population data**.  
The notebook (`InspectorGadget.ipynb`) walks through data cleaning, merging, and exploratory analysis to identify trends in gun ownership over time and across states.

---

## Data Sources

- **FBI NICS Firearm Background Checks** – [FBI.gov](https://www.fbi.gov/services/cjis/nics)  
- **U.S. Census Data** – [census.gov](https://www.census.gov/)  
- Repository Data Files:  
  - `Database_Ncis_and_Census_data/gun_data.csv`  
  - `Database_Ncis_and_Census_data/US_Census_Data.csv`  
  - `clean_merge.csv` (processed merge of the two datasets)  

---

## Usage

Clone the repository and open the notebook in Jupyter:
(make sure you have an env with Jupyter lab already installed)

```bash
git clone https://github.com/InspectorOfCorn/Exploratory-FBI-Gun-Data-Analysis.git
cd Exploratory-FBI-Gun-Data-Analysis
jupyter notebook InspectorGadget.ipynb
```
