# machine_learning_project-unsupervised-learning

## Project Goals
- The goal of this project was to perform unsupervised learning techniques on a wholesale data dataset, this dataset includes the monetary unit (for sales) for each of product categories, as well as the channel they go through and the region they are sold in. The project involves four main parts: exploratory data analysis and pre-processing, KMeans clustering, hierarchical clustering, and PCA.

### Prcocess
In this project, we will apply unsupervised learning techniques to a real-world data set and use data visualization tools to communicate the insights gained from the analysis.

The data set for this project is the "Wholesale Data" dataset containing information about various products sold by a grocery store.
The project will involve the following tasks:

- Exploratory data analysis and pre-processing: Data was imported and cleaned, the relationships between the different variables were then visualized and analyzed, missing values and outliers were checked for and handled, and feature engineering was performed as needed.
- Unsupervised learning models: the Wholesale Data dataset was used to perform k-means clustering, hierarchical clustering, and principal component analysis (PCA) to identify patterns and group similar data points together. The optimal number of clusters was also determined for each model.

### Results
From the model results, we found that the most optimal amount of clusters for the KMeans model was 6, where as the most optimal amount for the Hierarchical Clustering was only 3 clusters, and from the PCA analysis, we found that the compound combinations of features of PC1, PC2, and PC3 are the ones that best describe the customers, since they have the highest variance ratios,and since these 3 compound combinations together make up for ~83% of the information.

The key findings and results from this project are:
- From the EDA, We found that there are 2 channels of revenue, with most of it coming from channel 1 across all products, and we see that there are 3 regions of sales, with most of it coming from region 3 across all product categories.
- From the EDA, we found that there are quite a few notable correlations between the features. These include a very strong correlation for Detergents_Paper and Grocery, Grocery and Milk, Detergents_Paper and Milk. We also see that there is also a strong correlation between Detergents_Paper and Channel, and Grocery and Channel, which shows that for these product categories, the channel they go through is very correlated to the sales.
- From the unsupervised learning models, we found that the most optimal amount of clusters for the KMeans model was 6, where as the most optimal amount for the Hierarchical Clustering was only 4 clusters. Having more clusters means that each data in the clusters more compact and more specific. From a business perspective, having 6 clusters would mean that the clients are more specifically grouped, and the business can therefore talor their investment/marketing strategies
more closely to each of the client groups, whereas only 4 clusters means the clients are grouped more generally, and the business can therefore make more generalized investment/marketing strategies.
- Looking at the cluster with the most amount of clients in in for both models, we can see that products of the "Fresh" and "Grocery" categories had by far the highest average annual spending for clients in the cluster, and products of the categories "Detergents_Paper" and "Delicassen" had by far the lowest average annual spending. This shows us that clients in the most populated cluster regardless of the model spending far more money annually on Fresh and Grocery products than any other category of products, and spending the least on Detergents_Paper and Delicassen products. Since the most populated cluster for both models show this, we can use this to make better business decisions by focusing and investing more on the products of the Fresh and Grocery categories(as the most amount of clients spend the most amount of money on them) in order to generate more annual revenue. 
- From the PCA analysis, we found that the compound combinations of features of PC1, PC2, and PC3 are the ones that best describe the customers, since they have the highest variance ratios,and since these 3 compound combinations together make up for ~83% of the information.

