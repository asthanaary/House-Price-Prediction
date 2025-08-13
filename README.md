# House Price Prediction

A Machine Learning project to predict house prices based on property features such as area, number of rooms, and location.  
Built with **Python**, **scikit-learn**, and **XGBoost**.

---

##  Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Installation](#installation)

---

##  Overview
This project estimates house prices using supervised learning models.  
The workflow includes:
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Model training and tuning
- Predictions on new data

---

##  Features
- Data cleaning and preprocessing  
- Multiple models: Linear Regression, Random Forest, XGBoost  
- Performance evaluation (RMSE, MAE, R²)  
- Saved trained models for reuse  

---

##  Project Structure
House-Price-Prediction/
├── data/ # Dataset files
├── notebooks/ # Jupyter notebooks for EDA & experiments
├── src/ # Training & prediction scripts
├── models/ # Saved models
├── results/ # Metrics and plots
├── requirements.txt # Dependencies
└── README.md

yaml
Copy
Edit

---

##  Installation
Clone the repository:
```bash
git clone https://github.com/<your-username>/House-Price-Prediction.git
cd House-Price-Prediction
pip install -r requirements.txt
