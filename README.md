# US_Crime_rate_MLR
This is the final project of course *P8130 Biostatistical Method*.

## Introduction
The increasing crime rate of the United States in the 21st century has triggered significant attention. In this page, we created a model to predict the crime rate based on multiple socioeconomic variables, such as population, education level, poverty level, personal income and geographic regions. We conducted initial visualization of the crime rate dataset with various plots and variable transformation, followed by model selection, model interaction, and cross-validation. With these methods, we selected an optimal model to predict the crime rate in counties. Subsequently, we used model diagnostics to determine whether the selected model needed further transformation before excluding existing outliers.

## Data
[Data](./data/cdi.csv) are collected from the “County Demographic Information” (CDI) data set, which contains characteristics of 440 counties in the United States collected from 1990-1992. The primary objective of this investigation is to develop insight relevant to predicting the crime rate in counties, which could be summarized as the crime rate per 1,000 population (CRM_1000). 

## Model Establishment
Here we apply basic multivariable linear regression model to estimate the crime rate. The analyzing workflow includes:
1. Visualization
2. Variable selection
3. Interaction
4. Cross Validation and Comparison
5. Model Diagnostics

## Documents and Reports
The separated codes are kept in the file `previous`, while the final version could be find as [final_code.Rmd](./final_code.Rmd). A scientific report is also presented in [Report.pdf](./Report.pdf) for this project.
