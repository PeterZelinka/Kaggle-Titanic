# Titanic Passenger Survival Prediction

## Introduction
This project represents a take on the Kaggle Titanic competition. After data exploration, cleaning and feature engineering, 3 classification models are fitted to the training data supplied by Kaggle. Each model together with various hyperparameters is input to sklearn's grid search and one with the highest accuracy is chosen for predicting whether a passenger survived or not. The workflow of the project was desinged such that it is relatively easy to add/remove models, variables and/or hyperparameters and submit newly predicted values.

## Datasets
The data is divided into two datasets. The train.csv and the test.csv. The former contains information about passengers including whether they have survived or not (the ground truth). The latter on the other hand contains the same features except for the survived column. Information in test.csv is used to make predictions that are submitted to Kaggle.

### Variables:
- `PassengerID` (ID of the passenger)
- `Survived` (1 - Survived 0 - Did not survive) - only in train.csv
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

## Installation

### Install the requirements:

To install the requirements you can use `pip install -r requirements.txt`
-	You may also choose to use virtual environment for this

### To install the project:

In a directory of your choice, run:

 1. `git clone https://github.com/PeterZelinka/Message-Classifier.git`

 2. Install [Anaconda](https://www.anaconda.com/products/individual)
 3. Open JupyterNotebook
 4. Navigate to the location where you cloned the directory
 5. Open and run Titanic.ipynb
