# Churn Prediction for StreamWorks Media

## Overview

This project focuses on predicting customer churn for StreamWorks Media, a UK-based video streaming platform. By analysing user data, the goal is to identify factors contributing to churn and develop a predictive model to proactively retain customers.

## Business Scenario

StreamWorks Media faces increasing customer acquisition costs and competition. Understanding and predicting customer churn is crucial for implementing effective retention strategies.  This project aims to provide actionable insights to reduce churn and improve customer loyalty.

## Project Goals

*   Analyse Churn Behavior:** Identify key drivers of customer churn.
*   Predict Future Churners:** Build a model to predict which users are likely to cancel their subscriptions.

## Dataset

The project uses the `streamworks_user_data.csv` dataset, where each row represents a unique subscriber with the following columns:

 user_id -	Unique user identifier 
age -	Age of the user 
gender 	- Male, Female, Other 
signup_date  -	Date user joined 
last_active_date  -	Date of last login 
country - User's country 
subscription_type -	Basic, Standard, Premium 
monthly_fee  -	Amount paid monthly (£) 
average_watch_hours  -	Avg. monthly watch time 
mobile_app_usage_pct -	% of viewing via mobile app 
complaints_raised  -	No. of complaints submitted 
received_promotions -	Whether user received offers (Yes/No) 
referred_by_friend  -	Yes/No 
is_churned  1 if user cancelled in past 30 days, else 0 
 
 
 
## Deliverables

1.  **Jupyter Notebook (.ipynb):** A well-organised notebook containing:
    *   Data loading and exploration
    *   Data cleaning and preprocessing
    *   Feature engineering
    *   Summary tables and visualisations
    *   Statistical analysis
    *   Predictive modeling
    *   Explanations and insights in markdown
2.  **PDF Report (max 1500 words):** A professional summary including:
    *   Key insights
    *   Tables and charts
    *   Answers to business questions
    *   Clear recommendations

## Tasks

1.  **Load & Explore the Data:**
    *   Use pandas to load the dataset
    *   Use `.info()`, `.describe()`, `.value_counts()`, `.isnull().sum()` to understand structure and missing values
    *   Create a correlation matrix and heatmap for numeric variables
2.  **Clean & Prepare the Data:**
    *   Convert `signup_date`, `last_active_date` to datetime
    *   Create new features:
        *   `tenure_days` = days between signup and last\\_active\\_date
        *   `is_loyal` = tenure\\_days > 180
    *   Encode categorical features (e.g., LabelEncoder, `pd.get_dummies`)
    *   Handle missing values
3.  **Statistical Analysis & Insights:**
    *   Use Chi-square test to check if churn is related to `gender`, `received_promotions`, or `referred_by_friend`
    *   Use a t-test to check if watch time differs significantly between churned and retained users
    *   Use charts (boxplots, bar plots, histograms) to visualize key differences between churned and active users
4.  **Predictive Modelling:**
    *   Build a logistic regression model to predict `is_churned`:
        *   Split into training and test sets
        *   Scale features (StandardScaler)
        *   Fit a LogisticRegression() model
        *   Predict probabilities and classes
        *   Evaluate the model using:
            *   Confusion Matrix
            *   Precision, Recall, F1 Score
            *   ROC Curve and AUC Score
        *   Identify the most important predictors of churn

## Business Questions to Answer

1.  Do users who receive promotions churn less?
2.  Does watch time impact churn likelihood?
3.  Are mobile-dominant users more likely to cancel?
4.  What are the top 3 features influencing churn based on your model?
5.  Which customer segments should the retention team prioritise?

## Report Structure

The PDF report should include the following sections:

1.  **Introduction:** Business goal and dataset description.
2.  **Data Cleaning Summary:** Changes made to the data.
3.  **Feature Engineering Summary:** Explanation of new features created.
4.  **Key Findings:** Statistical findings and correlations.
5.  **Model Results:** Model performance, ROC curve, and top predictors of churn.
6.  **Business Questions Answered:** Answers to the business questions with evidence.
7.  **Recommendations:** Actionable strategies for StreamWorks Media.
8.  **Data Issues or Risks:** Limitations or risks identified.


