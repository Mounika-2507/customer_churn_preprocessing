# customer_churn_preprocessing
# Customer Churn Data Preprocessing Pipeline

## Project Overview

This project focuses on preparing a customer churn dataset for machine learning applications. The preprocessing pipeline includes data inspection, data quality checks, categorical variable encoding, feature scaling, and train-test splitting.

The objective is to transform raw customer data into a machine-learning-ready format that can be used for predictive modeling.

## Dataset Features

* CustomerID
* Age
* Gender
* Tenure
* Usage Frequency
* Support Calls
* Payment Delay
* Total Spend
* Last Interaction
* Churn
* Subscription Type
* Contract Length

## Preprocessing Steps

### 1. Data Inspection

* Loaded dataset using Pandas
* Examined dataset structure and data types
* Generated summary statistics

### 2. Data Quality Assessment

* Checked for missing values
* Checked for duplicate records
* Verified dataset consistency

### 3. Categorical Encoding

* Converted categorical variables into numerical representations
* Applied Label Encoding and One-Hot Encoding where appropriate

### 4. Feature Scaling

* Standardized numerical features using StandardScaler
* Ensured all numerical variables were on a comparable scale

### 5. Feature Selection

* Removed CustomerID as it does not contribute to prediction
* Selected relevant features for model training

### 6. Train-Test Split

* Split data into training and testing sets using an 80:20 ratio

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Jupyter Notebook

## Project Structure

customer-churn-preprocessing/

├── customer_churn_preprocessing.ipynb

├── README.md

├── requirements.txt

└── data/

## Learning Outcomes

Through this project, I learned:

* Data preprocessing techniques
* Handling categorical variables
* Feature scaling and normalization
* Preparing datasets for machine learning
* Building reproducible data science workflows

## Future Improvements

* Feature engineering
* Handling class imbalance
* Machine learning model development
* Customer churn prediction using classification algorithms
