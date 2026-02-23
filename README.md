## Project Title

Titanic Survival Prediction

## Problem Statement

Predict passenger survival on the Titanic shipwreck.

## Dataset

Source: Kaggle – Titanic: Machine Learning from Disaster

Key Features from Dataset:

- Survived → Target variable (0 = No, 1 = Yes)
- Pclass   → Passenger class (proxy for socioeconomic status)
- Sex      → Passenger gender
- Age      → Passenger age (contains missing values)
- Fare     → Ticket fare (skewed distribution)
- Cabin    → Cabin #
- sibsp    → # of siblings / spouses aboard the Titanic
- parch	   → # of parents / children aboard the Titanic

## Tech Stack

- Python
- Pandas
- Scikit-learn

## Approach

- Performed Exploratory Data Analysis (EDA)
- Handled missing values (Age, Cabin)
- Engineered predictive features:
    FamilySize
    IsAlone
    HasCabin
    Deck
- Feature Selection
- Trained RandomForestClassifier


## Model

RandomForestClassifier

## Results

Random Forest: 
    Cross Validation Accuracy: 0.81-->0.82-->0.83
    Kaggle Score: 0.76794

XGBoost:
    Cross Validation Accuracy: 0.84
    Kaggle Score: 0.77033