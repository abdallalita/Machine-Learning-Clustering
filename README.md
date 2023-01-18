## Introduction
The projects are about Customer Segmentation for a certain Motorvehicle company and a Supermarket Mall both of which are planning to enter new markets with their existing products. I aim to assist the sales and Marketing team in predicting the right group
of new customers for their advertising campaigns or plan their strategy accordingly.

---
## [Motorvehicle company Segmentation](motor)
### motor
The dataset had 10695 rows and 11 columns with mixed features (Numerical and Categorical). I dropped 3 variables that had leakage features and high cardinality for the segmentation
problem. Any mssing values were replaced through the Median Imputation method. I opted for K-Prototypes algorithm, which is a hybrid clustering algorithm that can process both
categorial and numerical simultaneously data as opposed to the K-Mean which is only feasible with numerical values and K-Modes which works best with the categorical values.





