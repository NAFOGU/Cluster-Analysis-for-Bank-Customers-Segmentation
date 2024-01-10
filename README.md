# Cluster-Analysis-for-Bank-Customers-Segmentation

## Introduction
Banks provide financial services to customers and in order to render quality service to diverse customer needs it is important to understand the different customer categories. Effective customer segmentation enables banks to properly classify their customers for the purpose of tailored service delivery, product development and marketing.

This work seeks to implement two machine learning algorithms to segment the customers of a bank (name not provided) in order to facilitate effective service delivery.

## Dataset
The dataset employed for this study is a publicly accessible dataset obtained from Kaggle (https://www.kaggle.com/datasets/parsagouran/bank-customer-segmentation-dataset/data), comprising of data from 8,950 bank customers. It was collected for the purpose of categorizing customers into different segments for marketing purposes. The dataset contains 18 features that are related to the purchasing behavior of the bank’s customers and will serve as the foundation of applying machine learning algorithms to extract groups of customers based on their unique behavioral patterns.

## Results and Discussion
In the analysis, cluster labels were assigned to the original dataset based on K-Means and Agglomerative algorithms, revealing that customers with an average balance above 1,800 tend to make frequent high-value purchases and possess an average credit limit exceeding 6,000. The Silhouette scores for both algorithms indicate that, while there may be some overlap in customer characteristics across clusters, K-Means performs slightly better in effectively separating bank customers into distinct clusters compared to the Agglomerative algorithm.
