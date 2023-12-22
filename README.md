# Bank Churn Prediction & Profiling Presentation

This documentation provides an overview and detailed analysis of the "Bank Churn Prediction & Profiling Presentation"
## Table of Contents

- [Overview](#overview)
- [Part 1: Data Preparation and Customer Segmentation](#part-1-data-preparation-and-customer-segmentation)
- [Part 2: Defined Focus Group and Prediction Model](#part-2-defined-focus-group-and-prediction-model)
- [Part 3: Customers and Churners Profiling](#part-3-customers-and-churners-profiling)
- [Part 5: Business Impact](#part-5-business-impact)
- [Conclusion](#conclusion)

## Overview

### Data Flow & Dataset
- **Data Set:** Involves a dataset of bank churn customers with 13 schema elements.

## Part 1: Data Preparation and Customer Segmentation

### Data Preparation Steps
1. Change Column Type
2. Replace Value
3. Clean Outlier

### Cluster Modeling
- Utilization of Elbow Method & Silhouette Score for cluster number determination (K = 4, 5).

### Cluster Training Result
- Four customer segments identified:
  1. Basic Account Holders
  2. Active Savers
  3. High-Value Customers
  4. Premium Clients

### Outlier Separation
- Process to separate cluster outliers is included.

## Part 2: Defined Focus Group and Prediction Model

### Focus Group for Churn Prediction
- Basic Account Holders & High-Value Customers with high churn ratios targeted.

### Model Development
- Data split into focus and non-focus groups.
- Resampling and K-fold cross-test for class imbalance.
- Evaluation metrics: AUC & F1 Score.
- Feature handling and algorithm selection detailed.

### Training Results
- Emphasis on variable importance.
- Confusion & cost metrics, lift chart.
- Training dataset prediction accuracy: 74.4%.

## Part 3: Customer & Churner Profile
- Detailed profiles for customers and churners (specifics not visible in provided sections).

## Part 5: Business Impact

### Impact Analyses
1. Upsell/cross-sell strategies for Basic Account Holders to convert them into Active Savers.
2. Retention program implementation for High-Value Customers and Basic Account Holders.
3. Cost-saving and reduced opportunity loss via churn prediction ML models.

## Conclusion

The presentation effectively details the processes of data preparation, segmentation, churn prediction, customer profiling, and the resulting business impacts. It emphasizes the significance of identifying high-churn customer segments and strategies for improving customer retention and reducing churn-related costs.