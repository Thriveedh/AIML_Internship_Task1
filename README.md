# AIML_Internship_Task1
# Titanic Dataset - Data Preprocessing and Cleaning

This task showcases the preprocessing steps applied to the **Titanic dataset**, including handling missing values, encoding categorical variables, standardization, and outlier removal.

##  Steps Performed

### 1. Import the Dataset and Explore Basic Info
- Loaded the dataset using pandas.
- Checked for null values, data types, and overall structure using functions like info(), describe(), and head().

### 2. Handle Missing Values
- Dropped the 'Cabin' column as it contained too many missing values.
- Filled missing values in the 'Age' column with the mean of the column.
- Replaced missing values in the 'Embarked' column with the most frequent value (mode).

### 3. Encode Categorical Variables
- Applied one-hot encoding to convert categorical columns like 'Sex' and 'Embarked' into numerical columns.

### 4. Standardize Numerical Features
- Standardized the 'Age' and 'Fare' columns so that they have a mean of 0 and standard deviation of 1.
- This was done to bring all numerical features to the same scale, which is important for many machine learning algorithms.

### 5. Remove Outliers
- Identified outliers visually using boxplots.
- Removed outliers from the numerical columns using the Interquartile Range (IQR) method.

##  Outcome
- A cleaned and preprocessed version of the Titanic dataset, ready for machine learning model building or further analysis.
