#Online Data Science Bootcamps for SDAIA Academy 

# Telemonitoring of Parkinson's disease progression 
#Comparing between machine learning techniques that can be used for improve the prediction of Parkinson's disease.

## Abstract 
The goal of this project is to improve prediction of Parkinson's disease (PD) progression, which is needed to support clinical decision-making and to accelerate research trials. I worked with data provided in this link (https://archive.ics.uci.edu/ml/datasets/Parkinsons+Telemonitoring), I will use machine learning models to achieve promising results for this problem. 

## Design
Unified Parkinson’s Disease Rating Scale (UPDRS) is widely used for tracking PD symptom progression. Motor- and Total-UPDRS are two important clinical scales. it can be predict UPDRS scores through analyzing the speech signal properties. with machine learning algorithms it can be improve the prediction 

## Data
This dataset consists of audio medical measurements of 42 people with early-stage Parkinson's disease. These people were hired for a six-month trial of a remote-controlled device to remotely diagnose the disease. The data were automatically recorded in patients' homes.
The columns include an index number of each patient, his age, his gender, the duration from the initial date of admission, two motor indicators UPDRS and total UPDRS, and 16 other medical sound measurements. Each line relates to one of 5,875 different sound measurements from those of the volunteers.

## Algorithm 
It can be separate the data into train and test, the train set is 30% of our original data set. Then divide the features, and select subset of important features to work with it. 
*Models:*
Linear Regression, Polynomial Regression, k-Nearest Neighbors, Gradient Boosting Regressor, Decision Tree Regressor and Random Forests. all models generally perform well, there is no one to give us bad results, but Random Forests have the best possible performance.

## Tools
Numpy and Pandas for data manipulation
Matplotlib and Seaborn for plotting
Scikit-learn for modeling
