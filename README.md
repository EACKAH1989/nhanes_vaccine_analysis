NHANES Vaccine Analysis

This project analyzes vaccination data from the National Health and Nutrition Examination Survey (NHANES) focusing on Hepatitis A, Hepatitis B, and HPV vaccines. The analysis includes:

Importing and merging demographic and immunization datasets from NHANES XPT files.
Cleaning and recoding variables for age groups, gender, and vaccination status.
Summarizing vaccine coverage rates by age group and gender.
Visualizing vaccine coverage trends using bar plots.
Preparing the data for further analysis including logistic regression models.
The goal is to better understand vaccination patterns across different demographic groups in the U.S., which can inform public health interventions and vaccination campaigns.

Installation

To run this project, you will need R (version 4.0 or higher) and the following R packages installed:

install.packages(c("tidyverse", "haven", "survey", "janitor", "ggplot2", "gt"))
Alternatively, if you use Quarto, it will automatically install and manage the required packages during rendering.

Usage

Place the NHANES .XPT data files (P_DEMO.xpt, P_IMQ.xpt, etc.) in a known directory.
Update the file paths in the R/Quarto script to point to these data files.
Run the analysis script or render the Quarto document (.qmd) to produce summarized tables and visualizations.
The output includes vaccine coverage percentages by age group and gender, and plots saved as PNG files for further reporting or presentations.
Data Sources

National Health and Nutrition Examination Survey (NHANES) data files are publicly available from the CDC website:
https://www.cdc.gov/nchs/nhanes/index.htm
This project uses demographic and immunization questionnaire datasets (P_DEMO, P_IMQ).
