# DATA-PREPROCESSING-OF-STUDENT-DATASET
Machine learning data preprocessing project featuring dataset exploration, missing value treatment, categorical encoding, and model-ready train-test split.

Objective
The objective of this project is to perform end-to-end data preprocessing on a student dataset using Google Colab. The dataset is explored, cleaned, and transformed into a machine-learning-ready format by handling missing values and encoding categorical variables.

Project Overview
Raw datasets often contain missing values and categorical features that cannot be directly used in machine learning models. This project demonstrates essential preprocessing techniques using Python libraries such as Pandas and Scikit-learn.

Tasks Performed


Loaded the CSV dataset using Pandas.
Displayed the first 5 rows and last 5 rows.
Examined:Dataset shape,Column names,Data types
Identified:Numerical columns and Categorical columns
Generated statistical summaries using describe()

 Identify Missing Values
Used isnull().sum() to detect missing values
Identified columns containing missing data

 Handle Missing Values
Numerical Columns
Missing values were replaced with the mean value for:
Age
Hours_Studied
Attendance
Final_Score
Categorical Columns

Missing values were replaced with the mode value for:
Gender
Parental_Education
Verification was performed to ensure that no missing values remained

Encoded Categorical Variables
Applied Label Encoding to the Gender column
Applied One-Hot Encoding to the Parental_Education column
Removed original categorical columns
Verified that the final dataset contained only numerical values

Prepared Data for Machine Learning
Separated:
Features (X)
Target variable (y = Final_Score)
Split the dataset into:
Training set (80%)
Testing set (20%)
Used a fixed random state for reproducibility

Technologies Used:
Python
Google Colab
Pandas
NumPy
Scikit-learn


Workflow
Dataset Exploration
Missing Value Detection
Missing Value Handling
Label Encoding
One-Hot Encoding
Feature and Target Separation
Train-Test Splitting

Required Libraries
Install the required libraries using:
pip install pandas numpy scikit-learn

Output

After preprocessing:
All missing values are removed.
Categorical variables are converted into numerical form
The dataset becomes suitable for machine learning models
Training and testing datasets are generated successfully

Through this project, the following concepts were practiced:

Data exploration using Pandas
Handling missing values with fillna()
Mean and mode imputation
Label Encoding
One-Hot Encoding
Feature-target separation
Train-test splitting using Scikit-learn
Preparing datasets for machine learning

Author

YUKTHA B RAMJI

Project completed as part of DP: TASK-01 – Data Preprocessing of Student Dataset using Google Colab.
    
