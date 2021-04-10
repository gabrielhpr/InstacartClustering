# InstacartClustering

## Description
This is a customer segmentation project. In this project the customers of Instacart Company were 
segmented in 5 groups using **K-Means Clustering Algorithm**. I also used **RFM analysis (Recency,
Frequency, Monetary)** to evaluate the clustering algorithm over theses metrics and to find the relative 
importance of each group and to create solutions to improve the company revenue based on each cluster’s behavior.

Applied all data science steps, including data cleaning, exploratory
data analysis, data preparation, creation of a machine learning model
and performance analysis (Silhouette score and Distortion).

### Dataset
The dataset used contains a sample from the original dataset: https://www.kaggle.com/c/instacart-market-basket-analysis/data.

### Filling Null values
The variable **days_since_prior_order** had it's null values filled with 0, because we assumed that if it's null it's due to 
the fact that it's the first purchase of the customer.

### How RFM metrics were obtained ?

RFM stands for Recency, Frequency and Monetary, as the dataset does not contain products prices, neither the date of each purchase,
we had to make some assumptions.

**Recency** - it was derived from the mean of the gap between the purchases already done by each customer.

**Frequency** - it was derived from the quantity of orders.

**Monetary** - it was derived from the amount of products bought by each customer.

