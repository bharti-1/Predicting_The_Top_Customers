# Predicting The Top Customers 
![Predicting The Top Cusomers](https://github.com/bharti-1/Predicting_The_Top_Customers/blob/main/target.jpeg)

# Term Deposit Subscription Prediction Dataset

**Dataset Source:** [https://www.kaggle.com/datasets/sharanmk/bank-marketing-term-deposit]

**Description:**
This dataset contains information about customers and their interactions with a bank. It includes features like customer age, job type, marital status, education level, account balance, loan status, communication type, and more.

**Dataset Size:**
- Number of Records: 23,880
- Number of Features: 17

**Missing Data:**
Implemented data cleaning techniques, including capping and flooring to remove outliers, and mean ,median
and mode imputation to fill missing values, ensuring dataset integrity for accurate analysis and modeling.

**Target Variable:**
The target variable in this dataset is "term_deposit_subscribed," which indicates whether a customer subscribed to a term deposit (binary classification).

**Data Exploration:**
During exploratory data analysis (EDA), several insights were discovered, such as the influence of job type, marital status, education level, and communication type on subscription rates.

**Data Preprocessing:**
Categorical variables were one-hot encoded, and numerical features were standardized. Outliers were also addressed.

**Modeling:**
Three machine learning models—Logistic Regression, Random Forest, and Decision Tree—were employed for predicting term deposit subscriptions. Class imbalance was handled using Synthetic Minority Oversampling Technique (SMOTE).

**Model Evaluation:**
The models were evaluated based on accuracy, precision, recall, F1-score, and ROC-AUC. 

**Future Steps:**
Potential improvements include hyperparameter tuning, feature engineering, and deeper analysis of misclassified instances.













