# Kaggle Titanic Machine Learning Competition

## Introduction
This project represents a take on the Kaggle Titanic competition. After data exploration, cleaning and feature engineering, 3 classification models are fitted to the training data supplied by Kaggle. Each model together with various hyperparameters is input to sklearn's grid search and one with highest accuracy is returned and used for predicting values of the survived column. The workflow of the project was desinged such that it is relatively easy add/remove models and/or parameters and submit the predicted values.

## Datasets
The data is divided into two datasets train.csv and test.csv. The former contains data about passengers including whether they have survived or not (the ground truth). The latter on the other hand contains the same features except for the survived column. The information in test.csv are used to make prediction that are submitted to Kaggle.

### Variables:
- `PassengerID` (ID of the passenger)
- `Survived` (1 - Survived 0 - Did not survive)
- `Pclass`	(Ticket class	1 = 1st, 2 = 2nd, 3 = 3rd)
- `Name` (Full name including titles)
- `Sex` (Sex of the passenger)
- `Age` (Age of the passenger)
- `Sibsp` (Number of siblings / spouses aboard)
- `Parch` (Number of parents / children aboard)
- `Ticket` (Ticket number)
- `Fare` (Passenger fare)
- `Cabin` (Cabin number)
- `Embarked` (Port of Embarkation)

## Reproducing the project
In order to reproduce the analysis all you need to do is download train.csv, test.csv and Kaggle Titanic.ipnyb and run the latter.
