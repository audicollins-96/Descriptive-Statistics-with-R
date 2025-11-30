#Descriptive Analysis of Health Data

This is a summary of my descriptive analysis of the **Whitehall FoSSA Study**, a simulated dataset inspired by the original Whitehall Study of Civil Servants. The dataset contains information on **4,327 participants** followed from 1997 to 2005, focusing on cardiovascular risk factors and mortality.

---

## Steps Taken

1. **Data Inspection**  
   - Imported the dataset and checked its structure, dimensions, and variable types.  
   - Identified continuous variables (BMI, SBP, cholesterol) and categorical variables (smoking status).

2. **Variable Transformation**  
   - Categorized **smoking status** as "Yes" or "No".  
   - Grouped **BMI** into standard categories (underweight, normal, overweight, obese) and a simpler "Not obese / Obese" classification.  
   - Categorized **LDL cholesterol** into "4 or below" and "above 4".  
   - Grouped **SBP** into clinical categories from normotensive to stage 2 hypertension.

3. **Descriptive Statistics**  
   - Calculated measures of central tendency and variability (mean, median, quartiles, standard deviation, confidence intervals).  
   - Examined the distribution and classification of variables to understand patterns and outliers.

4. **Visualization**  
   - Created histograms and bar plots to explore distributions of BMI, SBP, and other key variables.  
   - Used grouping and color coding to highlight participant characteristics and trends.

---

## Key Findings

- **BMI**: Most participants were healthy or overweight; few were underweight or obese.  
- **Blood Pressure**: Majority were normotensive or slightly elevated; fewer had stage 1 or stage 2 hypertension.  
- **Smoking**: Current smokers were a minority of the cohort.  
- **LDL Cholesterol**: Most participants fell into the lower risk category (≤4).  

These results provide a clear overview of the cohort and highlight patterns relevant to cardiovascular risk.

---

## References

Clarke et al. (2007), *Arch Intern Med*, 167(13) — details of the original Whitehall Study that inspired this dataset.
