
# Sociodemographic Determinants of COVID-19 Vaccine Uptake in Ontario

## Project Overview

This repository presents a multi‑phase independent data analysis project using an Ontario COVID-19 vaccination dataset. The project was designed as a complete end to end/complete reproducible workflow that moves from project planning and data wrangling to machine learning, model evaluation, and interpretation.

The project focuses on cleaning, describing, and preparing an Ontario vaccination dataset for further public health analysis.

The assignment emphasizes two major components:

- **Part 1** Identify and source appropriate dataset, develop a well structured data analysis plan, conduct data wrangling and descriptive statistics, use GitHub for reproducibility and version control.
- **Part 2** Extended data wrangling and preprocessing, missing data handling, machine learning, hyperparameter tuning, model comparison, and interpretation.

Collectively, these components illustrate a full intergrated and end-to end scientific computing pipeline, spanning the full spectrum of analysis from data acquisition and preprocessing to model development, evaluation, and effective reporting of findings.

---
## Dataset Description
The dataset used in this project is **Ontario Vaccination Status.xlsx** from the Public Health Ontario website which can be accessed through https://www.publichealthontario.ca/en/Data-and-Analysis/Infectious-Disease/Respiratory-Virus-Tool

### Size
- **Rows:** 720,720
- **Columns:** 7

### Variables
- `Public_health_unit`
- `Gender`
- `Age_group`
- `Vaccination_status`
- `Week_start_date`
- `Number_of_individuals_vaccinated`
- `Population`

### Relevance

This dataset is relevant to public health because it allows for the exploration of vaccination uptake across demographic groups, geography, and time. 

#### Why this dataset is appropriate

This dataset is appropriate for the project because it:

- is relevant to public health,
- includes multiple categorical and numeric variables,
- contains a time variable,
- includes missing data in `Population`,
- supports both descriptive and predictive analysis,
- requires preprocessing before modeling.

---


## Project Aim

The main aim of this project is to analyze the sociodemographic of COVID-19 vaccine uptake in Ontario, Canada.

### Research Questions

- What are the demographic and regional determinants of COVID-19 vaccine uptake in Ontario?

### Research Objectives

- To identify the sociodemographic determinants factors influencing COVID-19 vaccine uptake among residents in Ontario.

---


## Reproducibility Instructions

### 1. Clone the repository
Clone or download the repository to your computer.

### 2. Place the dataset in the folder
The analysis expects all the documents should be the same folder

### 3. Open the R Markdown files in RStudio
Recommended order:
1. `analysis_plan.Rmd & html`
2. `Part1_data_wrangling_Descriptives.Rmd & html`
3. `part2_machine_learning_analysis.Rmd & html`
4. `reference.bib`

### 4. Install required packages
Core packages used include:

- `tidymodels`
- `readxl`
- `janitor`
- `dplyr`
- `ggplot2`
- `lubridate`
- `skimr`
- `vip`

### 5. Knit the reports
Knit each file to HTML to reproduce the analysis.

---
## Tools and Packages

This project uses **R** and the following packages:
# Wrangling and Visualization
- `readxl`
- `janitor`
- `lubridate`
- `skimr`
- `forcats`
- `scales`
- `tidyverse`

# Modelling
- `tidymodels`
- `ranger`     # random forest engine
- `xgboost`     # gradient boosting engine
- `vip`         # variable importance plot

# Tables
- `knitr`
- `kableExtra`

**GitHub** for version control, documentation, and reproducibility.

---

## Author

Maureen Amuche Nwobodo
