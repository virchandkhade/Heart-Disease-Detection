Project Title: Heart Disease Prediction Using Logistic Regression

Objective:
The goal of this project was to predict whether a patient has heart disease based on various health attributes. By analyzing historical health data, the objective was to build a classification model that can accurately predict the presence of heart disease in a patient.

Process and Technology:
 1) Dataset and Data Cleaning:
 Downloaded the dataset from Kaggle, which contains information on various health indicators and heart disease diagnoses.
 Imported necessary libraries such as Pandas, NumPy, and Matplotlib in Jupyter Notebook.
 Cleaned the dataset by detecting and handling null values using a heatmap, identifying outliers through boxplots, and performing other 
 necessary data-cleaning steps.

 2) Exploratory Data Analysis (EDA):
 Analyzed the dataset using Python’s shape, describe(), value_counts(), and groupby() functions to understand the distribution of data 
 and detect any patterns.
 Performed statistical analysis using mean and median to get insights into the central tendencies of the data.

 3) Feature Engineering:
 Separated the dataset into dependent (target) and independent (predictor) variables.

 4) Model Development:
 Split the data into training and testing sets using train_test_split.
 Developed a Logistic Regression model to classify patients based on their health data.
 First iteration achieved an accuracy score of 82%, indicating a strong model performance.
 In the second iteration, re-evaluated and achieved an accuracy score of 81%, maintaining strong predictive capability.

Technology:
Programming Language: Python
Libraries and Tools:
                    Pandas, NumPy, Matplotlib for data manipulation and visualization
                    Scikit-learn for machine learning model (Logistic Regression)
                    Jupyter Notebook for interactive coding and analysis

Impact:
The project provided valuable insights into the factors contributing to heart disease, helping healthcare professionals make data-driven decisions for patient diagnosis and treatment.
It can be used to assist in early detection of heart disease, thereby improving patient outcomes by taking preventive measures at an early stage.

Result:
Achieved an accuracy score of 82% in predicting whether a patient has heart disease using a Logistic Regression model.
Validated the model with an accuracy of 81% in the second iteration, confirming its reliability for heart disease prediction.

