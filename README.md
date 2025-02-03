# Titanic_Survival_Classification
## Titanic Survival Classification - Machine Learning Project

Project Overview

This project aims to predict the survival of passengers the Titanic using machine learning models. The dataset is preprocessed, analyzed, and trained with multiple machine learning algorithms to select the best model.

## Dataset

train.csv: Contains labeled data for training the models.
link:- https://drive.google.com/file/d/1_IPwq6rt0QOzpkC5-qQ5oSxJfEbV5W1P/view?usp=drive_link

test.csv: Contains unlabeled data for making predictions.
link:- https://drive.google.com/file/d/1w52VqEAZtFXQSmOO2H5O1DKjZMqS-IH6/view?usp=drive_link

# 1. Data Exploration

Check dataset information and missing values.

Visualize survival distribution using seaborn.

Compute feature correlation using a heatmap.

# 2. Data Preprocessing

Handle missing values:

Fill missing Age values with the median.

Fill missing Embarked values with the mode.

Fill missing Fare values with the median.

Encode categorical variables (Sex, Embarked) using Label Encoding.

# 3. Feature Selection

Select important features using SelectKBest with the chi2 method.

Retain the top 5 most relevant features for training.

# 4. Model Training & Evaluation

Train multiple classifiers:

   1 Logistic Regression

   2 Decision Tree

   3 Random Forest

   4 Support Vector Machine (SVM)

## Evaluate models using:

Cross-validation accuracy

Test accuracy

F1 Score

ROC-AUC Score

Classification report & Confusion matrix

Selection of the best-performing model based on cross-validation accuracy.

# 5. Prediction & Output

Use the best model to make survival predictions on test.csv.

Save predictions to titanic_predictions.csv.

Display the first few predictions in the console.

Dependencies

pip install pandas numpy matplotlib seaborn scikit-learn

# Output

titanic_predictions.csv: Final predictions of passenger survival.

# Conclusion

This project demonstrates data cleaning, feature selection, model evaluation, and prediction for a classic ML problem. The best model is chosen based on performance metrics to make reliable survival predictions.
