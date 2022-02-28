# Customer-Segmentation

KMEANS CLUSTERING

The wholesale customers dataset was downloaded fromthe UCIrepository which contains information about the annual spending on different product categoriesand also different locations. This analysis aims to cluster the dataset according to the products being brought.The dataset contains 440 rows and 8 variables.This analysis aims to categorize customers ith similar behavioral characteristics

EXPLORATORY DATA ANALYSIS

The statistical summary of the dataset shows information such as the mean, standard deviation, percent quantile and other statistics. The region and channel column was dropped since we are only clustering based on products hereby remaining 440 rows and 6 columns. There was no missing values in the dataset.The scatterplot shows that the variables were heavily skewed therefore natural log transformation was applied to the dataset hereby giving a more normally distributed outcome(figure 2).A heat map was also used to see if there are any correlations between the variables: grocery and detergents paper seems to have a high correlation.

Outliers mostly affects the results of clustering therefore outlier detection is very important in our analysis.Tukey’s method which uses interquartile range was used to identify and eliminate the outliershereby remaining 426 rows and 6 columns.

CLUSTERING

The elbow method using distortion was used to determine the optimal number of k means clustering to be used.The elbow shows a value a value as the elbow point, I used between 3 and 5 to find the best clusters.Different clusters are were carried out on the datato find the best one that fits.To further our k means analysis, another variable clusterwas added to the variables to represent clusterseach rows in the dataset representsso as to show the clusters based on clients who buys each wholesale products based on the Channel (hotel, Café or Restaurant) they are buying from.Inertia which is the within sum of squares criteria was used to evaluate how good the clusters. The elbow graph was drawn on the inertia values which gave a value of 5 as optimal values.Principal Component analysis(PCA) was applied to the dataset to improve the results of the cluster analysisthereby giving us a better number of clusters.

The distribution was clustered based on the annual spending on products like frozen and fresh food and also between correlated variables.The customers in each clusters are categorized based on similarities to each other behaviorally.CONCLUSION.This canhelp the distributor to segment customers based on the channel through which the clients are buying the products either through hotels, restaurants and cafes. Also annual spending for clients buying detergentspaper and grocery seems high this could possibly be from hotel who cooks food from groceries and also provide detergent papers to each room. This would make the distributor make informed decisions
