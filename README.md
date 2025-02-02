# Overview
This project aims to predict whether an individual has diabetes using machine learning techniques. The dataset diabetes.csv is utilized for both training and testing purposes. The implementation is done in Jupyter Notebook, leveraging powerful Python libraries such as pandas, numpy, matplotlib, seaborn, and scikit-learn for data processing, visualization, and model training.

# Dataset
The dataset contains 2,000 rows and 9 columns, consisting of medical parameters that help in predicting diabetes. Some key features include:

* Pregnancies – Number of times the patient has been pregnant
* Glucose – Blood glucose level
* Blood Pressure – Diastolic blood pressure (mm Hg)
* BMI – Body mass index
* Age – Patient's age
* Outcome – Target variable (1 = Diabetic, 0 = Non-Diabetic)

# Data Preprocessing
* Missing or incorrect values (such as 0 in certain medical parameters) were treated and replaced with the median value of their respective columns.
* The dataset was split into 70% training data and 30% test data for model evaluation.

# Model Training
Two different machine learning models were implemented to analyze their performance:
* Logistic Regression Model
* Random Forest Classifier

# Results
The accuracy of both models was evaluated, and the following results were obtained:

* Logistic Regression Model: 79.5% Accuracy
* Random Forest Classifier: 97.17% Accuracy
