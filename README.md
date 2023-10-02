# Project-4-Stroke-Prediction-# README - Stroke Prediction Model

## Introduction
Stroke is a leading cause of death globally, responsible for approximately 11% of total deaths, according to the World Health Organization (WHO). Early detection and prediction of stroke risk can play a crucial role in preventing strokes and improving healthcare outcomes. This project aims to develop a machine learning model to predict whether a patient is likely to have a stroke based on various input parameters, such as gender, age, medical history, and lifestyle factors.

## Problem Statement
The primary problem we are addressing is the prediction of stroke occurrence in patients. We want to develop a model that can classify patients into two groups: those at risk of stroke (1) and those not at risk (0). This prediction will help healthcare providers identify high-risk patients and take preventive measures to reduce the likelihood of stroke.

## Data Source

https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset

The dataset used for this project contains information about patients and their attributes, including whether or not they had a stroke. Here are the attributes in the dataset:

1. **id:** Unique identifier
2. **gender:** Gender of the patient (e.g., "Male," "Female," or "Other")
3. **age:** Age of the patient
4. **hypertension:** 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
5. **heart_disease:** 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
6. **ever_married:** "No" or "Yes"
7. **work_type:** Type of work (e.g., "children," "Govt_job," "Never_worked," "Private," or "Self-employed")
8. **Residence_type:** Type of residence ("Rural" or "Urban")
9. **avg_glucose_level:** Average glucose level in the blood
10. **bmi:** Body mass index
11. **smoking_status:** Smoking status (e.g., "formerly smoked," "never smoked," "smokes," or "Unknown"*)
12. **stroke:** 1 if the patient had a stroke or 0 if not

*Note: "Unknown" in smoking_status means that the information is unavailable for this patient.

## Data Preprocessing
Before training the stroke prediction model, we carried out several data preprocessing steps to ensure the data is suitable for machine learning:

Data Cleaning: We checked for missing values in the dataset and handled them appropriately. Missing values in the bmi column were imputed with the mean BMI value, and missing values in the smoking_status column were marked as "Unknown."

Encoding Categorical Variables: We converted categorical variables like gender, ever_married, work_type, Residence_type, and smoking_status into numerical values using techniques like one-hot encoding or label encoding.

Data Splitting: We split the dataset into training and testing sets to evaluate the model's performance. Typically, we used a 80-20 split, with the larger portion for training.

## Model Development
We implemented a machine learning model to predict stroke occurrences based on the preprocessed data. Various algorithms were tested, including 
- Logistic Regression: This algorithm was used in the initial part of the code to create a logistic regression model. Logistic regression is a binary classification algorithm that is commonly used for predicting binary outcomes, such as whether or not a patient had a stroke (1 or 0 in this case).

- Artificial Neural Network (ANN): An ANN was created and trained using TensorFlow/Keras. This deep learning algorithm consists of multiple layers of interconnected nodes (neurons) and is capable of learning complex patterns in data. In this case, it was used for binary classification, similar to logistic regression, to predict whether a patient had a stroke.

These two algorithms were tested and evaluated using the provided healthcare data to determine their performance in predicting strokes.

## Visualization 
 We separated the visualization code from the machine learning code to enhance the organization and maintainability of our project. This separation allows us to keep the core machine learning logic focused in one file, making it easier to manage and update, while visualizations are organized separately for clarity, readability, and potential reuse in various project-related contexts.
 
## Resources 
- Online (Stackoverflow ,Blackbox.io,Kaggle and Chat Gpt)
- Course materials 
- https://www.who.int/news-room/fact-sheets/detail/the-top-10-causes-of-death


**Contributors:** 
-  Alexandra De Roos, Ryan Williams, and George Kalad

