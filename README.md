# Project Title : Predicting Personal Loan Acceptance using Logistic Regression and Neural Networks

## Objective
To develop predictive models using Logistic Regression and Neural Networks to identify customers likely to accept personal loan offers. The project aims to enhance marketing efficiency, optimize resource allocation, and increase customer conversion rates.

## Tools and Technologies Used
Programming Language: Python
Libraries:
Pandas and Numpy for data manipulation.
Scikit-learn for Logistic Regression and evaluation metrics.
TensorFlow/Keras for Neural Network modeling.
Matplotlib and Seaborn for visualization.

## Dataset Details
File Name: bank.xlsx
Content: Customer demographic and financial data, including features like income, education, age, family size, and banking service usage.

## Key Features:
Demographics: Age, Income, Education, Family Size.
Banking Services: Mortgage value, CD account, Online banking usage, Credit card ownership.

## Models Used
Logistic Regression

Thresholds Tested:
Threshold = 0.5
Threshold = 0.1
Performance Metrics:
At Threshold = 0.5:
Sensitivity (Recall): 66%
Accuracy: 95%
Specificity: 99%
At Threshold = 0.1:
Sensitivity: 83%
Accuracy: 91%
Specificity: 92%
Neural Network

Hyperparameters:
Learning Rate: 0.3
Performance Metrics:
Accuracy: 97%
Sensitivity: 81%
Specificity: 99%

## Key Insights
Logistic Regression with a lower threshold (0.1) improves recall but slightly reduces accuracy compared to the default threshold.
The Neural Network model outperforms Logistic Regression in overall accuracy (97%) and specificity (99%), making it the best choice for predicting loan acceptance.
## Recommendations
Implement the Neural Network model for loan prediction as it provides the best results.
Use the Logistic Regression model with a threshold of 0.1 for quick and interpretable predictions when computational resources are limited.
Leverage demographic and banking service usage data to tailor marketing strategies and campaigns for high-conversion customer segments.


## Business Implications
Enhanced Targeting: Accurate prediction models allow personalized marketing to high-probability customers.
Increased Profitability: Optimized resource allocation ensures higher conversion rates and reduced marketing costs.
Customer Satisfaction: Tailored loan offers improve customer experience and loyalty.
## Future Work
Test additional machine learning models (e.g., Random Forest, Gradient Boosting) for comparative analysis.
Explore feature engineering techniques to include interaction terms and derived features.
Evaluate the model's robustness on new, unseen data.

