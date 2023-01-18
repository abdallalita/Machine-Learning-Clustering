## Introduction
Customer Segmentation for a certain Motorvehicle company that plans to enter new markets with their existing products; to assist the sales team in predicting the right group
of new customers for their advertising campaigns.

---
### Overview
The dataset has 10695 rows and 11 columns with mixed features (Numerical and Categorical). I dropped 3 variables that had leakage features and high cardinality for the segmentation
problem. Any mssing values were replaced through the Median Imputation method. I opted for K-Prototypes algorithm, which is a hybrid clustering algorithm that can process both
categorial and numerical simultaneously data as opposed to the K-Mean which is only feasible with numerical values and K-Modes which works best with the categorical values.

