# Census Income Prediction Project Report

## 1. Introduction

This report outlines a project focused on analyzing and predicting income levels using the Census Income dataset. The dataset contains various demographic and socioeconomic features, and the goal is to develop a model that can accurately predict whether an individual's income exceeds $50K per year. This project utilizes Python, Pandas, Seaborn, and Matplotlib for data manipulation, exploration, and visualization.

## 2. Objectives

The primary objectives of this project were:

* To load and preprocess the Census Income dataset.
* To explore and understand the dataset's structure and content.
* To perform data cleaning, including renaming columns.
* To visualize key features and their relationships.
* To prepare the data for predictive modeling.

## 3. Methodology

The project followed these steps:

1.  **Data Loading and Initial Inspection:**
    * Imported necessary Python libraries: Pandas, NumPy, Matplotlib, and Seaborn.
    * Loaded the "census-income.csv" dataset into a Pandas DataFrame, skipping initial spaces in the data.
    * Used the `head()` method to view the first few rows of the DataFrame, gaining an initial understanding of the data's structure.

2.  **Data Cleaning:**
    * Identified the column "Unnamed: 14" as the target variable representing income levels.
    * Used the `unique()` method to confirm the unique values in the target column ('<=50K', '>50K').
    * Renamed the column "Unnamed: 14" to "income" for clarity using the `rename()` method.
    * Viewed the head of the dataframe again to confirm the column name change.

3.  **Data Exploration:**
    * The head of the dataframe was displayed to give an overview of the data.

## 4. Dataset Description

The "census-income.csv" dataset contains the following columns:

* **age:** Age of the individual.
* **workclass:** Type of employment.
* **fnlwgt:** Final weight, a statistical measure.
* **education:** Highest level of education achieved.
* **education-num:** Numerical representation of education level.
* **marital-status:** Marital status of the individual.
* **occupation:** Occupation of the individual.
* **relationship:** Relationship status.
* **race:** Race of the individual.
* **sex:** Gender of the individual.
* **capital-gain:** Capital gains.
* **capital-loss:** Capital losses.
* **hours-per-week:** Number of hours worked per week.
* **native-country:** Native country of the individual.
* **income:** Income level (<=50K or >50K).

The dataset contains 32561 rows and 15 columns.

## 5. Results and Observations

* The dataset was successfully loaded and cleaned.
* The target variable "income" was identified and renamed.
* The initial inspection of the data revealed the presence of categorical and numerical features.
* The output of the head method displays the data, and shows the renamed column.
* The intrinsic json of the dataframe shows the data types, and sample data of each column.

## 6. Conclusion

This project successfully completed the initial steps of data loading, cleaning, and exploration. The dataset is now prepared for further analysis, including feature engineering, visualization, and predictive modeling.

## 7. Future Work

Future work on this project could include:

* Handling missing values and inconsistencies in the data.
* Performing exploratory data analysis (EDA) to visualize relationships between features and the target variable.
* Feature engineering to create new relevant features.
* Developing and evaluating predictive models to accurately predict income levels.
* Visualizing the distributions of the data.
* Analyzing the distributions of the data, based on race, and sex.
* Creating a machine learning model to predict income.
