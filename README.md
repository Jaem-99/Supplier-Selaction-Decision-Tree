# 🏢 Supplier Selection & Decision Support System (AI-Powered)
An automated machine learning pipeline built to evaluate and classify potential suppliers using a Decision Tree Classifier, integrating core supply chain metrics to optimize vendor selection decisions.

## 📊 Project Overview
Selecting the right supplier is critical for operational efficiency and risk mitigation. This project replaces manual, subjective evaluations with a data-driven classification model. The system evaluates vendors based on four key performance indicators and automatically classifies them into **Approved** or **Rejected**.

## ⚙️ Key Features
External Data Ingestion: Modular pipeline that ingests clean dataset structures via external `.csv` files (`pd.read_csv`).
Machine Learning Model:Implements a `DecisionTreeClassifier` from `scikit-learn` for binary classification.
Explainable AI (XAI): Generates clear, intuitive visual decision trees (`matplotlib` & `scikit-learn.tree`) allowing stakeholders to interpret the exact decision rules.
Performance Validation: Validates model accuracy and generalization using train/test splits.

## 📐 Evaluated Metrics (Features)
1. Quality: Product/service quality score.
2. TCO (Total Cost of Ownership): Cost efficiency and pricing competitiveness.
3. Lead Time: Delivery speed and operational reliability.
4. Financial:Financial stability and risk assessment score.
5. Target: Final decision label (`1` = Approved, `0` = Rejected).

## 🛠️ Tech Stack
Language: Python 3.x
Libraries:Pandas, NumPy, Scikit-Learn, Matplotlib
Environment: Google Colab
Version Control:Git / GitHub
