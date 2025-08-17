1. Introduction:
Business Goal: StreamWorks Media wants to reduce customer churn (customers leaving) because it's getting more expensive to attract new subscribers. This report helps them understand why customers leave and predict who is likely to leave next.

The analysis for this report is based on a dataset of 1,500 StreamWorks users with 14 columns of data, including demographics, subscription details, and engagement. Some data is missing and must be addressed before further analysis.

2. Data Cleaning Summary:
To ensure accuracy, the report notes the removal of duplicate records, converting data columns to the correct date format, and removing columns with less than 5% of missing data. These steps lay the foundation for effective feature engineering.

3. Feature Engineering Summary:
Two new features were created. ‘Tenure_days’, which calculates how long each user has been a customer, to show the customer life span. ‘is_loyal’, which determines if a user has been using StreamWorks for a long period.

4. Key Findings:
There’s no strong direct relationship (correlation) between individual user characteristics (like age or gender) and churn.
Customer demographics or engagement metrics are not strongly predictive of customer churn

5. Model Results:
Model Performance: The model can identify which customers are likely to churn with low precision, which results in an overall F1 score that is considered below moderate.
ROC Curve: The ROC curve analysis indicates that the model's performance needs improvement.
Top Predictors of Churn: The factors that most influence whether a customer churns are:
Whether they've received promotions (receiving them reduces churn).
Whether they are loyal customer.
Average watch hours (higher watch hours decrease churn).

6. Business Questions Answered:
Do users who receive promotions churn less?
Yes. Those who receive promotions have a lower churn rate (21.19%) compared to those who don't (24.80%).

Does watch time impact churn likelihood?
No, we can't prove or disprove.

7. Recommendations:
Focus on Promotions and Loyalty: StreamWorks should prioritise promotions and loyalty programs as key retention strategies.
Prioritise Retention Efforts: Target retention efforts towards less loyal, less engaged, and unpromoted customers, especially those with lower watch hours.

8. Data Issues or Risks:

The model used is not very accurate and needs to be improved with better quality data or different analysis techniques.
The data has limits, so the recommendations should be tested and refined over time.
