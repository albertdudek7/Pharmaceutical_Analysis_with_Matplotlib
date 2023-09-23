# Pharmaceutical Analysis with Matplotlib

Conducting analysis on a fictional new pharmaceutical company, Pymaceuticals, that specializes in anti-cancer medications. Recently, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

Granted access to the complete data from their most recent animal study. In this study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

Tasks include tables and figures needed for the technical report of the clinical study. As well as a top-level summary of the study results.

Preparing the data.
![image](https://github.com/albertdudek7/Pharmaceutical_Analysis_with_Matplotlib/assets/127783844/5880eccd-ac5a-4657-b4b3-351b9bbef694)
![image](https://github.com/albertdudek7/Pharmaceutical_Analysis_with_Matplotlib/assets/127783844/e362aed0-dbbd-4a0d-9819-cc58518c497d)

Generating summary statistics.
![image](https://github.com/albertdudek7/Pharmaceutical_Analysis_with_Matplotlib/assets/127783844/34effc00-fda3-4e04-9476-3185a1c49d83)
![image](https://github.com/albertdudek7/Pharmaceutical_Analysis_with_Matplotlib/assets/127783844/fbaeb839-397b-44a3-9e6d-e1cbea665e83)

Created bar charts and pie charts.
![image](https://github.com/albertdudek7/Pharmaceutical_Analysis_with_Matplotlib/assets/127783844/57011b37-4fae-4d68-87a6-5dfa1c15e7b1)
![image](https://github.com/albertdudek7/Pharmaceutical_Analysis_with_Matplotlib/assets/127783844/e8197dac-a011-40ea-86da-f701f027e31f)
![image](https://github.com/albertdudek7/Pharmaceutical_Analysis_with_Matplotlib/assets/127783844/d5e04d06-f70a-4fba-bd79-fc1f4e54897a)

Calculated quartiles, find outliers, and created a box plot.
![image](https://github.com/albertdudek7/Pharmaceutical_Analysis_with_Matplotlib/assets/127783844/85712eaa-64e6-49eb-9e90-d08f79757410)
![image](https://github.com/albertdudek7/Pharmaceutical_Analysis_with_Matplotlib/assets/127783844/cb5d1485-4858-47a0-b70f-8f765420355b)
![Uploading image.png…]()

Created a line plot and a scatter plot.

Calculate correlation and regression.

Submit your final analysis.



Your summary statistics should include:

A row for each drug regimen. These regimen names should be contained in the index column.

A column for each of the following statistics: mean, median, variance, standard deviation, and SEM of the tumor volume.

Create Bar Charts and Pie Charts
Generate two bar charts. Both charts should be identical and show the total total number of rows (Mouse ID/Timepoints) for each drug regimen throughout the study.

Create the first bar chart with the Pandas DataFrame.plot() method.

Create the second bar chart with Matplotlib's pyplot methods.

Generate two pie charts. Both charts should be identical and show the distribution of female versus male mice in the study.

Create the first pie chart with the Pandas DataFrame.plot() method.

Create the second pie chart with Matplotlib's pyplot methods.

Calculate Quartiles, Find Outliers, and Create a Box Plot
Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Then, calculate the quartiles and IQR, and determine if there are any potential outliers across all four treatment regimens. Use the following substeps:

Create a grouped DataFrame that shows the last (greatest) time point for each mouse. Merge this grouped DataFrame with the original cleaned DataFrame.

Create a list that holds the treatment names as well as a second, empty list to hold the tumor volume data.

Loop through each drug in the treatment list, locating the rows in the merged DataFrame that correspond to each treatment. Append the resulting final tumor volumes for each drug to the empty list.

Determine outliers by using the upper and lower bounds, and then print the results.

Using Matplotlib, generate a box plot that shows the distribution of the final tumor volume for all the mice in each treatment group. Highlight any potential outliers in the plot by changing their color and style.

hint: All four box plots should be within the same figure. Use this Matplotlib documentation pageLinks to an external site. for help with changing the style of the outliers.

Create a Line Plot and a Scatter Plot
Select a single mouse that was treated with Capomulin, and generate a line plot of tumor volume versus time point for that mouse.

Generate a scatter plot of mouse weight versus average observed tumor volume for the entire Capomulin treatment regimen.

Calculate Correlation and Regression
Calculate the correlation coefficient and linear regression model between mouse weight and average observed tumor volume for the entire Capomulin treatment regimen.

Plot the linear regression model on top of the previous scatter plot.

