# PREDICTION_OF_HOTEL_BOOKING_CANCELLATION

## Project Overview
This project focuses on predicting hotel booking cancellations using supervised machine learning (Classification).

### Problem Statement
Unexpected hotel cancellations have led to a significant revenue loss for the hotel. The objective is to predict which customers are likely to cancel their bookings, allowing the hotel to implement proactive strategies such as incentives and special reminders to reduce cancellations and ultimately increase revenue.

### Objective
The primary objective is to develop a model that accurately predicts hotel booking cancellations. This prediction will provide valuable insights for the company, enabling them to allocate resources effectively and reduce the number of cancellations, thereby increasing revenue.

## Project Steps and Processes

### Data Understanding & Data Preprocessing
- **Dataset Information**: 
  - Contains 83,293 rows and 33 columns.
- **Data Cleaning**:
  - Handling missing values and duplicates.
  - Converting incorrect data types.

### Exploratory Data Analysis
- **Outlier Handling**.
- **Exploratory Analysis**:
  - Analyzing both categorical and numerical data.

### Modelling
Six classification models were used, and performance evaluations were conducted to determine the best model:
  - Logistic Regression
  - K-Nearest Neighbors (KNN)
  - Decision Tree
  - Random Forest
  - LGBM (Light Gradient Boosting Machine)
  - XGBoost

### Evaluation
- **Best Model for Prediction**: 
  - **Random Forest Classifier**:
    - **F1 Score**: 0.7979
    - **Recall Score**: 0.8218
  - **Best Parameters for Random Forest**: 
    - `max_depth`: 50
    - `min_samples_split`: 2
    - `n_estimators`: 300
  - **False Negative Rate (FNR)**: 0.1781

### Business Recommendations
- **Manage Peak Season Reservations**:
  - Focus on prospective customers likely to cancel.
- **Implement a Deposit System**:
  - Require upfront payments for early bookings to minimize cancellations.
- **Stricter Cancellation Policies**:
  - Differentiate policies between regular and high seasons, including down payments and partial refunds during regular seasons and no charge during high seasons due to high demand.
- **Adjust Room Category Pricing**:
  - Reduce the price gap between lower and higher room categories to encourage upgrades.
- **Create a Membership System**:
  - Implement a points-based membership system to encourage repeat bookings.
- **Provide Reminders**:
  - Send reminders to customers as their arrival date approaches.
- **Collect Customer Feedback**:
  - Conduct surveys for guests to gather feedback and improve services, promoting repeat bookings.

These steps and recommendations aim to mitigate booking cancellations and enhance revenue by improving the overall customer experience and operational efficiency.
