📌 Project Overview

Fraud detection is a critical issue in financial systems. This project uses data analysis and machine learning models to:

Understand transaction patterns

Visualize fraud-related trends

Engineer useful features

Train a classification model

Evaluate model performance

The analysis and modelling are implemented in the Jupyter notebook:
📄 Fraud Detection.ipynb

📂 Dataset

The dataset contains millions of transaction records with features such as:

type – Transaction type (e.g., TRANSFER, CASH_OUT)

amount – Transaction amount

oldbalanceOrg / newbalanceOrg – Sender balances

oldbalanceDest / newbalanceDest – Receiver balances

isFraud – 1 if fraud, 0 otherwise

isFlaggedFraud – System-flagged fraud

New engineered features include:

balanceDiffOrig – Difference in sender balance

balanceDiffDest – Difference in receiver balance

🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn (for ML model-building)

🔍 Key Steps in the Notebook
1. Data Loading & Inspection

Loaded dataset with pandas

Viewed first/last rows

Checked missing values

Analyzed fraud distribution

2. Exploratory Data Analysis (EDA)

Histogram of transaction amounts

Bar charts of transaction types

Fraud rate per transaction type

Boxplots to compare fraud vs non-fraud

3. Feature Engineering

Created new features to improve model accuracy, such as balance differences.

4. Model Training

Split data into training/testing sets

Trained classification models

Evaluated accuracy, precision, recall, and F1-score

5. Insights

Fraud is very rare in the dataset

Certain transaction types have higher fraud rates

Balance differences help identify suspicious transactions

📊 Visualizations

The notebook contains several charts including:

Transaction type distribution

Fraud rate by type

Log-scaled amount distribution

Boxplots of fraud vs amount

These visualizations help reveal important fraud patterns.

🤝 Contributing

Pull requests and suggestions are welcome!
