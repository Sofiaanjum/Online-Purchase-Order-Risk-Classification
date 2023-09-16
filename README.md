# Online Purchase Order Risk Classification

**Repository:** [https://github.com/Sofiaanjum/AIGC5005_MidtermProject]

## Project Description

This repository contains the code and steps for the "Online Purchase Order Risk Classification" project for the AIGC 5005 course.

The project aims to classify online purchase orders into different risk categories. It involves data exploration, preprocessing, building and evaluating machine learning models, and generating predictions for test data.

## Steps

### 1. Import Libraries

In this step, we import the necessary Python libraries required for data analysis and machine learning.

### 2. Explore and Clean Dataset

Explore the dataset to understand its structure, columns, and characteristics. This step may involve checking for missing data, outliers, and data quality issues.

### 3. Identify Null Values

Identify columns with missing values (null values) in the dataset.

### 4. Delete Columns with More than 50% Null Data

Columns with a high percentage of missing data (more than 50%) are deleted as they may not provide meaningful information.

### 5. Impute Data for Columns with Less than 50% Missing Data

For columns with less than 50% missing data, we impute the missing values using appropriate techniques.

### 6. Reduce the Null Values to 0

After imputation, we aim to reduce the null values in the dataset to zero.

### 7. Convert Text Labels to Numerical Labels

Machine learning models require numerical inputs, so we convert text labels into numerical labels for classification.

### 8. Build Your Data Model

In this step, we prepare the data for modeling, including feature selection and engineering if necessary.

### 9. Scale the Datapoints

Scaling is important to ensure that features are on a similar scale, which can improve the performance of some machine learning algorithms.

### 10. Split the Data into X and y

We split the data into input features (X) and the target variable (y) to train the machine learning models.

### 11. Split the Data into Train & Test

The dataset is split into training and testing sets to train and evaluate the models.

### 12. Implement Different Models

We implement different machine learning models, such as Support Vector Machine (SVM), Random Forest Classifier, and Logistic Regression, to classify purchase orders into risk categories.

### 13. Evaluate Different Metrics

We evaluate the models using various metrics to assess their performance, including accuracy, precision, recall, and F1-score.

### 14. Apply the Best Model to the Test Dataset

The best-performing model is applied to the test dataset to generate predictions. The results are saved as a .csv file for further analysis.

## Getting Started

To run the code and follow the project, open the `code.ipynb` Jupyter Notebook file.

## Dependencies

Ensure you have the required Python libraries installed by referring to the list of libraries in the code.

## Author

[Sofiaanjum Ahmed]

Feel free to reach out if you have any questions or need further assistance.


