## Heart Attack Prediction Project

### Team:

Kaustav ghosh Dastidar, 
Itzel Cruz, 
Subin An

### 1. Introduction:
This project aims to develop a predictive model that can accurately classify individuals based on their risk of experiencing a heart attack. Utilizing various clinical and demographic features, our model aims to assist healthcare providers in identifying high-risk patients for preventative interventions.

### 2. Data:
The dataset for this project comprises clinical records and demographic information of individuals, encapsulating features that are potentially indicative of heart disease risk.

Data Attributes:
Age: Age of the individual
Sex: Gender of the individual
ChestPainType: Type of chest pain experienced
RestingBP: Resting blood pressure
Cholesterol: Serum cholesterol
FastingBS: Fasting blood sugar
RestingECG: Resting electrocardiographic results
MaxHR: Maximum heart rate achieved
ExerciseAngina: Exercise-induced angina
Oldpeak: ST depression induced by exercise relative to rest
Slope: The slope of the peak exercise ST segment
HeartDisease: Presence or absence of heart disease

### 3. Exploratory Data Analysis:
Initial data exploration steps included checking for missing values, duplicate entries, and understanding the distribution of the target variable (HeartDisease). A correlation analysis was performed to identify relationships between features.

Visualizations:
Distribution of Age vs. Heart Disease Risk
Gender and Heart Disease Prevalence
Impact of Chest Pain Type on Heart Disease Risk

### 4. Data Visualization Libraries Used:
Matplotlib
Seaborn
Plotly Express

### 5. Modeling
Various models were evaluated for their performance in predicting heart attack risk, including Logistic Regression, Decision Trees, and Random Forests. Performance metrics such as accuracy, precision, recall, and AUC-ROC were used to compare model efficacy.

### 6. Insights & Recommendations:
The analysis provided insights into key factors influencing heart attack risk and the effectiveness of different modeling approaches. Recommendations for healthcare interventions and areas for future research are discussed.

### 7. Setup:
Required Libraries:
python
Copy code
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.model_selection import train_test_split
from sklearn.linear_model import Logistic Regression
from sklearn.metrics import confusion_matrix, accuracy_score
import plotly.express as px

### To Run the Project:
Clone the repository.
Install the required libraries.
Run the analysis notebook or scripts as detailed in the project's documentation.

### Note:
Ensure your data is correctly formatted and placed in the specified directories before executing the scripts. Refer to the project's Jupyter notebooks or Python scripts for any custom functions or detailed model training steps.
