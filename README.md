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
Note: A requirements.txt file is included with the project.

How to Run the Project:
Clone the Repository:
cmd: 
git clone <repository_url>
cd <repository_directory>
Ensure tested.csv is in the project directory.

Run the Script:
cmd: python titanic_survival.py

The script will:
Load and perform exploratory data analysis (EDA).
Engineer new features and preprocess the data.
Train a Random Forest classifier with hyperparameter tuning.
Evaluate the model and display performance metrics.
Save the best model to disk.

Project Structure:
├── titanic_survival.py   # Main Python script containing the entire pipeline
├── tested.csv            # Titanic dataset file
├── requirements.txt      # List of required Python libraries
└── README.md             # This file

Evaluation & Results: The project prints out:
Basic EDA information and visualizations.
The best hyperparameters found by GridSearchCV.
Test accuracy, classification report, and confusion matrix.
A feature importance plot showing which features were most useful for predicting survival.

Innovation & Creativity:
Advanced Feature Engineering: The project extracts a passenger's title from their name and calculates family size.
Comprehensive EDA: Visualizations and a correlation heatmap help understand the dataset.
Optimized Pipeline: Uses scikit-learn’s Pipeline and ColumnTransformer for clean, efficient code.
Hyperparameter Tuning: GridSearchCV is used to optimize model performance.

License: This project is for educational purposes. You are free to use and modify the code.

Contact:
For any questions or suggestions, please contact:
Email: help.growthlink@gmail.com
Website: GrowthLink
