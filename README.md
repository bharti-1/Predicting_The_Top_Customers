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
Missing data in this dataset was handled through imputation. This dataset contained missing values in several columns. To ensure data completeness and to avoid potential bias in the analysis, the following imputation strategy was applied:
Customer Age: Missing values in the "customer_age" column were imputed using the mean age of the dataset. This approach ensures that the missing values are replaced with a representative value that does not significantly impact the overall distribution.
Marital Status: Missing values in the "marital" column were imputed with the mode (most frequent marital status) of the dataset. Since marital status is a categorical variable, this approach preserves the distribution of marital statuses.
Balance: Missing values in the "balance" column were imputed using the median balance of the dataset. Median imputation is robust to outliers and helps maintain the integrity of the balance distribution.
Personal Loan: Missing values in the "personal_loan" column were imputed with "no." This decision was made based on the assumption that customers with missing values did not have a personal loan, which aligns with the majority of the data.
Communication Type:Missing values in the "communication_type" column were imputed with "unknown." This choice was made since there was no specific information available for these cases.
Num Contacts in Campaign:Missing values in the "num_contacts_in_campaign" column were imputed using the median number of contacts in the campaign. This imputation method ensures that the missing values are replaced with a typical value for this feature.

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













