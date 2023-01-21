## Introduction
The projects are about Customer Segmentation for a certain Motorvehicle company and a Supermarket Mall both of which are planning to enter new markets with their existing products. I aim to assist the sales and Marketing team in predicting the right group
of new customers for their advertising campaigns or plan their strategy accordingly.
## [Motorvehicle company Segmentation](#Overview-1)
## [Supermarket mall segmentation](#Overview-2)
### Overview 1
The dataset had 10695 rows and 11 columns with mixed features (Numerical and Categorical). I dropped 3 variables that had leakage features and high cardinality for the segmentation
problem. Any mssing values were replaced through the Median Imputation method. I opted for K-Prototypes algorithm, which is a hybrid clustering algorithm that can process both
categorial and numerical simultaneously data as opposed to the K-Mean which is only feasible with numerical values and K-Modes which works best with the categorical values

---
### Overview 2
The dataset had 200 rows and 5 columns.I dropped two columns that had irrelevant data for the problem. The dataset had no missing values.
I opted for K-Means algorithm due to the fact that the dataset had all numerical features feasible with the K-Means algorithm. I created a pipeline that consisted of
the `StandarScaler()` transformer and the `K-Means()` algorithm. I finally applied the Principal Component Analysis (PCA) to perform dimensionality reduction. The data
was transformed from  higher dimension, say 5D to a lower one, 2D, while maintaining as much information as possible.



