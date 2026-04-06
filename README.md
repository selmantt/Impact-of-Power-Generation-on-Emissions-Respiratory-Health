# Impact of Power Generation on Emissions & Respiratory Health

An exploratory data analysis and statistical modeling study that investigates how different energy production mixes affect CO₂ and pollutant emissions, and downstream respiratory health outcomes across European countries.

## Overview

Fossil-fuel power plants are a primary source of airborne pollutants linked to chronic respiratory diseases. This project quantifies the relationship between a country's energy source mix (coal, gas, nuclear, renewables) and two outcome dimensions: greenhouse gas emissions and population-level respiratory health indicators (hospitalization rates, prevalence of COPD and asthma).

## Research Questions

- Does a higher share of renewable energy statistically correlate with lower respiratory disease rates?
- Which energy sources show the strongest association with harmful emissions per GWh produced?
- Are emission reductions following energy transitions reflected in near-term health improvements?

## Methodology

- **Data sources:** Eurostat energy production statistics, EEA emission inventories, WHO / Eurostat health statistics
- **Analysis pipeline:** Data cleaning → feature correlation → regression modeling → visualization
- **Models used:** OLS regression, Spearman correlation, time-series trend analysis
- **Outputs:** Coefficient tables, scatter plots, and country-level comparison charts

## Project Structure

'''
├── main.ipynb          # Full analysis notebook
├── Project Report.pdf  # Detailed write-up with findings and references
└── README.md
'''


## Usage

Open `main.ipynb` in Jupyter and run all cells. All required datasets are either embedded in the notebook or fetched from public Eurostat/EEA endpoints.

## Technologies

Python · Pandas · NumPy · Statsmodels · Matplotlib · Seaborn 
