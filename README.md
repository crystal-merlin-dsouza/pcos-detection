# PCOS Detection Using Logistic Regression

## Project Overview
This project uses logistic regression to predict Polycystic Ovary Syndrome (PCOS) based on clinical and biological features such as hormone levels, BMI, and menstrual cycle regularity. The aim is to assist healthcare professionals in early diagnosis and personalized treatment of PCOS.

## Dataset
- The dataset is sourced from **Kaggle** and contains clinical features relevant to PCOS diagnosis. Features include age, BMI, insulin resistance, hormone levels (e.g., LH, FSH, testosterone), and menstrual regularity. 
- Link: https://www.kaggle.com/datasets/prasoonkottarathil/polycystic-ovary-syndrome-pcos/data

## Key Features
1. **Exploratory Data Analysis (EDA):** Patterns in clinical and biological variables related to PCOS are analyzed.
2. **Logistic Regression Model:** A logistic regression model is built and trained to predict PCOS.
3. **Model Evaluation:** The model is evaluated using metrics like accuracy, precision, recall, and F1-score.

## Results
The logistic regression model provides the following performance metrics:
- **Accuracy:** 86.24%
- **Precision (Class 0 - No PCOS):** 0.89
- **Precision (Class 1 - PCOS):** 0.82
- **Recall (Class 0 - No PCOS):** 0.90
- **Recall (Class 1 - PCOS):** 0.79
- **F1-Score (Class 0 - No PCOS):** 0.89
- **F1-Score (Class 1 - PCOS):** 0.81

These results indicate that the model performs well in predicting both PCOS and non-PCOS cases, with an overall accuracy of 86.24%.
