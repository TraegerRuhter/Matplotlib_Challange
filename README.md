# Matplotlib_Challange

## Pymaceuticals Inc. Anti-Cancer Medication Analysis
Overview
Pymaceuticals, Inc. is a pharmaceutical company that specializes in anti-cancer medications. This analysis revolves around a study of 249 mice with SCC tumors treated with various drug regimens over 45 days. The primary objective was to evaluate the efficacy of Pymaceuticals' drug, Capomulin, against other treatments.

## Data Preparation

Merging Datasets: The datasets mouse_metadata and study_results were merged into one DataFrame.

Data Cleaning: Duplicate mice data, based on Mouse ID and Timepoint, were identified and removed. The cleaned DataFrame was used for all subsequent analyses.

## Analysis Details
1. Summary Statistics
Calculation of tumor volume statistics for each drug regimen:
Mean
Median
Variance
Standard Deviation
SEM
2. Visualization
Bar Charts: Two bar charts were created to display the total number of timepoints for all mice tested for each drug regimen. One chart was created using Pandas and the other using Matplotlib's pyplot.
Pie Charts: Two pie charts were generated to show the gender distribution of mice in the study. Again, one was made with Pandas and the other with pyplot.
3. Quartiles, Outliers, and Box Plot
Focused on four treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin.
Calculated the final tumor volume for each mouse in these regimens.
Computed quartiles, IQR, and identified any potential outliers.
A combined box plot was created to visualize the tumor volume distribution for each treatment, with any outliers highlighted.
4. Line and Scatter Plots
Line Plot: Showcased the tumor volume vs. time point for a single mouse treated with Capomulin.
Scatter Plot: Illustrated the relationship between mouse weight and the average tumor volume for the Capomulin regimen.
5. Correlation and Regression
Calculated the correlation coefficient between mouse weight and average tumor volume for mice on Capomulin.
Generated a linear regression model and plotted it atop the previously created scatter plot.

## Conclusions
The results from this analysis offer insights into the performance of Capomulin against other drug regimens. The visualizations and statistics serve as foundational evidence for potential next steps in the research and development process.
