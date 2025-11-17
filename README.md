# Project2
Analysis of air pollutant concentrations (CO, PM2.5, O3) in Durham County, NC (2018-2020) and potential associations with sickle cell disease.

## Project Overview

This project examines temporal patterns in air pollution data from the EPA monitoring station at RDU airport. The analysis includes:
- Data cleaning and processing of daily air quality measurements
- Calculation of monthly averages and confidence intervals
- Visualization of seasonal trends in pollutant concentrations

## Files

- `air_quality_analysis.Rmd` - Main analysis R Markdown file
- `AQ_2018.csv`, `AQ_2019.csv`, `AQ_2020.csv` - Raw air quality data
- `air_quality_analysis.docx` - Knitted report (generated)

## Requirements

- R (version 4.0 or higher)
- Required packages:
  - tidyverse
  - lubridate
  - knitr

## Usage

1. Open `air_quality_analysis.Rmd` in RStudio
2. Ensure all CSV files are in the project directory
3. Click "Knit" to generate the Word document

## Data Source

Air quality data obtained from EPA monitoring station at Raleigh-Durham International Airport.
