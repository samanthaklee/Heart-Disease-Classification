## Heart-Disease-Classification
Testing the effectiveness of various classification algorithms on predicting heart disease.

### Contributors
+ Samantha Lee
+ Richard Boone

### Abstract
Data classification can often be applied to medical data, helping detect the prevalence of disease.

The following analysis predicts the prevalence of heart disease from a dataset drawn from four different sources: the Cleveland Clinic Foundation, the Hungarian Institute of Cardiology, Budapest and the University Hospital, Zurich, Switzerland and is drawn from the UCI Machine Learning Repository. This project focuses on the classification of heart disease by using several machine learning algorithms, such as random forests, kth-nearest neighbors, support vector machine and logistic regression. The analysis implements Python and Python libraries including these algorithms to come up with a model that best predicts the diagnosis (0 = not present, 1 = present). Through the investigation, we will find which algorithm most effectively and consistently predicts the presence of heart disease.

We will examine 11 out of 76 total attributes, including age, sex, chest pain type, resting blood pressure, cholesterol level, etc.

### Methods
Here are the Machine learning methods we decided to use:
+ Kth Nearest Neighbor
+ Decision Trees
+ Random Forest
+ Support Vector Machine 

Some libraries in python that we used were 
+ pandas
+ scikit learn
+ matplotlib (for visuals)
+ plotly (for interactive plots)

### Conclusions
Using random forests has produced the best performances in test error rate and having true positives/true negatives, and I highly doubt that I will find an algorithm that performs better than that. 

| Model/Algorithm | Test Accuracy Rate | Area under the Curve for ROC |
|-----------------|-----------------|----------------|
| Decision Trees | 95.64% | 0.9706 | 
| Random Forest| 96.491% | 0.9706 | 
| Support Vector Machine| 72.81% | 0.7399 | 
| Kth Nearest Neighobrs| 73.68% | 0.7434 | 
