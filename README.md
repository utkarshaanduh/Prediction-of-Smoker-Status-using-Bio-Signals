# Prediction-of-Smoker-Status-using-Bio-Signals

## Problem Description
The goal of this project is to create a machine learning model to predict a patient's smoking status using various bio-signals. This is part of a Kaggle Playground Series Competition. Our model will output the probability that a given patient smokes. We will evaluate the model's performance on area under the ROC curve using Stratified KFold validation.

For each id in the test set, you must predict the probability for the target variable smoking. The file should contain a header and have the following format:

id,smoking
159256,0.5
159257,0.5
159258,0.5
etc.

# About the Dataset
Here we have used the "Kaggle Competition Data" which has following features:
* Id: It is a Unique key identifier
* Age: Age of the observations of the dataset
* Height(cm): Height of the observations of the dataset
* Weight(kg): Weight of the observations of the dataset
* Waist(cm): Waist of the observations of the dataset
* Eyesight(Left,Right): Eyesight details of the observations of the dataset
* Hearing(Left,Right): Hearing of the observations of the dataset
* Systolic: Systolic of the observations of the dataset
* Relaxation: Relaxaton detail of the observations of the dataset
* Fasting: Fasting detail of the observations of the dataset
* Blood Sugar: Blood Sugar level of the observations of the dataset
* Cholesterol: Cholesterol level of the observations of the dataset
* Triglyceride: Triglyceride level in the body of the observations of the dataset
* HDL: HDL value in body of the observations of the dataset
* LDL: LDL value in body of the observations of the dataset
* Hemoglobin: Hemoglobin status of the observations of the dataset
* Urine: Urine status of the observations of the dataset
* Protein: Protein level of the observations of the dataset
* Serum: Serum Cotinine level of the observations of the dataset
* Creatinine: Creatinine level in body of the observations of the dataset
* AST: AST level of the observations of the dataset
* ALT: ALT level of the observations of the dataset
* GTP: GTP value of the observations of the dataset
* Dental Caries: Dental condition of the observation of the datset
# Software tools used:
* Jupyter notebook
# Python Library Used:
* Pandas
* Sci-Kit Learn
