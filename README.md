# Customer-Segmentation

KMEANS CLUSTERING
The wholesale customers dataset was downloaded fromthe UCIrepository which contains information about the annual spending on different product categoriesand also different locations. This analysis aims to cluster the dataset according to the products being brought.The dataset contains 440 rows and 8 variables.This analysis aims to categorize customers ith similar behavioral characteristics

EXPLORATORY DATA ANALYSIST=
The statistical summary of the dataset shows information such as the mean, standard deviation, percent quantile and other statistics. The region and channel column was dropped since we are only clustering based on products hereby remaining 440 rows and 6 columns. There was no missing values in the dataset.The scatterplot shows that the variables were heavily skewed therefore natural log transformation was applied to the dataset hereby giving a more normally distributed outcome(figure 2).A heat map was also used to see if there are any correlations between the variables: grocery and detergents paper seems to have a high correlation.



Outliers mostly affects the results of clustering therefore outlier detection is very important in our analysis.Tukey’s method which uses interquartile range was used to identify and eliminate the outliershereby remaining 426 rows and 6 columns.
