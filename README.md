# ✈️ Airline Customer Satisfaction Prediction using XGBoost

![Python](https://img.shields.io/badge/Python-3.9-blue)
![Status](https://img.shields.io/badge/Project-Active-brightgreen)

## 📌 Project Overview

This project focuses on predicting customer satisfaction in the airline industry using a dataset of 129,000+ records. The objective is to build a machine learning model using **XGBoost** to classify whether a customer is satisfied or not based on various service and demographic features.

---

## 🎯 Objectives

- Perform Exploratory Data Analysis (EDA)
- Clean and preprocess the dataset
- Build a classification model using **XGBoost**
- Evaluate the model using relevant metrics
- Interpret feature importance to understand key drivers of satisfaction

---

## 🗃️ Dataset Summary

| Column Name                         | Description                              |
|------------------------------------|------------------------------------------|
| `satisfaction`                     | Target variable: Satisfied / Not Satisfied |
| `Gender`, `Customer Type`          | Demographic attributes                   |
| `Age`, `Flight Distance`           | Numerical features                       |
| `Type of Travel`, `Class`          | Travel context                           |
| `Seat comfort`, `Online support`, `Cleanliness`, etc. | Service ratings (1–5) |
| `Departure Delay in Minutes`, `Arrival Delay in Minutes` | Flight punctuality |

---

## 🔧 Tools & Technologies

- **Python 3.9+**
- **Jupyter Notebook**
- **Pandas**, **NumPy** – Data handling
- **Matplotlib**, **Seaborn** – Data visualization
- **XGBoost** – Model training
- **Scikit-learn** – Model evaluation and preprocessing

---


---

## ⚙️ Model Building with XGBoost

### ✅ Steps:

1. Encode categorical features (`Gender`, `Customer Type`, etc.)
2. Handle missing values (e.g., `Arrival Delay in Minutes`)
3. Split the dataset into training and test sets
4. Train **XGBoost Classifier**
5. Evaluate model using:
   - Accuracy
   - Precision, Recall, F1-score
6. Analyze **feature importance**

---

## 💡 Key Insights

- Long flight delays significantly reduce satisfaction
- Service quality features like `Seat comfort`, `Inflight entertainment`, and `On-board service` are highly important
- Business class travelers are generally more satisfied

---


