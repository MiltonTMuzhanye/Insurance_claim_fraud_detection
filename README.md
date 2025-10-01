Insurance Claim Fraud Detection
Project overview
This project detects fraudulent insurance claims using machine learning. It helps insurance companies save money by identifying suspicious claims before payment.

Business Problem
Insurance companies lose billions to fraud each year. This system helps:
Reduce financial losses from fake claims
Speed up processing for honest customers
Automate fraud detection
Provide explanations for flagged claims

Dataset
We use insurance claims data with:
15,420 claims
32 features including:
Claim details (amount, type, date)
Customer information (age, marital status)
Vehicle information
Policy details
Historical data

Fraud Rate: 6% (923 fraudulent claims out of 15,420)

What This Project Does
1 Data Preparation
Encodes categorical variables (like car make, accident area)
Handles missing values
Creates new features for better detection

2 Data Analysis
Shows fraud distribution (6% of claims are fraudulent)
Identifies features most related to fraud
Analyzes patterns in fraudulent claims

3 Fraud Detection Models
We test three machine learning models:

Logistic Regression - Simple but interpretable
Accuracy: 81.1%
Recall: 46.0% (catches 46% of fraud)

Random Forest - Handles complex patterns
Accuracy: 91.2%
Recall: 14.6% (misses too much fraud)

XGBoost - Advanced gradient boosting Best Model
Accuracy: 94.8%
Recall: 48.6% (catches nearly half of fraud)
Precision: 58.4% (low false alarms)

4 Model Performance
Model	  Accuracy	Precision	Recall	F1-Score
Logistic Regression	81.1%	15.0%	46.0%	22.6%
Random Forest	91.2%	19.3%	14.6%	16.6%
XGBoost	94.8%	58.4%	48.6%	53.1%

Key Results
Best Model: XGBoost
Catches 49% of fraudulent claims
58% of flagged claims are actually fraudulent
95% overall accuracy

Business Impact
XGBoost identifies 90 out of 185 fraud cases in test data
Low false positive rate - doesn't bother honest customers
Explanations available for why claims are flagged
