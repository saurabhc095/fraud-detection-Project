# Credit Card Fraud Detection – Final Project

##  Project Overview
This project focuses on detecting fraudulent transactions using supervised machine learning. It involves data cleaning, exploratory data analysis (EDA), feature selection, model training and evaluation, and Power BI dashboard reporting.

The original dataset contains anonymized credit card transactions, and the goal is to accurately classify transactions as fraudulent (1) or legitimate (0).

---

##  Project Structure

Fraud_Detection_Project/
│
├── 03_notebooks/              # Jupyter notebooks (Week 1 to Week 4)
├── 04_Final Report/           # Project report DOCX & PDF
├── 05_visuals/                # Exported graphs and charts
├── 06_Power BI/               # Power BI dashboard files (.pbix, .pdf)
├── .gitignore                 # Git ignore file for large CSVs
├── README.md                  # Project overview and instructions
└── requirements.txt           # Python dependencies

---

## Key Highlights

- **Data Cleaning** – Removed missing values and irrelevant columns.
- **Feature Engineering** – Selected important features using correlation and SelectKBest.
- **Modeling** – Trained Logistic Regression, Decision Tree, and Random Forest models.
- **Imbalance Handling** – Used SMOTE to balance the dataset.
- **Evaluation** – Compared models using Accuracy, Precision, Recall, F1-score, and ROC-AUC.
- **Reporting** – Final results visualized using an interactive Power BI dashboard.

---

##  Best Performing Model

> **Random Forest Classifier**  
- Accuracy: **99.94%**  
- Precision: **90%**  
- Recall: **78%**  
- F1 Score: **83%**  
- AUC Score: **0.96**

---

## Dataset Access (via Google Drive)

To keep GitHub lightweight, large CSV files are hosted externally.  
 [Download Processed Dataset](https://drive.google.com/file/d/1kiZSAyY3WrWSLIQD3CgT2ZmmRBFLhFzx/view?usp=sharing)

---

## Tools and Technologies

- **Python** (pandas, numpy, matplotlib, seaborn, scikit-learn, imblearn)
- **Jupyter Notebook**
- **Power BI Desktop**
- **SMOTE (Synthetic Minority Over-sampling Technique)**

---

##  Author

- **Name:** *Saurabh Chaturvedi*  
- **Internship:** Outsource360 – Data Science Internship  
- **Date:** July 2025

---

##  License

This project is developed as part of an academic internship and is intended for educational and presentation purposes.
