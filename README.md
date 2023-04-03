# Stroke - EDA and classification

In this project, medical data classification related to stroke was performed. The project included the replacement of NaN values using the MICE algorithm and the removal of outliers using the Local Outlier Factor algorithm. Additionally, EDA (Exploratory Data Analysis) was carried out.

The data was then divided into training and test sets, and several algorithms were implemented using a pipeline that included StandardScaler and SMOTETomek for each model. The focus was on the best model, which was the Random Forest Classifier. The pipeline with PCA was made to reduce the number of features in the dataset. Hyperparameters were then tuned using Random Search. A confusion matrix and ROC curve were also created to evaluate the classifier.

Therefore, the project successfully implemented various techniques to clean and preprocess the medical data, applied different algorithms using a pipeline, and fine-tuned the best model using PCA and RandomizedSearch to achieve optimal performance.


#### Source of dataset:
https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset

Description:

1) id: unique identifier
2) gender: "Male", "Female" or "Other"
3) age: age of the patient
4) hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
5) heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
6) ever_married: "No" or "Yes"
7) work_type: "children", "Govt_jov", "Never_worked", "Private" or "Self-employed"
8) Residence_type: "Rural" or "Urban"
9) avg_glucose_level: average glucose level in blood
10) bmi: body mass index
11) smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"*
12) stroke: 1 if the patient had a stroke or 0 if not
