**Data Source and Packages:** 
1. Downloaded a raw data set from Kaggle on Smartwatch and Health.
2. Imported packages, such as pandas, matplotlib, seaborn, and numpy. 
3. Conducted the 5-inspection ritual method to understand the data.


**Data Cleaning:** 
proceeded to clean the data by doing the following:
1. Renamed variable names to match Python's naming rule.
2. Converted 'Error' texts to null values using numpy.
3. Dropped null values
4. Converted the data type in numeric columns to float
5. Corrected misspelt words in each of the cells.
6. Dropped the User ID column because it added no value to the data set
7. Filtered data to remove outliers (top 10% and bottom 5%)

   
**Exploratory Data Analysis:**
1. Created multiple histograms to observe the shapes of each of the variables and ascertain their skewness.
2. Conducted a correlation analysis using the seaborn heatmap feature: Variables have no linear relationship.
3. Built a scatterplot to observe non-linearity: Variables had no relationship.

   
**Conclusion:**
Pairwise correlation analysis and scatterplot visualization were used to assess 
linear and non-linear relationships among the five variables (heart rate, blood 
oxygen level, step count, sleep duration, and stress level). Correlation 
coefficients across all variable pairs were close to zero, and visual inspection 
of the corresponding scatterplots did not reveal any discernible non-linear 
patterns. Based on this combined evidence, I conclude that no meaningful linear or non-linear 
relationship exists among these variables in the current dataset.

**Limitations:** This analysis is based on pairwise associations only and does 
not account for potential interaction effects, confounding variables, or 
relationships involving three or more variables simultaneously. Absence of a 
pairwise correlation does not rule out more complex, multivariate relationships 
in the data.
