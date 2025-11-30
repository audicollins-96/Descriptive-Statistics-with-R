---
title: "Whitehall Study (FoSSA Course) Dataset"
author: "Your Name"
date: "`r Sys.Date()`"
output: html_document
---

# About the Dataset

The **Whitehall Study (By Oxford FoSSA Course)** is a simulated cohort study similar to the original Whitehall Study of Civil Servants, set up in the 1960s. It followed London-based male civil servants to investigate cardiovascular disease and mortality.  

Participants from the original Whitehall cohort in the 1960s were flagged for mortality at the **Office for National Statistics**, which provided the date and cause of all deaths occurring until the end of September 2005.  

The (simulated) Whitehall FoSSA Study was conducted in 1997 to assess risk factors for cardiac and all-cause mortality in a subset of the original cohort that was still being followed.  

The Whitehall FoSSA Study contains information on **4,327 individuals** followed from 1997 until 2005. The variables are summarized in the table below.  

For more details on the real data that inspired this dataset, see:  
Clarke et al. (2007), *Arch Intern Med*, 167(13).

---

# Descriptive Statistics with the Whitehall Study (FoSSA Course Simulation)

The following steps were performed in analyzing the dataset:

- Imported and checked dataset structure
- Transformed variables and created categories (e.g., BMI, SBP)
- Calculated means, medians, standard deviations, quartiles, standard errors, and confidence intervals
- Visualized distributions using histograms and bar plots
- Practiced **tidyverse** and **DescTools** for data manipulation and statistics
