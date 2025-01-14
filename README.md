# Credit Card Attrition Rate Prediction

## Overview

This project aims to predict customer attrition (churn) in the credit card domain using machine learning models. By analyzing customer demographics, transactional behavior, and account details, businesses can identify at-risk customers and take proactive retention measures.

## Key Features

1. **Data Analysis:**
   - Univariate and Bivariate Analysis.
   - Insights on customer age, education, income, and card category trends.
   - Analysis of gender and educational qualifications' influence on attrition rates.

2. **Preprocessing:**
   - Handling missing values and outliers.
   - Encoding categorical variables using Label Encoding.
   - Feature engineering and data transformation.

3. **Model Training:**
   - Logistic Regression.
   - Decision Tree Classifier.
   - Random Forest Classifier.

4. **Evaluation Metrics:**
   - Accuracy score comparisons for the models.
   - Logistic Regression achieved ~85% accuracy.
   - Decision Tree achieved ~93% accuracy.
   - Random Forest demonstrated high accuracy with additional feature handling.

## Dataset

The dataset contains the following attributes:

1. **CLIENTNUM**: Client number (unique identifier for customers).
2. **Attrition_Flag**: Target variable indicating whether the customer is "Existing Customer" or "Attrited Customer".
3. **Customer_Age**: Age of the customer.
4. **Gender**: Gender of the customer.
5. **Dependent_Count**: Number of dependents.
6. **Education_Level**: Highest educational qualification of the customer.
7. **Marital_Status**: Marital status of the customer.
8. **Income_Category**: Annual income category of the customer.
9. **Card_Category**: Type of credit card (e.g., Blue, Silver, Gold, Platinum).
10. **Months_on_Book**: Period of relationship with the bank (in months).
11. **Total_Relationship_Count**: Total number of products held by the customer.
12. **Months_Inactive_12_mon**: Number of months inactive in the last 12 months.
13. **Contacts_Count_12_mon**: Number of contacts in the last 12 months.
14. **Credit_Limit**: Credit limit on the credit card.
15. **Total_Revolving_Bal**: Total revolving balance on the credit card.
16. **Avg_Open_To_Buy**: Average open-to-buy credit line over the last 12 months.
17. **Total_Amt_Chng_Q4_Q1**: Change in transaction amount from Q4 to Q1.
18. **Total_Trans_Amt**: Total transaction amount (last 12 months).
19. **Total_Trans_Ct**: Total transaction count (last 12 months).
20. **Total_Ct_Chng_Q4_Q1**: Change in transaction count from Q4 to Q1.
21. **Avg_Utilization_Ratio**: Average card utilization ratio.

## Results

- **Logistic Regression**: ~85% accuracy.
- **Decision Tree**: ~93% accuracy.
- **Random Forest**: High accuracy with better handling of non-linearity.

## Future Work

- Explore ensemble methods for improved performance.
- Deploy the model for real-time predictions.
- Integrate external datasets for richer insights.
