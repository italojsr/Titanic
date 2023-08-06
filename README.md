# Titanic Challenge

<div align = "center">

![RMS_Titanic_3](https://github.com/italojsr/Titanic/assets/97315148/540cde97-0a3b-4fc5-8a10-18e7b3376b33)

</div>

## Challenge Description
Over the challenge, it is expected to use machine learning to create a model that predicts which passengers survived the Titanic shipwreck.
It is a classical problem of binary classification, once that is given a training set with the labels of the passengers who survived and who died.

## Goals
The goal of this project is to apply all steps that an end-to-end machine learning project may have. Such as Preprocessing,Exploratory Data Analysis (EDA),
Selecting models and Tuning Hyperparameters. All of it was done using libraries as Scikit-learning, pandas,numpy, matplotlib and seaborn.

## Solution Strategy
To solve this problem the following steps were taken:
- Data Cleaning : Missing values and Outliers were evaluated and cleaned from the dataset.
- Exploratory Data Analysis : It was evaluated how some attribute could be correlated to the survival of the passengers
- Preprocessing : Categorical attributes were encoded and Numerical attributes were scaled.
- Model Selection : Different models were tested using metrics for classification.
- Hyperparameter optimization : Different configurations of parameters were tested for the best model.
- Predictions on the Test Set : The test set was classified by the final model. 

## Insights from EDA
-  Females had a greater percentage of survivals
-  The third class of the ship had the greater percentage of people that didn't survive
-  There were a greater percentage of males on the third class

## Machine learning models performance
| Model | Accuracy | AUC score | F1 score
| ------- | ------- |------- |------- |
| SVC | 0.825677 | 0.839334 | 0.758190 |
| Random Forest| 0.813317 | 0.852638 | 0.750000 |
| Decision Tree| 0.806512 | 0.842618 | 0.733746 |
| LinearSVC| 0.786249 | 0.812547 | 0.708589 |
| SGD| 0.717735 | 0.752229 | 0.613251 |

  
![metric](https://github.com/italojsr/Titanic/assets/97315148/9b8d78eb-865c-465f-a13f-96eb166bea1a)


## Results

The final prediction on the test set had an accuracy of 0.77272 which is slightly greater than the sample available for comparison on the kaggle website (0.76555).
