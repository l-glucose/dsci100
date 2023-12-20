# dsci100
This is Group Project for DSCI 100 2023W T1 Group 2

# Cardiovascular Diseases Report

## Introduction

Cardiovascular diseases (CVDs) stand as the leading global cause of death, claiming an estimated 17.9 million lives annually [1]. This group of disorders affecting the heart and blood vessels includes coronary heart disease, cerebrovascular disease, rheumatic heart disease, and other conditions [1]. Over four-fifths of CVD deaths result from heart attacks and strokes, with one-third occurring prematurely in individuals under 70 years of age [2].

The data for this analysis was sourced from Kaggle, focusing on characteristics related to heart attacks and contributing factors.

In this project, our goal is to develop a classification model using a database capturing key factors like gender, age, blood glucose, and blood pressure. This model aims to predict the likelihood of a new patient experiencing a heart attack.

By employing a classification model, we aim to predict the presence of a heart attack based on key predictors. The central question we address is: Is a new patient likely to have heart disease, considering age, troponin, and kcm?

## Methods

As the variable "class," depicting the presence of a heart attack, is categorical, we choose to conduct our data analysis using the K nearest neighbors classification algorithm.

To visually represent our results and predictions, we plan to create a scatter plot highlighting factors contributing to the presence of a heart attack. We will select specific columns of data for our prediction:

- **age**: Age of the patients
- **kcm**: Amount of specific enzymes (CK-MB) - renamed to enzyme_amount
- **troponin**: Test-Troponin in (ng/L [4])
- **class**: Diagnosis type - negative refers to the absence of a heart attack, while positive refers to the presence of a heart attack.

We will conduct a KNN-classification analysis for three models: the first model (age, troponin) and the second (age, enzyme_amount) leverage two predictors, while the third model (age, troponin, and enzyme_amount) uses all three.

# Running Project in Jupyter Notebook with R Kernel

To get started, follow these instructions to open and run the project in Jupyter Notebook using the R kernel.

1. **Navigate to the Project Directory:**
   Open a terminal or command prompt and navigate to the directory where your project file is located. In this case, it seems to be in the "Final" directory under the file name "DSCI 100 003 Group 2 Report.ipynb".

   ```bash
   cd path/to/Final

