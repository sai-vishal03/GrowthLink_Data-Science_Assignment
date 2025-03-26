# GrowthLink_Data-Science_Assignment
Titanic Project

"Titanic Survival Prediction": This project predicts whether a passenger survived the Titanic disaster using a machine learning model. The goal is to build a classification model that accurately predicts survival based on various features such as age, gender, ticket class, fare, and engineered features like family size and title.

Task Objectives:
- Predict Survival: Develop a model to predict the `Survived` status (0 or 1) for Titanic passengers.
- Data Preprocessing: Handle missing values, encode categorical variables, and scale numerical features.
- Feature Engineering: Create additional features such as FamilySize and extract Title from passenger names.
- Model Training & Tuning: Use a Random Forest classifier with hyperparameter tuning via GridSearchCV.
- Evaluation: Assess model performance using accuracy, classification report, confusion matrix, and feature importance.

Dataset: The dataset used in this project is provided in the file `tested.csv`. It contains the following columns (among others):
- `PassengerId`
- `Survived`
- `Pclass`
- `Name`
- `Sex`
- `Age`
- `SibSp`
- `Parch`
- `Ticket`
- `Fare`
- `Cabin`
- `Embarked`

Requirements
- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, joblib

You can install the required libraries with:
cmd: pip install -r requirements.txt
