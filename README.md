# machine_learning_project-supervised-learning

## Project Outcomes
- Supervised Learning: use supervised learning techniques to build a machine learning model that can predict whether a patient has diabetes or not, based on certain diagnostic measurements.The project involves three main parts: exploratory data analysis, preprocessing and feature engineering, and training a machine learning model. 
### Duration:
Approximately 3 hours and 20 minutes.
### Project Description:
In this projects, you will apply supervised learning techniques to a real-world data set and use data visualization tools to communicate the insights gained from the analysis.

The data set for this project is the "Diabetes" dataset from the National Institute of Diabetes and Digestive and Kidney Diseases 
The project will involve the following tasks:

-	Exploratory data analysis and pre-processing: We will import and clean the data sets, analyze and visualize the relationships between the different variables, handle missing values and outliers, and perform feature engineering as needed.
-	Supervised learning: We will use the Diabetes dataset to build a machine learning model that can predict whether a patient has diabetes or not, using appropriate evaluation metrics such as accuracy, precision, recall, F1-score, and ROC-AUC. We will select at least two models, including one ensemble model, and compare their performance.

The ultimate goal of the project is to gain insights from the data sets and communicate these insights to stakeholders using appropriate visualizations and metrics to make informed decisions based on the business questions asked."

# Supervised Learning Project

## Project/Goals
- Use supervised learning techniques to build a machine learning model that can predict whether a patient has diabetes or not, based on certain diagnostic measurements. 
- Perform exploratory data analysis, 
- Preprocessing and feature engineering, and 
- Training a machine learning model. 

## Process
Step 1: Import libraries and load dataset
Step 2: Explorative Data Analysis to understand the dataset.
Step 3: Check for missing information in the dataset.
Step 4: Clean dataset by identifying and treating outliers, and filling missing values.
Step 5: Apply various machine learning algorithms
Step 6: Validate the ML algorithms to ascertain the best.
Step 7: Interpret and summary findings


## Results/Findings
- After analyzing the histogram we can identify that there are some outliers in some columns.
For Example:-
- Blood Pressure - A living person cannot have a diastolic blood pressure of zero.
- Plasma glucose levels - Zero is invalid number as fasting glucose level would never be as low as zero.
- Skin Fold Thickness - For normal people, skin fold thickness can’t be less than 10 mm better yet zero.
- BMI: Should not be 0 or close to zero unless the person is really underweight which could be life-threatening.
- Insulin: In a rare situation a person can have zero insulin but by observing


## Conclusion
- We can see the Logistic Regression, Random Forest and Gradient Boosting have performed better than the rest. 
- Diabetic and non-diabetic groups shows similar distribution pattern.
- Most variables shows relative positive relationship between themselves.
- Skin thickness and Insulin shows alot of outliers due to the numbers of zeros
- Pregnancies, glucose and BMI variables help to explain the outcome variables better.


