# 🧠 Employee Attrition Prediction Using Machine Learning



<p align="center">
  <img src="https://img.shields.io/badge/Project-ML%20HR%20Attrition-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge">
  <img src="https://img.shields.io/badge/Model-XGBoost-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/Python-3.10-yellow?style=for-the-badge">
  <img src="https://img.shields.io/badge/ML-ScikitLearn-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Deployment-Ready-critical?style=for-the-badge">
</p>




# 🧠 Employee Attrition Prediction Using Machine Learning  
End-to-End HR Analytics Project | Classification | EDA → Preprocessing → Modeling → Deployment

## 📌 Project Overview  
This project focuses on predicting **employee attrition** (whether an employee will leave the company) using the famous **IBM HR Analytics dataset**.  
The goal is to help HR teams identify key factors that lead to attrition and provide data-driven insights for better decision-making.

The workflow includes:
- Exploratory Data Analysis (EDA)
- Data Cleaning & Preprocessing Pipeline
- Feature Engineering
- Training Machine Learning Models (DT, RF, GB, XGBoost)
- Saving Models using Pickle
- Deployment-ready Preprocessing & Model Files

---

```mermaid
flowchart LR

A[📂 Raw HR Data] --> B[🧹 Data Cleaning]
B --> C[📊 EDA & Visualization]
C --> D[⚙️ Preprocessing Pipeline<br/>Encoding • Scaling • Transformation]
D --> E[🤖 Model Training<br/>DT / RF / GB / XGBoost]
E --> F[🏆 Model Selection & Evaluation]
F --> G[💾 Save Model & Preprocessing<br/>model.pkl • preprocessing.pkl]
G --> H[🚀 Deployment Ready]
 
