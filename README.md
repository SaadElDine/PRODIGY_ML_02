# Customer Segmentation Project (K-means)

This project aims to segment customers of a retail store based on their purchase history using K-means clustering. The project uses the `customer-segmentation-tutorial-in-python` dataset from Kaggle, which contains information about customers' gender, age, annual income, and spending score.

![image](https://github.com/SaadElDine/PRODIGY_ML_02/assets/113860522/cea1e038-302e-47af-985e-d5ffa9eb3d44)


## Dataset
- **Dataset Source:** [Customer Segmentation Tutorial in Python](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
- **Data Shape:** (200, 5)
- **Attributes:**
  - CustomerID
  - Gender
  - Age
  - Annual Income (k$)
  - Spending Score (1-100)

## Preprocessing
- Removed the `CustomerID` column as it is not relevant for clustering.
- Handling missing values
- remove outliers
- normalization
- Encoded the categorical data `Gender` using one-hot encoding.

## K-means Clustering
- Used sklearn's KMeans algorithm to perform clustering.
- Chose the number of clusters (K=4) based on the elbow method.
- Fit the KMeans model to the selected features.
- Added the cluster labels to the original dataset.
- Visualized the clusters using matplotlib and seaborn.
- Analyzed the clusters to understand the characteristics of each group.

## Results
- The K-means clustering algorithm successfully grouped the customers into 4 clusters.
- Each cluster represents a distinct segment of customers based on their annual income and spending score.
- These clusters can be used for targeted marketing strategies to tailor products and services to specific customer segments.

## Conclusion
The clustering analysis provides valuable insights into customer segmentation, which can be used for personalized marketing strategies and business decisions.

