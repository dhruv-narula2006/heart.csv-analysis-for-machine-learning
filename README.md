# ❤️ Heart Disease Data Analysis & Preprocessing

A complete **Data Analysis and Preprocessing project** based on a heart disease dataset. The project focuses on understanding the dataset through **Exploratory Data Analysis (EDA), data cleaning, preprocessing, feature engineering, and feature selection** to prepare the data for Machine Learning.

## 📌 Project Overview

The objective of this project is to transform raw heart disease data into a **clean, structured, and machine-learning-ready dataset**.

The complete workflow includes:

```text
Raw Dataset
     ↓
Exploratory Data Analysis
     ↓
Data Cleaning
     ↓
Data Preprocessing
     ↓
Feature Engineering
     ↓
Feature Selection
     ↓
Machine Learning Ready Dataset
```

## 📊 Dataset

The dataset contains **918 records and 12 features**.

### Target Variable

* `HeartDisease` — Target variable indicating the presence of heart disease.

### Features

| Feature          | Description                           |
| ---------------- | ------------------------------------- |
| `Age`            | Age of the patient                    |
| `Sex`            | Gender of the patient                 |
| `ChestPainType`  | Type of chest pain                    |
| `RestingBP`      | Resting blood pressure                |
| `Cholesterol`    | Cholesterol level                     |
| `FastingBS`      | Fasting blood sugar indicator         |
| `RestingECG`     | Resting ECG results                   |
| `MaxHR`          | Maximum heart rate achieved           |
| `ExerciseAngina` | Exercise-induced angina               |
| `Oldpeak`        | ST depression                         |
| `ST_Slope`       | Slope of the peak exercise ST segment |
| `HeartDisease`   | Target variable                       |

## 🔍 Exploratory Data Analysis

The EDA phase focuses on understanding the structure, distribution, and relationships within the dataset.

### Analysis Performed

* Dataset shape and structure
* Data types
* Descriptive statistics
* Missing-value analysis
* Duplicate-value analysis
* Target variable distribution
* Numerical feature distributions
* Categorical feature analysis
* Outlier detection
* Correlation analysis
* Relationship between features and target variable

### 📈 Visualizations

The project uses:

* 📊 Histograms
* 📦 Box plots
* 📊 Count plots
* 📈 Bar charts
* 🔵 Scatter plots
* 🔥 Correlation heatmaps

## 🧹 Data Cleaning

The dataset was checked and cleaned before applying further preprocessing techniques.

### Steps Include

* Checking missing values
* Checking duplicate records
* Identifying invalid values
* Checking data types
* Detecting potential outliers
* Removing unnecessary or redundant information

## ⚙️ Data Preprocessing

The preprocessing stage converts the raw dataset into a format suitable for Machine Learning.

### Categorical Data

Categorical variables such as:

* `Sex`
* `ChestPainType`
* `RestingECG`
* `ExerciseAngina`
* `ST_Slope`

are transformed into numerical representations using appropriate encoding techniques.

### Numerical Data

Numerical features are analyzed and transformed where required.

Depending on the modeling approach, preprocessing may include:

* Feature scaling
* Standardization
* Outlier treatment
* Numerical transformations

## 🛠️ Feature Engineering

Feature engineering is performed to improve the quality and usefulness of the input variables.

The process includes:

* Creating meaningful derived features
* Transforming existing features
* Converting categorical information into useful numerical features
* Examining relationships between variables
* Preparing features for model development

## 🎯 Feature Selection

Feature selection is used to identify the most relevant variables for Machine Learning.

Techniques explored include:

* Correlation analysis
* Removing highly correlated features
* Statistical analysis
* Feature importance
* Removing irrelevant or redundant features

The objective is to reduce unnecessary features while retaining the information most useful for predicting `HeartDisease`.

## 🧰 Technologies & Libraries

<p align="center">

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white">
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white">
<img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white">
<img src="https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge">
<img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white">

</p>

### Development Tools

`Jupyter Notebook` • `Spyder` • `VS Code` • `Git` • `GitHub`

## 📂 Project Structure

```text
Heart-Disease-Analysis/
│
├── heart.csv
├── heart.ipynb
├── requirements.txt
└── README.md
```

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/sharmavinay9932-cse/heart.csv-analysis-for-machine-learning
```

### 2. Navigate to the project

```bash
cd Heart-Disease-Analysis
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the notebook

```bash
jupyter notebook
```

Open `heart_disease_analysis.ipynb` and run the notebook cells sequentially.

## 📚 Concepts Practiced

Through this project, I practiced:

* Exploratory Data Analysis
* Data Cleaning
* Missing Value Analysis
* Duplicate Detection
* Outlier Analysis
* Data Visualization
* Categorical Encoding
* Feature Engineering
* Feature Selection
* Correlation Analysis
* Data Preprocessing
* Preparing datasets for Machine Learning

## 🔮 Future Improvements

* Train Machine Learning classification models
* Compare multiple algorithms
* Perform hyperparameter tuning
* Apply cross-validation
* Evaluate model performance using appropriate metrics
* Build a complete Machine Learning pipeline
* Deploy the final model as a web application

## 🎯 Learning Outcome

This project helped me understand the complete **data preprocessing workflow** required before building a Machine Learning model.

The main focus was:

**EDA → Cleaning → Preprocessing → Feature Engineering → Feature Selection**

---

## 👨‍💻 Author

**Vinay Sharma**

B.Tech CSE — Artificial Intelligence & Machine Learning

**GitHub:** `sharmavinay9932-cse`

**Email:** `sharmavinay9932@gmail.com`

---

⭐ If you found this project useful, consider giving the repository a star!
