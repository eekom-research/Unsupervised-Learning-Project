# machine_learning_project-unsupervised-learning

## Project Description:
In this project, we will apply unsupervised learning techniques to a real-world data set and use data visualization tools to communicate the insights gained from the analysis.

The data set for this project is the "Wholesale Data" dataset containing information about various products sold by a grocery store.
The project will involve the following tasks:

### Exploratory data analysis and pre-processing: 
We will import and clean the data sets, analyze and visualize the relationships between the different variables, handle missing values and outliers, and perform feature engineering as needed.

### Unsupervised learning: 
We will use the Wholesale Data dataset to perform k-means clustering, hierarchical clustering, and principal component analysis (PCA) to identify patterns and group similar data points together. We will determine the optimal number of clusters and communicate the insights gained through data visualization.

## Conclusions:
* Overall, there are two main clusters in segmenting the clients for the wholesale datasets. The first cluster prefers mostly `Fresh` produce and the other cluster being more balanced but also favouring the `Milk`,`Grocery`, and `Detergents_Paper` products.
* If more granularity is sort, at the expense of greater complexity, then, using the elbow method, we can partition the clientele into five sub-clusters. These clusters are described below.
* Cluster 0 is distinguished by a significantly higher purchase volume in `Fresh`, indicating these clients likely prioritize fresh produce.
* Cluster 1 features the most diverse set of purchases with relatively high sales in `Milk`, `Grocery`, and `Detergents_Paper`, suggesting these clients may be small retailers or grocery stores.
* Cluster 2 has moderate purchasing volumes across most product categories but is notably less for `Fresh` and `Frozen`, possibly representing smaller households or clients with limited storage.
* Cluster 3 shows a preference for `Frozen` products and relatively lower median sales in other categories, which might indicate clients like cafes or small eateries that use more frozen goods.
* Cluster 4 has the lowest median sales across all product categories, which could imply these are clients with low purchasing volumes, such as small, independent buyers.

