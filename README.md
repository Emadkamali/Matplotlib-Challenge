# Matplotlib-Challenge

This repository encompasses a Python script designed for the thorough analysis of data from Pymaceuticals Inc., a pharmaceutical company specializing in anti-cancer medications, particularly for treating squamous cell carcinoma (SCC), a type of skin cancer, through an animal study. The script efficiently handles data preparation tasks by merging information from mouse metadata and study results CSV files into a consolidated DataFrame, subsequently eliminating duplicate entries.

# Overview 

The analysis encompasses the computation of essential summary statistics, including mean, median, variance, standard deviation, and standard error of the mean (SEM) for tumor volume associated with each drug regimen. Additionally, the script employs Pandas and Matplotlib to craft informative bar charts illustrating the total number of timepoints for each drug regimen, along with pie charts visualizing the gender distribution among mice.

Further analysis involves the determination of quartiles, identification of outliers, and the creation of box plots elucidating the distribution of final tumor volume across selected treatment regimens (Capomulin, Ramicane, Infubinol, and Ceftamin).

Moreover, the script generates insightful line and scatter plots, depicting tumor volume versus time point for a singular mouse undergoing Capomulin treatment, as well as showcasing the correlation between mouse weight and the average observed tumor volume throughout the entire Capomulin regimen. The inclusion of linear regression analysis enhances the visualization, with the resulting model overlaid on the scatter plot for a comprehensive understanding of the relationship between mouse weight and tumor volume.





