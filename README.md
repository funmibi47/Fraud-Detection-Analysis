# Fraud Detection Project — Technical Documentation Version

A machine learning project built to analyze financial transactions and detect potential fraud. This repository contains the dataset, preprocessing steps, exploratory data analysis (EDA), feature engineering, model training, and evaluation.

---

## 📌 Project Overview (Technical)

Fraud detection helps identify suspicious financial transactions using machine learning techniques. This project walks through:

* Data cleaning
* Exploratory Data Analysis (EDA)
* Feature engineering
* Model development
* Performance evaluation

The notebook included demonstrates the full workflow using real transactional data.

---

## 📂 Repository Structure

```
├── Fraud Detection.ipynb     # Full analysis & model building notebook
└── README.md                 # Project documentation
```

---

## 🔧 Tools & Technologies

* **Python**
* **Pandas** and **NumPy** (Data processing)
* **Matplotlib** and **Seaborn** (Visualization)
* **Scikit-learn** (Machine learning)

---

## 📊 Key Steps in the Notebook

### 1. **Data Loading & Inspection**

* Preview dataset structure
* Check missing values
* Analyze fraud distribution

### 2. **Exploratory Data Analysis (EDA)**

* Transaction type distribution
* Fraud rate per transaction type
* Relationship between amount, balance changes, and fraud

### 3. **Feature Engineering**

* Balance difference calculations
* Transformations 
* Encoding categorical features

### 4. **Model Development**

* Train/test split
* Model training 
* Performance evaluation: accuracy, precision, recall

### 5. **Results & Insights**

* Which features matter most?
* Which transaction types are most risky?
* Model performance summary

---


## 📝 Notes

* The dataset may contain millions of rows. Running the notebook may require sufficient RAM.
* All visualizations and analyses are explained step-by-step inside the notebook.
---

