# Car Evaluation Classification

## Problem Statement
Build a multi-class classifier to predict a car’s acceptability category based on purchase/maintenance cost, safety, and related attributes.

## Dataset
The Car Evaluation dataset contains categorical features describing car attributes (e.g., buying price, maintenance, doors, persons, luggage boot, safety) and a target label representing acceptability.

## Approach
1. Load and validate the dataset
2. Exploratory checks (shape, missing values, label distribution)
3. Encode categorical variables
4. Train/test split
5. Train baseline model
6. Train improved model
7. Evaluate and compare

## Models
- Baseline: Decision Tree
- Improved: Random Forest

## Evaluation
Metrics:
- Accuracy
- Confusion Matrix
- Classification Report (precision/recall/F1)

## Results (fill after running)
- Decision Tree Accuracy: [TBD]
- Random Forest Accuracy: [TBD]

## How to Run
1. Open `car_classification.ipynb`
2. Run all cells top to bottom

## Next Improvements
- Hyperparameter tuning (GridSearchCV)
- Proper ordinal encoding for ordered features
- Cross-validation and learning curves
- Model interpretability (feature importance / permutation importance)
