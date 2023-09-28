<<<<<<< HEAD
# Project-4-Stroke-Prediction-# README - Stroke Prediction Model
=======
# Project-4-Stroke-Prediction
>>>>>>> bc172e23993d3c13cd7ba324915c36cbb75ebd7b

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
To prepare the data for model training, we performed several preprocessing steps:

<<<<<<< HEAD
1. **Feature Selection:** We dropped the non-beneficial ID columns, 'EIN' and 'NAME,' from the dataset.

2. **Categorical Data Encoding:** We used one-hot encoding (pd.get_dummies) to convert categorical data into numeric format, making it suitable for machine learning.

3. **Binning:** We performed binning on the "APPLICATION_TYPE" and "CLASSIFICATION" columns to reduce the number of unique values and improve model performance.

4. **Data Split:** We
=======
>>>>>>> bc172e23993d3c13cd7ba324915c36cbb75ebd7b
