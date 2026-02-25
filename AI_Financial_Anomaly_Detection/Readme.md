# 💰 AI-Driven Financial Anomaly Detection Dashboard

## 📌 Project Overview

This project builds an AI-powered anomaly detection system to identify suspicious financial transactions and visualize risk insights using Power BI.

It combines Machine Learning, Data Analysis, and Business Intelligence to simulate a real-world fraud detection system.

---

## 🎯 Business Problem

Financial institutions face revenue loss due to fraudulent or abnormal transactions.

The objective of this project was to:

- Detect unusual transaction patterns
- Classify transactions as Normal or Anomalous
- Visualize risk insights in an interactive dashboard
- Support data-driven fraud monitoring

---

## 🗂 Dataset Description

The dataset includes:

- Transaction ID
- Transaction Amount
- Customer ID
- Transaction Type
- Timestamp
- Account Balance
- Fraud Label (if available)

---

## 🛠 Technologies Used

- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib
- Power BI
- Machine Learning (Isolation Forest / Logistic Regression)

---

## ⚙️ Project Workflow

### 1️⃣ Data Preprocessing
- Missing value handling
- Feature engineering
- Data normalization
- Outlier inspection

### 2️⃣ Model Development
- Isolation Forest for anomaly detection
- Logistic Regression (if supervised)
- Train-test split
- Hyperparameter tuning

### 3️⃣ Model Evaluation
- Confusion Matrix
- Accuracy Score
- Precision & Recall
- ROC Curve

### 4️⃣ Dashboard Development
- Risk Score KPI
- Fraud Transaction Count
- Anomaly Distribution
- Time-based Risk Trend
- High-Risk Customer Identification

---

## 📊 Key Insights

- A small percentage of transactions were classified as high-risk.
- High-value transactions had greater anomaly probability.
- Certain transaction types were more prone to fraud patterns.
- Time-based analysis revealed periodic spikes.

---

## 📈 Business Impact

This system can help financial institutions:

- Reduce fraud losses
- Improve transaction monitoring
- Automate anomaly detection
- Enhance risk management strategies

---

## 📂 Repository Structure

AI-Financial-Anomaly-Detection/
│
├── data/
│   └── financial_transactions.csv
│
├── notebooks/
│   └── model_training.ipynb
│
├── src/
│   ├── data_preprocessing.py
│   ├── model_training.py
│   └── evaluation.py
│
├── dashboard/
│   ├── PowerBI_Dashboard.pbix
│   └── Dashboard_Screenshot.png
│
├── models/
│   └── anomaly_model.pkl
│
├── reports/
│   ├── Confusion_Matrix.png
│   └── ROC_Curve.png
│
└── README.md


---

## 📷 Model Evaluation

![](JupyterNotebook-Screenshot-1.png)
![](JupyterNotebook-Screenshot-2.png)
![](JupyterNotebook-Screenshot-3.png)
![](JupyterNotebook-Screenshot-4.png)
![](JupyterNotebook-Screenshot-5.png)

---

## 📷 Dashboard Preview

 ![Dashboard](Dashboard.png)

---

## 🚀 Future Improvements

- Real-time anomaly detection
- Deployment using Flask or FastAPI
- Integration with live transaction streams
- Model performance optimization

---

## 👨‍💻 Author

Faraz Niyazi  
Data Analyst | Machine Learning Enthusiast  
Excel | SQL | Power BI | Python

