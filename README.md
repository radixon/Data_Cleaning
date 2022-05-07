# Data Cleaning

Data cleaning is part of the Data Exploration & Preprocessing stage of the Workflow.  This is where we create data that a model can use.

## Import the Required Libraries
**Pandas** manages the data
**NumPy** mathematical operations
**Seaborn** visualizations
**sklearn** machine learning related functions
**SciPy** statistical computations

## Read/Understand the Data
__info()__ method
__describe()__ method
__value_counts()__method

## Look for Correlations
__corr()__ function for numerical values
__pairplot()__ function for visualization

## Check for Skewness
__skew()__ function for numerical value
__distplot()__ function for visualization

## Log Transformation
Transformation as required by results of Skewness

## Duplicate Handling
__duplicated()__ function to check for duplicates
__drop_duplicates()__ function removes duplicates

## Missing Value Handling[^1]
__isnull().sum()__ counts total number of missing values
__dropna()__ method drops missing values

## Feature Scaling

## Outlier Handling








[^1] Data Imputation is an option if you can determine if missing data is missing completely at random (MCAR) or missing at random (MAR).
