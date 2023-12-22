# Bank Churn Prediction & Profiling

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
- **Data Flow:**

![dataflow](https://github.com/Toeyeses/Bank_ChurnPredict-Profile/assets/128026055/607a5b95-4e16-4a9a-9b5a-b15702788212)

- **Data Set:** Involves a dataset of bank churn customers with 13 schema elements.

![dataset](https://github.com/Toeyeses/Bank_ChurnPredict-Profile/assets/128026055/2b6c8982-b0a8-4ba8-84de-3eecd82b22e7)

## Part 1: Data Preparation and Customer Segmentation

### Data Preparation Steps
1. Change Column Type
2. Replace Value
3. Clean Outlier

### Cluster Modeling
- Utilization of Elbow Method & Silhouette Score for cluster number determination (K = 4, 5).
  
![clusde](https://github.com/Toeyeses/Bank_ChurnPredict-Profile/assets/128026055/c2bc1fd1-be68-4655-8b3e-7e3b45ba8d8e)

### Cluster Training Result

![clusre](https://github.com/Toeyeses/Bank_ChurnPredict-Profile/assets/128026055/c3d9435e-7ee1-409b-b0c1-b12643164bb5)

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
  
![focus](https://github.com/Toeyeses/Bank_ChurnPredict-Profile/assets/128026055/4a1b5654-8d1f-4ae4-981f-27824a1f82c6)

### Model Development
- Data split into focus and non-focus groups.
- Resampling and K-fold cross-test for class imbalance.

![churnmo](https://github.com/Toeyeses/Bank_ChurnPredict-Profile/assets/128026055/5ce57a8c-4167-4aca-8c2a-82fb8b7df547)

- Evaluation metrics: AUC & F1 Score.

![churnmo 1](https://github.com/Toeyeses/Bank_ChurnPredict-Profile/assets/128026055/bfea620d-43bd-432f-a453-9744f7617045)

- Feature handling and algorithm selection detailed.

![churnde](https://github.com/Toeyeses/Bank_ChurnPredict-Profile/assets/128026055/414fd0e4-f4c7-49fb-802f-345f94fe3e91)


### Training Results

![churnre](https://github.com/Toeyeses/Bank_ChurnPredict-Profile/assets/128026055/aeb9ba43-53f4-4ca4-80be-43e56dee6092)

- Emphasis on variable importance.

![churnre1](https://github.com/Toeyeses/Bank_ChurnPredict-Profile/assets/128026055/8b43b586-fbef-4257-a64d-51de8792a708)

- Confusion & cost metrics, lift chart.

![churnre2](https://github.com/Toeyeses/Bank_ChurnPredict-Profile/assets/128026055/d0de47dc-d006-4268-aa5b-432699ebd1fb)

- Training dataset prediction accuracy: 74.4%.

## Part 3: Customer & Churner Profile
- Customer Profile
  
![Bank_Churn_Prediction_Profiling_Presentation](https://github.com/Toeyeses/Bank_ChurnPredict-Profile/assets/128026055/7bbed546-2621-41cb-a8e0-8806b18f2ea7)

- Churner Profile

![Bank_Churn_Prediction_Profiling_Presentation (1)](https://github.com/Toeyeses/Bank_ChurnPredict-Profile/assets/128026055/57bd0e3e-5508-4f94-a6b2-dc7f457545f2)


## Part 5: Business Impact

### Impact Analyses
1. Upsell/cross-sell strategies for Basic Account Holders to convert them into Active Savers.
2. Retention program implementation for High-Value Customers and Basic Account Holders.
3. Cost-saving and reduced opportunity loss via churn prediction ML models.

## Conclusion

The presentation effectively details the processes of data preparation, segmentation, churn prediction, customer profiling, and the resulting business impacts. It emphasizes the significance of identifying high-churn customer segments and strategies for improving customer retention and reducing churn-related costs.
