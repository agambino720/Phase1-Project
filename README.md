# Aircraft Safety Analysis Project

## Introduction
This project aims to enhance aircraft safety by evaluating various aircraft configurations and their associated risks. Utilizing historical data, the analysis identifies the safest aircraft models, engine types, and engine counts, providing important insights for making informed decisions in entering into the aviation industry.

## Data Collection
The dataset used in this project was sourced from Kaggle.com, specifically the NTSB (National Transportation Safety Board) aviation accident database. This dataset contains detailed records of aviation accidents and incidents.
- [NTSB Dataset on Kaggle](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses)

## Data Cleaning
Data relevant to the analysis included variables such as total fatal injuries, aircraft damage, model, engine type, and number of engines. The following steps were taken in the data cleaning process:
- Standardization: Relevant columns were standardized for type casing and spacing.
- Imputations: Null values were imputed using related columns where possible; otherwise, rows with missing necessary values were removed.
- Damage Severity: Aircraft damage descriptions were converted into a numerical scale (1 - Minor, 2 - Substantial, 3 - Destroyed) and recorded in a new column titled 'Damage Severity'.

## Data Analysis
The analysis employed descriptive statistics to assess the safety of different aircraft configurations. Key metrics analyzed included:
- **Average Fatalities and Damage Severity:** Calculated for each engine type, number of engines, and aircraft model.
- **Composite Safety Score:** Created by averaging the damage severity and fatalities scores to rank the configurations from safest to least safe.

## Results
Key findings from my analysis include:
- **Engine Types:** Electric and Reciprocating engines are identified as the safest, though data on electric engines is limited.
- **Number of Engines:** Aircraft with a single engine have the lowest average fatalities, while those with three engines show the least average damage severity. Single engine aircraft also have best overall safety score as well. 
- **Safest Models:** The models with the lowest composite safety scores, indicating higher safety, are 727-223, 787, DC-9-51, MD-80, and 727-200.

## Recommendations
Based on the analysis, the following recommendations are made:
- **Single-Engine and Reciprocating Engines:** Focus on acquiring single-engine aircraft equipped with reciprocating engines due to their proven safety.
- **Exploration of Electric Engines:** Further research and data collection are recommended for electric engines to fully evaluate their safety potential.
- **Incorporate Top Models:** It is advised to consider the top models identified through the analysis (727-223, 787, DC-9-51, MD-80, 727-200) in future aircraft acquisitions.
