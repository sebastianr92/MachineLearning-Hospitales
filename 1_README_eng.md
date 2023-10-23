# ML Project: Hospitalization Prediction in Patients Undergoing Prostate Biopsy

This Machine Learning project aims to perform exploratory data analysis (EDA), data preparation and transformation, and the construction and evaluation of Machine Learning models to predict hospitalization in patients undergoing a prostate biopsy. The models used are K-Nearest Neighbors and Decision Trees. In the case of Decision Trees, we seek to determine the optimal value for the depth hyperparameter (K-depth).

## Introduction

The application of Machine Learning in Medicine allows the analysis of clinical data to make predictive diagnoses, assess the effectiveness of intervention strategies, and anticipate complications in medical care. In this project, we focus on identifying the most important characteristics that patients with a specific type of disease have, leading to hospitalization after undergoing a prostate biopsy.

## Problem Statement

Our client needs a better understanding of the factors that influence hospitalization in patients undergoing a prostate biopsy. A case was defined as a patient who experienced fever, urinary tract infection, or sepsis within a maximum of 30 days after the prostate biopsy, requiring outpatient or inpatient medical management to resolve the complication. A control is a patient who did not experience infectious complications during the same period.

The dataset includes information about patient backgrounds, patient-associated morbidities, biopsy-related details, and infectious complications. Due to data quality issues, it is necessary to conduct exploratory analysis and proper data preparation before building prediction models.

## Data Dictionary

Below is a data dictionary with the variables included in the dataset:

![image](https://user-images.githubusercontent.com/118769777/220240501-8c21461d-2de5-495b-954e-10fb9bf38014.png)

## Project Development

The project is divided into three main phases:

### 1. Exploratory Data Analysis (EDA)

In this phase, we conducted exploratory data analysis to understand data quality and obtain valuable insights. We explored variable distributions, identified missing values, and evaluated the relationship between features and hospitalization.

### 2. Data Preparation

Various data cleaning and transformation tasks were performed. We addressed missing values, encoded categorical variables, and selected relevant features for the Machine Learning models.

### 3. Modeling and Evaluation

Two supervised Machine Learning models were built: K-Nearest Neighbors and Decision Trees. In the case of Decision Trees, we explored the search for the optimal depth hyperparameter. The models were evaluated using appropriate metrics to determine which one provides the best performance in predicting patient hospitalization. This selection was based on the results analysis and consideration of the specific healthcare problem at hand.

## Machine Learning Models

To address the prediction of hospitalization in patients undergoing a prostate biopsy, we implemented two supervised Machine Learning models: K-Nearest Neighbors and Decision Trees.

1. **K-Nearest Neighbors (K-NN)**: The K-NN model is based on the idea that patients with similar characteristics exhibit similar hospitalization behavior. This nearest neighbors approach uses the distance between data points to classify new patients based on the majority of the K nearest neighbors. The choice of K, the number of neighbors considered, is a critical hyperparameter that was explored during the modeling phase.
2. **Decision Trees**: Decision Trees are models that split the dataset into subsets based on decision rules. Each tree node represents a feature and a decision, allowing patients to be classified based on their characteristics. In this project, we sought to find the optimal tree depth, an important hyperparameter, to ensure the model is neither overfitting nor underfitting.

Both models were evaluated using appropriate metrics to determine which one provides the best performance in predicting patient hospitalization. This selection was based on the results analysis and consideration of the specific healthcare problem at hand.

## Conclusions

The project enabled the identification of significant features influencing patient hospitalization after a prostate biopsy. The developed Machine Learning models provide a foundation for predicting hospitalization and supporting medical decision-making.

This project demonstrates the application of Data Science techniques in the field of medicine, potentially leading to substantial improvements in patient care.

## Acknowledgments

We would like to thank our client and the consultancy for providing the opportunity to work on this project. We also extend our gratitude to our instructors for their guidance and support throughout the course.

Data Science Team: Kevin Coaguila, Sebastián Risi, Adrián Felipe Pérez Díaz, Carlos G. Cantón, César Chirino.

October 2023
