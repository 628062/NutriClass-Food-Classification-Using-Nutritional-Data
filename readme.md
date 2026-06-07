# NutriClass: Food Classification Using Nutritional Data

## Project Overview

NutriClass is a machine learning project that predicts the category of a food item based on its nutritional information. The objective is to classify foods such as Pizza, Burger, Sushi, Pasta, and others using nutritional attributes.

The project applies data preprocessing, feature engineering, machine learning model training, evaluation, and model saving for future predictions.

---

## Problem Statement

Food items contain different nutritional characteristics such as calories, protein, fat, carbohydrates, sugar, fiber, sodium, cholesterol, glycemic index, water content, and serving size.

The goal of this project is to build a machine learning model that can accurately predict the food category based on these nutritional features.

---

## Dataset Features

### Numerical Features

* Calories
* Protein
* Fat
* Carbs
* Sugar
* Fiber
* Sodium
* Cholesterol
* Glycemic_Index
* Water_Content
* Serving_Size

### Categorical Features

* Meal_Type
* Preparation_Method
* Is_Vegan
* Is_Gluten_Free

### Target Variable

* Food_Name

---

## Data Preprocessing

The following preprocessing steps were performed:

1. Removed duplicate records.
2. Handled missing values using mean imputation.
3. Encoded categorical variables into numerical format.
4. Standardized numerical features using StandardScaler.
5. Split the dataset into training and testing sets.

---

## Models Used

The following machine learning algorithms were trained and evaluated:

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)
* Gradient Boosting Classifier
* XGBoost Classifier

---

## Model Evaluation

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## Results

After comparing all models, XGBoost achieved the best performance.

### Best Model

XGBoost Classifier

### Accuracy

Approximately 99%

The model demonstrated excellent classification performance across all evaluation metrics.

---

## Why XGBoost?

XGBoost was selected as the final model because:

* Highest accuracy among all models
* Strong precision, recall, and F1-score
* Handles complex patterns effectively
* Reduces errors through boosting

---

## Model Saving

The final trained XGBoost model was saved using Joblib.

This allows the model to be loaded and used for predictions without retraining.

---

## Future Improvements

* Hyperparameter tuning
* Cross-validation
* Streamlit web application
* Cloud deployment
* Real-time food prediction system

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* XGBoost
* Matplotlib
* Seaborn
* Joblib

---

## Project Workflow

Data Collection
↓
Data Cleaning
↓
Feature Engineering
↓
Data Scaling
↓
Train-Test Split
↓
Model Training
↓
Model Evaluation
↓
Best Model Selection (XGBoost)
↓
Model Saving
↓
Future Deployment

---

## Conclusion

NutriClass successfully classifies food categories using nutritional data. Multiple machine learning models were evaluated, and XGBoost achieved the best performance with approximately 99% accuracy. The project demonstrates the complete machine learning workflow from preprocessing to model deployment readiness.


