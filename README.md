# Pymaceuticals-Project

This repository encompasses a Python script designed for the thorough analysis of data from Pymaceuticals Inc., a pharmaceutical company specializing in anti-cancer medications, particularly for treating squamous cell carcinoma (SCC), a type of skin cancer, through an animal study. The script efficiently handles data preparation tasks by merging information from mouse metadata and study results in CSV files into a consolidated DataFrame, subsequently eliminating duplicate entries.

# Analysis

- Identification of Outliers: The outlined circles effectively highlight extreme data points, facilitating the identification of outliers within the dataset.

- Visual Focus: The use of contrasting colours effectively draws attention to outliers, making them visually prominent within the boxplot.

- Insights into Data Distribution: The boxplot offers a succinct overview of the dataset's distribution, presenting essential statistical measures such as the median, quartiles, and range.

- Interpretation of Regression Line: The linear regression line visually illustrates the relationship between mouse weight and average tumour volume. Its slope indicates the rate of change in tumour volume per unit change in weight, while the intercept signifies the estimated tumour volume when weight is zero.

- The correlation coefficient between mouse weight and average tumour volume is 0.84, indicating a robust positive correlation between these variables. This suggests that as mouse weight increases, the average tumour volume tends to increase as well.

# Overview 

The analysis encompasses the computation of essential summary statistics, including mean, median, variance, standard deviation, and standard error of the mean (SEM) for tumour volume associated with each drug regimen. Additionally, the script employs Pandas and Matplotlib to craft informative bar charts illustrating the total number of time points for each drug regimen, along with pie charts visualizing the gender distribution among mice.

The further analysis involves the determination of quartiles, identification of outliers, and the creation of box plots elucidating the distribution of final tumour volume across selected treatment regimens (Capomulin, Ramicane, Infubinol, and Ceftamin).

Moreover, the script generates insightful line and scatter plots, depicting tumour volume versus time point for a singular mouse undergoing Capomulin treatment, as well as showcasing the correlation between mouse weight and the average observed tumour volume throughout the entire Capomulin regimen. The inclusion of linear regression analysis enhances the visualization, with the resulting model overlaid on the scatter plot for a comprehensive understanding of the relationship between mouse weight and tumour volume.





