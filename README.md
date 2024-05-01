Pymaceuticals Data Analysis

Introduction:
This repository contains the analysis of a real-world dataset from Pymaceuticals, Inc., a pharmaceutical company specializing in anti-cancer medications. The dataset pertains to a study on potential treatments for squamous cell carcinoma (SCC), a common form of skin cancer, conducted on 249 mice. The study compares the effectiveness of various drug regimens, with a focus on Pymaceuticals' drug of interest, Capomulin.

Files:
Download the necessary files for this analysis: mouse_metadata.csv and study_results.csv

Tasks:

1. Prepare the Data:
Merge the provided mouse_metadata and study_results DataFrames.
Check for and remove any duplicate mouse IDs with duplicate time points.

2. Generate Summary Statistics:
Create a DataFrame of summary statistics for each drug regimen, including mean, median, variance, standard deviation, and SEM of the tumor volume.

3. Create Bar Charts and Pie Charts:
Generate bar charts to visualize the total number of rows (Mouse ID/Timepoints) for each drug regimen.
Create pie charts to display the distribution of female versus male mice in the study.

4. Calculate Quartiles, Find Outliers, and Create a Box Plot:
Calculate final tumor volume for mice across promising treatment regimens (Capomulin, Ramicane, Infubinol, and Ceftamin).
Determine outliers and create a box plot showing the distribution of final tumor volume for each treatment group.

5. Create a Line Plot and a Scatter Plot:
Generate a line plot of tumor volume versus time point for a single mouse treated with Capomulin.
Create a scatter plot of mouse weight versus average observed tumor volume for the entire Capomulin treatment regimen.

6. Calculate Correlation and Regression:
Calculate the correlation coefficient and linear regression model between mouse weight and average observed tumor volume for the Capomulin treatment regimen.
Plot the linear regression model on top of the scatter plot.
