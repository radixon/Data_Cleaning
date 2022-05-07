# Data Cleaning

Data cleaning is part of the Data Exploration & Preprocessing stage of the Workflow.  This is where we create data that a model can use.

## Import the Required Libraries
**Pandas** manages the data <br>
**NumPy** mathematical operations <br>
**Seaborn** visualizations <br>
**sklearn** machine learning related functions <br>
**SciPy** statistical computations <br>

## Read/Understand the Data
__info()__ method <br>
__describe()__ method <br>
__value_counts()__method <br>

## Look for Correlations
__corr()__ function for numerical values <br>
__pairplot()__ function for visualization <br>

## Check for Skewness
__skew()__ function for numerical value <br>
__distplot()__ function for visualization <br>

## Log Transformation
Transformation as required by results of Skewness <br>

## Duplicate Handling
__duplicated()__ function to check for duplicates <br>
__drop_duplicates()__ function removes duplicates <br>

## Missing Value Handling[^1]
__isnull().sum()__ counts total number of missing values <br>
__dropna()__ method drops missing values <br>

## Feature Scaling

## Outlier Handling








[^1] Data Imputation is an option if you can determine if missing data is missing completely at random (MCAR) or missing at random (MAR).
