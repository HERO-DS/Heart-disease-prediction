# Heart Disease Prediction Project

## Overview

This project aims to predict the likelihood of coronary heart disease (CHD) using machine learning techniques, specifically logistic regression. The dataset used for this project is sourced from the Framingham Heart Study, which is a well-known study focusing on cardiovascular health.

## Table of Contents
- [Background](#background)
- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Modeling](#modeling)
- [Results](#results)
- [Conclusion](#conclusion)
- [Acknowledgments](#acknowledgments)

## Background

Coronary heart disease (CHD) remains a leading cause of death worldwide, making early detection and prevention crucial. In this project, I aim to build a predictive model that helps identify individuals at high risk of developing CHD based on various health parameters.

## Dataset

The dataset used in this project is the [Framingham Heart Study dataset] from kaggle, which includes the following features:

- **Sex_male**: Male gender indicator (1 = male, 0 = female)
- **Age**: Age of the patient
- **CurrentSmoker**: Smoking status (1 = current smoker, 0 = non-smoker)
- **CigsPerDay**: Number of cigarettes smoked per day
- **BPMeds**: Blood pressure medication indicator
- **PrevalentStroke**: History of stroke (1 = yes, 0 = no)
- **PrevalentHyp**: History of hypertension (1 = yes, 0 = no)
- **Diabetes**: Diabetes status (1 = yes, 0 = no)
- **TotChol**: Total cholesterol level
- **SysBP**: Systolic blood pressure
- **DiaBP**: Diastolic blood pressure
- **BMI**: Body Mass Index
- **HeartRate**: Heart rate
- **Glucose**: Glucose level
- **TenYearCHD**: Indicator for coronary heart disease (1 = yes, 0 = no)

The dataset contains a total of 3,751 entries.

## Data Preprocessing

The data preprocessing steps included:

- Loading the dataset and inspecting the first few rows.
- Dropping the 'education' feature as it was deemed irrelevant for this analysis.
- Renaming columns for clarity.
- Handling missing values by dropping any rows with null values.
- Normalizing the feature set using `StandardScaler`.

## Exploratory Data Analysis (EDA)

The EDA included:

- A visualization of the distribution of patients affected by CHD using a count plot.
- An evaluation of significant variables that correlate with the likelihood of developing CHD.

## Modeling

I implemented a Logistic Regression model for the prediction of CHD. The steps included:

- Splitting the dataset into training and testing sets (70% train, 30% test).
- Training the logistic regression model on the training data.
- Making predictions on the test data.

## Results

The accuracy of the model was evaluated using the accuracy score metric. The fitted logistic regression model achieved an accuracy of **85.26%**.

## Conclusion

This project demonstrates the application of logistic regression in predicting the likelihood of coronary heart disease using vital health indicators. The model can serve as a preliminary tool for assessing heart disease risk in patients, aiding healthcare professionals in making informed decisions about further testing and preventative measures.

## Acknowledgments

I would like to acknowledge the contributors of the Framingham Heart Study dataset, which made this analysis possible. Additionally, this project was guided by online resources (GeeksforGeeks) and tutorials, but all implementations were executed independently to enhance my learning and understanding of data science and machine learning concepts.

Feel free to explore the code and analysis in the accompanying Jupyter Notebook. Contributions and feedback are welcome!
