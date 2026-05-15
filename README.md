# Medical Insurance Cost Prediction Using Random Forest Regression

## Project Overview

This project is a Machine Learning application developed to predict medical insurance charges using the Random Forest Regression algorithm. The project demonstrates the end-to-end Machine Learning workflow, including:

- Data preprocessing
- Feature engineering
- Feature scaling
- Random Forest model training
- Model serialization
- Deployment using Streamlit

The application predicts insurance costs using customer-related attributes such as age, BMI, smoking status, gender, and number of children.

---

## Project Structure

```text
Medical-Insurance-Cost-Prediction-RF/
│
├── 01_Random_Forest_.ipynb
├── 02_Deployment_Random_Forest_.ipynb
├── app.py
├── insurance_pre.csv
├── Finalized_RF_model.sav
├── requirements.txt
└── README.md
```

---

## Technologies Used

| Category | Tools / Libraries |
|---|---|
| Programming Language | Python |
| Machine Learning | Scikit-learn |
| Data Processing | Pandas |
| Numerical Computing | NumPy |
| Data Visualization | Matplotlib |
| Model Deployment | Streamlit |
| Feature Scaling | StandardScaler |
| Model Serialization | Pickle |

---

## Dataset Information

The dataset contains customer-related information used for medical insurance cost prediction.

### Features Used

| Feature Name | Description |
|---|---|
| age | Customer age |
| bmi | Body Mass Index |
| children | Number of dependent children |
| sex | Gender |
| smoker | Smoking status |
| charges | Insurance charges (target variable) |

---

## Machine Learning Workflow

### 1. Import Required Libraries

Libraries are imported for:

- Data preprocessing
- Visualization
- Feature scaling
- Model training
- Deployment

---

### 2. Load Dataset

The dataset is loaded using Pandas for preprocessing and analysis.

The preprocessing workflow includes:

- Dataset inspection
- Missing value handling
- Data cleaning
- Feature analysis

---

### 3. Data Preprocessing

Categorical variables are converted into numerical format.

Example encoding:

- Male → 1
- Female → 0
- Smoker → 1
- Non-Smoker → 0

Feature scaling is performed using:

```python
StandardScaler
```

---

### 4. Feature Selection

### Input Features

```text
Age
BMI
Children
Gender
Smoking Status
```

### Target Variable

```text
Insurance Charges
```

---

### 5. Model Training

The project uses:

```python
Random Forest Regression
```

Random Forest Regression combines multiple decision trees to improve prediction accuracy and reduce overfitting.

---

### 6. Model Saving

The trained model is serialized and saved using Pickle.

```text
Finalized_RF_model.sav
```

---

### 7. Model Deployment

The trained Random Forest model is deployed using Streamlit.

Users can provide customer details and instantly predict medical insurance costs.

---

## Streamlit Application

The Streamlit application provides an interactive interface for insurance cost prediction.

### User Inputs

| Input | Description |
|---|---|
| Age | Customer age |
| BMI | Body Mass Index |
| Number of Children | Dependents count |
| Gender | Male / Female |
| Smoker | Smoking status |

---

### Application Output

```text
Predicted Medical Insurance Cost
```


---

## Run the Streamlit Application

```bash
streamlit run app.py
```

---

## Example Prediction Workflow

### Sample Inputs

| Feature | Example Value |
|---|---|
| Age | 47 |
| BMI | 33 |
| Children | 2 |
| Gender | Female |
| Smoker | No |

### Predicted Output

```text
8695.62
```

---

## Learning Outcomes

This project demonstrates practical understanding of:

- Random Forest Regression
- Ensemble learning
- Feature scaling
- Data preprocessing
- Streamlit deployment
- Interactive ML applications
- Machine Learning workflow
- Model serialization using Pickle

---

## Future Improvements

Potential enhancements for this project:

- Hyperparameter tuning
- Improve prediction accuracy
- Add model evaluation metrics
- Add visualization dashboards
- Deploy on cloud platforms
- Build REST API integration
- Improve user interface design

---

## Author

**MANIKANDAPRABHU.S**

Machine Learning and Artificial Intelligence Enthusiast

