# pyplot-challenge

In this analysis, we delved deep into the study of various tumor treatment regimens on mice. The data was analyzed to determine the efficacy of different treatments, identify outliers, visualize the findings using multiple charting techniques, and calculate statistical correlations.

# Generate Summary Statistics
The data was summarized to provide insight into each drug regimen. The summary statistics included:

    - Mean of the tumor volume
    - Median of the tumor volume
    - Variance of the tumor volume
    - Standard deviation of the tumor volume
    - SEM of the tumor volume

# Create Bar Charts and Pie Charts
Two bar charts were generated showing the total number of rows (Mouse ID/Timepoints) for each drug regimen:

    - One was created using Pandas DataFrame.plot()
    - Another was created using Matplotlib's pyplot

Additionally, two pie charts were generated to display the distribution of female vs. male mice:

    - One using Pandas DataFrame.plot()
    - One using Matplotlib's pyplot

# Calculate Quartiles, Find Outliers, and Create a Box Plot
The final tumor volume for the four major treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin was calculated. Following this, quartiles and the IQR were computed, and potential outliers for each regimen were identified. A box plot was generated to visualize the final tumor volume for each regimen, with outliers easily identifiable.

# Create a Line Plot and a Scatter Plot
A line plot was generated for a selected mouse that was treated with Capomulin, showcasing the tumor volume vs. time point for that mouse. A scatter plot was also created to visualize the relationship between mouse weight and the average observed tumor volume for the Capomulin regimen.

# Calculate Correlation and Regression
The correlation coefficient between mouse weight and average tumor volume for the Capomulin regimen was calculated. A linear regression model was computed, and its representation was overlaid on the previously mentioned scatter plot.
