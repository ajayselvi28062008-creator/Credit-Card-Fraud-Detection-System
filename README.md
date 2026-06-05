# Credit Card Fraud Detection System

## Problem Statement

Financial institutions process millions of credit card transactions daily, where some transactions are fraudulent and unauthorized. Manual fraud detection is difficult due to the large volume of data and fast transaction processing. Incorrect fraud detection can lead to financial losses, unauthorized transactions, and reduced customer trust.
This project focuses on analyzing transaction data using Exploratory Data Analysis (EDA), Linear Regression, and Data Visualization to identify fraud patterns and support fraud detection.

## Dataset

* **Source:** Kaggle

* **Dataset Name:** Credit Card Fraud Detection Dataset

### Selected Columns

* Time → Time elapsed between transactions
* Amount → Transaction amount
* V1 – V28 → Anonymized features
* Class → Target column
* 0 = Normal
* 1 = Fraud

## Objectives
* Perform Data Cleaning & Preprocessing
* Analyze fraud and normal transactions
* Perform Descriptive Statistics
* Identify fraud patterns
* Create Data Visualizations
* Build a Linear Regression Model
* Evaluate model performance using R² Score
* Understand transaction behavior and fraud risk
  
## Technologies Used
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Project Workflow
1. Data Collection
2. Data Cleaning
3. Descriptive Statistics
4. Fraud Behavior Analysis
5. Correlation Analysis
6. Data Visualization
7. Risk Analysis
8. Linear Regression Modeling
9. Model Evaluation
10. Insights & Conclusion
    
## Visualizations

### Fraud Distribution
2<img width="732" height="562" alt="Screenshot (504)" src="https://github.com/user-attachments/assets/0449eb01-ce94-45e6-b910-193a48b30ca4" />

### Transaction Amount 
<img width="713" height="541" alt="Screenshot (505)" src="https://github.com/user-attachments/assets/98e63d33-eb95-4bc2-aaf8-ffd1e5cf28fc" />

### Correlation Heatmap
<img width="908" height="637" alt="Screenshot (506)" src="https://github.com/user-attachments/assets/da8f5083-b72b-4fd1-b9a6-37608cb66c86" />

## Model Used
**Linear Regression**
* Independent Variables: Time, Amount
* Dependent Variable: Fraud Class
  
**Evaluation Metric**
* R² Score
  
## Conclusion

This project helps analyze transaction behavior and identify suspicious patterns in credit card transactions. The visualizations and predictive modeling support better fraud detection and risk management.




