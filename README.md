# data-visualization-challenge
This is a repository for my module 5 Data Visualization Challenge
# Data and Summary Statistics
The datasets are merged into a single DataFrame. 

The number of mice are shown from the merged DataFrame. 

Each duplicate mice is found based on the Mouse ID and Timepoint. 

A clean DataFrame is created with the dropped duplicate mice. 

The number of mice are shown from the clean DataFrame. 

The mean of the tumor volume for each regimen is calculated using groupby. 

The media of the tumor volume for each regimen is calculated using groupby. 

The variance of the tumor volume for each regimen is calculated using groupby. 

The standard deviation of the tumor volume for each regimen is calculated using groupby. 

The SEM of the tumor volume for each regimen is calculated using groupby. 

A new DataFrame is created using the summary statistics. 
# Bar and Pie Charts
A bar plot showing the total number of timepoints for all mice tested for each drug regimen using Pandas and one using Pyploy is generated.

A pie plot showing the distribution of female versus male mice using Pandas and one using Pyplot is generated.
# New DataFrame 
A DataFrame that has the last timepoint for each mouse ID is created using groupby. 

Retrieved the maximum timepoint for each mouse. 

The four treatment groups, Capomulin, Ramicane, Infubinol, and Ceftamin, were put in a list. 

An empty list is created to fill with tumor volume data. 

A for loop is used to display the tumor volume data for each treatment group

Generated the IQR and Outlier data from the data in the for loop

A box plot is generated that shows the distribution of the final tumor volume for all the mice in each treatment group. 
# Line Plot, Scatter Plot, Correlation, Linear Regression
A line plot that shows the tumor volume vs. time point for one mouse treated with Capomulin. 

A scatter plot that shows average tumor volume vs. mouse weight for the Capomulin regimen.

The correlation coefficient and linear regression model are calculated for mouse weight and average tumor volume for the Capomulin regimen.
