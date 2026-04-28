# Medical Insurance Cost Prediction using Random Forest Regression

### Author: MANIKANDAPRABHU.S

### Project Type: Machine Learning – Regression

---

## 1) Project Overview

This project predicts medical insurance costs using a **Random Forest Regression** model.

Random Forest is an ensemble learning technique that combines multiple decision trees to improve prediction accuracy and reduce overfitting. The model learns patterns from customer demographic and health-related data to estimate insurance charges.

---

## 2) Dataset

File used: `insurance_pre.csv`

The dataset contains:

* Age
* BMI (Body Mass Index)
* Number of Children
* Gender
* Smoking Status
* Charges (Target Variable)

The goal is to predict insurance cost based on these features.

---

## 3) Workflow

1. Import required libraries
2. Load dataset using pandas
3. Handle categorical variables using encoding
4. Prepare feature matrix (X) and target variable (y)
5. Split dataset into training and testing sets
6. Train Random Forest Regression model
7. Perform hyperparameter tuning using GridSearchCV
8. Make predictions
9. Evaluate model using:

   * R² Score
   * Mean Squared Error (MSE)
   * Root Mean Squared Error (RMSE)
10. Analyze feature importance
11. Visualize results
12. Save trained model using pickle

---

## 4) Model Evaluation

* Random Forest improves prediction accuracy compared to a single Decision Tree.
* The model reduces overfitting by averaging multiple trees.
* Performance is evaluated using R² Score, MSE, and RMSE.

---

## 5) Project Files

* `01_Random_Forest_Model.ipynb` – Model training and evaluation
* `02_Deployment_Random_Forest.ipynb` – Model deployment and prediction
* `insurance_pre.csv` – Dataset
* `Finalized_RF_model.sav` – Trained Random Forest model
* `requirements.txt` – Required Python libraries

---

## 6) Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn
* Pickle

---

## 7) Model Deployment

* Model is saved using pickle
* Deployment implemented using Jupyter Notebook
* User input is taken and passed directly to the model for prediction
* No feature scaling is required for Random Forest

---

## 8) Conclusion

* Implemented Random Forest Regression for insurance cost prediction
* Ensemble learning improved accuracy and reduced overfitting
* Model effectively captures non-linear relationships
* Feature importance provides insights into key influencing factors

---

## 9) Use Case

This project can help insurance companies estimate customer charges based on personal and health-related factors, enabling better pricing and risk assessment strategies.
