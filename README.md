# kerala flood prediction
This notebook walks through the data cleaning, preprocessing, and visualization steps to explore the dataset for flood prediction in kerala from 1900 to 2020. It includes:

Handling missing values
Handling duplicate values
Correlation analysis
Univariate and bivariate analysis
Visualization using plots and graphs
Dataset

Name: kerala.csv 
Source: Kaggle, UCI Machine Learning Repository 
Rows: 118
Columns:16

Tools & Libraries Used

Python 3.x Pandas NumPy Matplotlib Seaborn Jupyter Notebook

Objectives

To understand the relation of each features provided in the dataset with the flood prediction.
Identify missing or anomalous values
Visualize relationships between variables
Generate hypotheses for further analysis or modeling
Description

This data set contains year ,rainfall in each month,annual rainfall and fllod occurence as atrributes.
In this EDA, I found out that how these attributes influences the occurence of flood.
for that first step is to clean the data.
removed the duplicate values.
visualized relation between each attribute with the income and made inferences
Conclusion

The conclusions from this EDA are:

Rain fall during may,jun,july,august and september are correlated with annual rainfall.
July month shows the highest correlation with the annual rain fall
There was flood when annual rainfall is between 3000 and 3500.
Tere are some outliers in annulal rainfall when flood occured. Since it is a significant data, we can not treat this outlier.
There is no outliers when there is no flood. so if the annual rainfall is around 2500 there is no chance for flood.
The annual rainfall influences occurences of flood.
Maximum rainfall occured in 2018.
In 2018 the rain fall increasing from jun and the rainfall was maximum in august.
Maximum average rainfall occured during the months of jun, july and august.
From 1900 to 2020, about half of the years experienced floods.
