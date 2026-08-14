# ❤️ Heart Attack Risk Prediction Using Machine Learning

## 📌 Project Overview

Heart Attack Risk Prediction is a Machine Learning project developed to predict the risk of heart disease based on various patient health and lifestyle attributes.

The project uses a **Support Vector Machine (SVM)** classification algorithm to predict whether a person is at risk of a heart attack. A **StandardScaler** is used to preprocess and scale the input features before passing them to the trained model.

This project demonstrates the complete Machine Learning workflow, including data preprocessing, exploratory data analysis, feature scaling, model training, evaluation, and prediction.

---

## 🎯 Objectives

* Predict the risk of heart attack using Machine Learning.
* Analyze important health and lifestyle factors associated with heart disease.
* Preprocess and clean the healthcare dataset.
* Apply feature scaling using StandardScaler.
* Train an SVM classification model.
* Evaluate the performance of the trained model.
* Save the trained model and scaler for future predictions.

---

## 📊 Dataset

The dataset contains approximately **7,000 patient records** with **22 features** related to health, lifestyle, and medical factors.

### Dataset Features

The dataset includes information such as:

* Age
* Gender
* Cholesterol
* Blood Pressure
* Heart Rate
* Diabetes
* Smoking
* Obesity
* Alcohol Consumption
* Exercise Habits
* Previous Heart Problems
* Medication Usage
* Stress Level
* Sedentary Hours
* BMI
* Triglycerides
* Physical Activity Days
* Sleep Hours
* Country
* Continent
* Hemisphere
* Heart Attack Risk

The target variable is:

**Heart Attack Risk**

---

## 🧠 Machine Learning Algorithm

### Support Vector Machine (SVM)

The project uses **Support Vector Machine (SVM)** as the primary classification algorithm.

SVM is a supervised Machine Learning algorithm commonly used for classification problems. It attempts to find an optimal decision boundary that separates different classes in the dataset.

In this project, SVM is used to classify patients based on their risk of heart attack.

---

## ⚙️ Data Preprocessing

The following preprocessing steps were performed:

1. Loaded the dataset.
2. Checked the dataset structure and data types.
3. Identified missing values.
4. Performed data cleaning.
5. Selected relevant features.
6. Separated input features and target variable.
7. Split the dataset into training and testing sets.
8. Applied feature scaling using **StandardScaler**.

Feature scaling is important for SVM because the algorithm is sensitive to differences in feature magnitudes.

---

## 🔬 Project Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Feature Selection
   ↓
Train-Test Split
   ↓
Feature Scaling
   ↓
SVM Model Training
   ↓
Model Evaluation
   ↓
Model & Scaler Saving
   ↓
Heart Attack Risk Prediction
```

---

## 🛠️ Technologies Used

* **Python**
* **Jupyter Notebook**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Scikit-learn**
* **Seaborn**
* **Pickle**
* **Machine Learning**
* **Support Vector Machine (SVM)**

---

## 📁 Project Structure

```text
Heart-Attack-Risk-Prediction/
│
├── Heart_Attack_Risk_Prediction.ipynb
├── heart_attack_prediction.csv
├── heart_attack_svm_model.pkl
├── heart_attack_scaler.pkl
└── README.md
```

### File Description

| File                                 | Description                                         |
| ------------------------------------ | --------------------------------------------------- |
| `Heart_Attack_Risk_Prediction.ipynb` | Complete Machine Learning project notebook          |
| `heart_attack_prediction.csv`        | Dataset used for training and testing               |
| `heart_attack_svm_model.pkl`         | Trained SVM Machine Learning model                  |
| `heart_attack_scaler.pkl`            | Saved StandardScaler used for feature preprocessing |
| `README.md`                          | Project documentation                               |

---

## 📈 Model Development

The Machine Learning model was developed using the following process:

### 1. Data Collection

A healthcare dataset containing approximately 7,000 records and 22 attributes was used.

### 2. Data Analysis

The dataset was analyzed to understand:

* Data types
* Missing values
* Feature distributions
* Target variable distribution
* Relationships between health factors and heart attack risk

### 3. Feature Engineering

Relevant numerical and categorical features were prepared for Machine Learning.

### 4. Data Splitting

The dataset was divided into training and testing data.

### 5. Feature Scaling

`StandardScaler` from Scikit-learn was used to standardize the input features.

### 6. Model Training

An SVM classifier was trained using the processed training dataset.

### 7. Model Evaluation

The model was evaluated using appropriate classification metrics.

---

## 📊 Model Evaluation

The trained model was evaluated using classification performance metrics such as:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

These metrics help determine how effectively the model classifies patients according to their predicted heart attack risk.

---

## 💾 Saved Model

The trained SVM model is saved using Python's Pickle module:

```text
heart_attack_svm_model.pkl
```

The feature scaler is also saved:

```text
heart_attack_scaler.pkl
```

These files can be loaded later without retraining the Machine Learning model.

---

## ▶️ How to Run the Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/Heart-Attack-Risk-Prediction.git
```

### Step 2: Navigate to the Project Folder

```bash
cd Heart-Attack-Risk-Prediction
```

### Step 3: Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Step 4: Start Jupyter Notebook

```bash
jupyter notebook
```

### Step 5: Open the Notebook

Open:

```text
Heart_Attack_Risk_Prediction.ipynb
```

Run the cells sequentially to reproduce the analysis and Machine Learning workflow.

---

## 🔮 Future Improvements

The project can be further improved by:

* Comparing multiple Machine Learning algorithms.
* Performing hyperparameter tuning.
* Improving feature engineering.
* Handling class imbalance if required.
* Using cross-validation.
* Deploying the model as a web application.
* Creating an interactive prediction interface.
* Deploying the application using Streamlit or Flask.
* Adding real-time patient risk prediction.

---

## ⚠️ Disclaimer

This project is developed for **educational and demonstration purposes only**.

The predictions generated by this Machine Learning model should **not be considered medical advice or a medical diagnosis**.

For any health concerns or medical decisions, consult a qualified healthcare professional.

---

## 👨‍💻 Author

**Asokan**

### Skills Demonstrated

* Python
* Machine Learning
* Data Analysis
* Data Preprocessing
* Exploratory Data Analysis
* Scikit-learn
* SVM Classification
* Model Evaluation
* Jupyter Notebook

---

## ⭐ Project Highlights

* ✔️ 7,000+ healthcare records
* ✔️ 22 dataset features
* ✔️ Data preprocessing and analysis
* ✔️ Feature scaling using StandardScaler
* ✔️ SVM classification
* ✔️ Model evaluation
* ✔️ Saved Machine Learning model
* ✔️ Saved feature scaler
* ✔️ Complete Jupyter Notebook workflow

---

## 📌 Conclusion

The **Heart Attack Risk Prediction Using Machine Learning** project demonstrates how Machine Learning can be applied to healthcare-related classification problems.

By preprocessing patient data, scaling features, and training an SVM classifier, the project provides a Machine Learning-based approach for predicting heart attack risk.

This project showcases practical skills in **Python, Data Analysis, Data Preprocessing, Machine Learning, Model Evaluation, and Model Deployment Preparation**.
