
# My Analysis Story

I had the opportunity to explore the **Whitehall FoSSA Study**, a simulated dataset inspired by the original Whitehall Study of Civil Servants from the 1960s. This dataset includes information on **4,327 participants** followed from 1997 to 2005, with the goal of understanding risk factors for cardiovascular disease and mortality.

---

## Getting to Know the Data

I started by importing and inspecting the dataset to understand its structure, dimensions, and variable types. This step was crucial for planning how to transform the data and prepare it for analysis. I checked categorical variables such as smoking status, and continuous variables like BMI, blood pressure, and cholesterol levels.  

---

## Transforming Variables

To make the analysis meaningful, I created categories for key variables:  

- **Smoking status** was labeled as "Yes" or "No".  
- **BMI** was categorized into standard groups (underweight, normal, overweight, obese) and also into a simpler "Not obese / Obese" classification.  
- **LDL cholesterol** was categorized into “4 or below” and “above 4”.  
- **Systolic blood pressure (SBP)** was grouped into clinical categories from normotensive to stage 2 hypertension.  

These transformations allowed me to summarize trends and visualize patterns effectively.

---

## Descriptive Statistics

I summarized the dataset using descriptive statistics to understand central tendencies and variability:  

- Calculated **means, medians, quartiles, interquartile ranges, standard deviations, and confidence intervals**.  
- Examined distributions and identified outliers in variables like BMI, SBP, and cholesterol.  
- Categorized variables as binary, continuous, or ordinal to guide analysis.  

This step provided a clear sense of the overall patterns and characteristics of the participants.

---

## Visualizing the Data

Visualization helped bring the data to life:  

- **BMI** was shown using bar plots and histograms, revealing that most participants were in the healthy and overweight ranges, with fewer underweight and obese individuals.  
- **SBP** was visualized with histograms using both fine and broad bin widths, showing the distribution from normotensive to hypertensive participants.  
- Color gradients and grouping enhanced the clarity of these plots, making patterns easy to interpret at a glance.  

---

## Key Takeaways

Through this analysis, I learned to:  

- Transform and categorize variables to facilitate understanding.  
- Calculate and interpret descriptive statistics for both continuous and categorical data.  
- Create visual summaries that highlight key trends in the dataset.  
- Tell a coherent story about participant characteristics and risk factors, rather than just presenting numbers.  

This project reinforced the importance of **tidy data practices** and clear, visual communication when exploring complex health datasets.

---

## References

Clarke et al. (2007), *Arch Intern Med*, 167(13) — for details on the original Whitehall Study that inspired this dataset.
