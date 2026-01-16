# AI-ML-Internship-Task2
Task 2: Data Cleaning & Missing Value Handling
OVERVIEW

This project focuses on identifying and resolving missing data within a housing dataset to ensure high data quality for machine learning models. The task involves loading data, visualizing missingness, and applying statistical imputation techniques.

TOOLS USED

Language: Python 
Libraries: Pandas, NumPy (Data Manipulation), Matplotlib (Visualization)

STEPS FOLLOWED

Data Loading: Successfully loaded the House Prices dataset into a Pandas DataFrame.
Missing Value Identification: Used .isnull().sum() to audit the dataset for empty cells
Visualization: Created a bar chart to visualize missing data patterns, making gaps easy to identify at a glance.
Imputation Strategy:
Numerical Columns: Applied Median Imputation to handle skewed data and outliers.
Categorical Columns: Applied Mode Imputation for text-based columns.
Validation: Performed a final check to ensure zero missing values remained, guaranteeing 100% data completeness

### Data Cleaning Results
| Feature | Before Cleaning | After Cleaning |
| :--- | :---: | :---: |
| Missing Values (Count) | 303 | 0 |
| Data Completeness | ~98% | 100% |
| Dataset Integrity | Gaps Found | Clean & Validated |

KEY LEARNINGS

Learned when to use Mean vs. Median based on data distribution.
Understood the danger of Data Leakage and how it affects model performance.
Gained hands-on experience in ensuring Data Quality (Accuracy, Completeness, and Consistency).
