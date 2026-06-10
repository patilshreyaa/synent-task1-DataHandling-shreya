# Problem Statement

The raw Titanic dataset contained missing values, inconsistent formats, redundant features, and unstructured text fields that could affect the accuracy and reliability of further analysis. The objective of this task was to clean and preprocess the dataset, handle missing values, standardize features, and prepare the data for exploratory data analysis (EDA) and machine learning.

# Data Cleaning Steps Performed
1) Inspected dataset structure, data types, duplicate records and missing values.
2) Removed unnecessary columns with excessive missing values (e.g., Cabin).
3) Handled missing values in relevant features.
4) Explored the Duplicate data
5) Extracted passenger titles from the Name column.
6) Standardized and grouped title categories.
7) Cleaned text-based columns by removing unwanted characters and spaces.
8) Dropped redundant columns after feature extraction.
9) Verified data quality and ensured consistency across features.
10) Prepared the final dataset for downstream analysis and modeling.
# Key Insights from Data Quality Assessment
1) Missing Values : 
The Cabin feature contained approximately 78% missing values, making it unsuitable for reliable analysis and therefore removed.
Other missing values were identified and handled appropriately to maintain data integrity.


2) Feature Engineering Opportunities : 
The Name column contained useful information such as passenger titles (Mr, Mrs, Miss, etc.), which were extracted into a separate feature.
Grouping similar titles reduced category complexity and improved consistency.


3) Data Consistency :
Text fields required standardization to eliminate formatting inconsistencies.
Unnecessary symbols, extra spaces, and inconsistent naming patterns were cleaned.


4) Dataset Readiness
The final dataset contained cleaner, more structured features.
Missing value issues were minimized.
Features were standardized and suitable for visualization, statistical analysis, and predictive modeling.


# Outcome

Successfully transformed the raw Titanic dataset into a clean, structured, and analysis-ready dataset by handling missing values, removing redundant information, standardizing features, and performing basic feature engineering.
