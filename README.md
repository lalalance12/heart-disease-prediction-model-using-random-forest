# Heart Disease Prediction Model using Random Forest

## Project Overview

This project aims to predict the risk of heart disease using a Random Forest algorithm. The dataset used contains 14 features that are known to contribute to heart attack risk. The goal is to develop a model that can help in early detection and prevention of heart disease.

## Feature Descriptions

- **age**: Age of the patient (Numeric).
- **sex**: Gender of the patient. Values: 1 = male, 0 = female.
- **cp**: Chest pain type. Values: 0 = Typical angina, 1 = Atypical angina, 2 = Non-anginal pain, 3 = Asymptomatic.
- **trestbps**: Resting Blood Pressure (in mm Hg) (Numeric).
- **chol**: Serum Cholesterol level (in mg/dl) (Numeric).
- **fbs**: Fasting blood sugar > 120 mg/dl. Values: 1 = true, 0 = false.
- **restecg**: Resting electrocardiographic results. Values: 0 = Normal, 1 = ST-T wave abnormality, 2 = Left ventricular hypertrophy.
- **thalach**: Maximum heart rate achieved (Numeric).
- **exang**: Exercise-induced angina. Values: 1 = yes, 0 = no.
- **oldpeak**: ST depression induced by exercise relative to rest (Numeric).
- **slope**: Slope of the peak exercise ST segment. Values: 0 = Upsloping, 1 = Flat, 2 = Downsloping.
- **ca**: Number of major vessels (0-3) colored by fluoroscopy. Values: 0, 1, 2, 3.
- **thal**: Thalassemia types. Values: 1 = Normal, 2 = Fixed defect, 3 = Reversible defect.
- **target**: Outcome variable (heart attack risk). Values: 1 = more chance of heart attack, 0 = less chance of heart attack.

## Description

This dataset includes 14 features known to contribute to heart attack risk. It is ideal for training machine learning models aimed at early detection and prevention of heart disease. The records have been cleaned by removing missing data to ensure data integrity. This dataset can be applied to various machine learning algorithms, including classification models such as Decision Trees, Neural Networks, and others.

## Algorithm

The Random Forest algorithm is used in this project to predict the risk of heart disease. Random Forest is an ensemble learning method that operates by constructing multiple decision trees during training and outputting the mode of the classes for classification tasks.

## Dataset

The dataset used in this project is sourced from Kaggle. You can find it [here](https://www.kaggle.com/datasets/mfarhaannazirkhan/heart-dataset/data?select=cleaned_merged_heart_dataset.csv).
