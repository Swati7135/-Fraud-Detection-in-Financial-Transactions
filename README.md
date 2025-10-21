# Fraud-Detection-in-Financial-Transactions
This project was completed as part of my internship at **Codec Technologies**. The goal of the project was to identify suspicious or fraudulent transactions in financial datasets and create an interactive, alert-based dashboard to help monitor potential fraud in real-time.
### 🎯 Goals
- Detect fraudulent transactions in financial datasets

- Perform anomaly detection using Isolation Forest and AutoEncoders

- Handle class imbalance using SMOTE

- Create alert-based dashboards for monitoring high-risk transactions

### 📊 Dataset

- Source: Anonymized financial transaction data

- Features: Time, V1–V28 (PCA components), Amount, Class, Risk Score, Risk Level

- Rows: 284,807 transactions

- Fraud Rate: 0.172%

### 🛠 Technologies Used

- Programming: Python 3.8+

- ML Libraries: Scikit-learn, TensorFlow, Imbalanced-learn

- Visualization: Matplotlib, Seaborn, Power BI

- Models: Isolation Forest, AutoEncoder, Random Forest

### 🚀 Installation & Usage
### 1. Install Dependencies
pip install -r requirements.txt

#### 2. Run Analysis
jupyter notebook notebooks/fraud_dectection.ipynb

### 3. Open Dashboard

Open dashboards/fraud_detection_dashboard.pbix in Power BI Desktop

### 📈 Models Implemented

- Isolation Forest – Unsupervised anomaly detection for outliers

- AutoEncoder – Neural network reconstruction error indicates fraud

- Random Forest – Supervised learning with SMOTE for class imbalance

### 📊 Power BI Dashboard Features

- Overview Page: Total transactions, fraud metrics, average risk

- Alert Dashboard: High-risk transaction alerts with conditional formatting

- Analysis Page: Hourly fraud patterns, transaction type distribution, risk-level breakdown.

 ### 🔧 Key Features

- Data Preprocessing: Missing values, feature scaling

- Class Imbalance: SMOTE for balancing dataset

- Anomaly Detection: Isolation Forest + AutoEncoder

- Alert System: Real-time alerts based on risk level & score

- Interactive Dashboard: Hourly fraud rate, transaction types, alerts visualization

### 📄 Results (Sample)
| Model            | Precision | Recall | F1-Score |
|-----------------|-----------|--------|----------|
| Isolation Forest | 0.85      | 0.78   | 0.81     |
| AutoEncoder      | 0.82      | 0.85   | 0.83     |
| Random Forest    | 0.89      | 0.92   | 0.90     |
