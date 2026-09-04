# Delivery Delay Risk Prediction using Logistic Regression

## Project Overview
This project predicts the risk of delivery delays using Machine Learning. Logistic Regression is used as the classification algorithm to determine whether an order is likely to be delivered on time or delayed.

## Objective
The main objective of this project is to build a machine learning model that predicts delivery delay risk based on different operational factors.

## Dataset
The dataset contains 1000 records and 7 columns.

### Features
- distance_km – Distance of delivery in kilometers
- warehouse_load – Current warehouse workload
- order_hour – Hour at which the order was placed
- items_count – Number of items in the order
- weather_risk – Weather-related risk factor
- carrier_delay_rate – Carrier delay rate

### Target
- 0 – On Time
- 1 – Delayed

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Machine Learning Model
Logistic Regression was used as the classification algorithm.

## Project Workflow
1. Import required libraries
2. Load the dataset
3. Perform data exploration
4. Check missing values and duplicates
5. Perform Exploratory Data Analysis
6. Analyze feature correlations
7. Split the dataset into training and testing sets
8. Scale the features
9. Train the Logistic Regression model
10. Evaluate model performance
11. Generate predictions

## Model Performance

| Metric | Score |
|--------|-------|
| Accuracy | 0.6250 |
| Precision | 0.6126 |
| Recall | 0.6800 |
| F1-Score | 0.6445 |
| ROC-AUC | 0.7146 |

## Confusion Matrix
- True Negative: 57
- False Positive: 43
- False Negative: 32
- True Positive: 68

## Key Findings
- Carrier delay rate has the strongest positive influence on delivery delay risk.
- Warehouse load and items count also positively influence delay risk.
- The model achieved an ROC-AUC score of approximately 0.71.

## Conclusion
The Logistic Regression model was successfully developed to predict delivery delay risk. The model provides useful insights into factors influencing delivery delays.

## Author
Karthick Raja S
