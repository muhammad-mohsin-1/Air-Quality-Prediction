# 🌫️ Air Quality Analysis & Prediction System

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1yGyTWtxqfxOp_xCguy8PAWA6f-xMJVA9#scrollTo=P_QH1gqjCDTE)
[![Kaggle Dataset](https://img.shields.io/badge/Dataset-Kaggle-blue.svg)](https://www.kaggle.com/datasets/khushikyad001/air-quality-data)

## 📌 Project Overview
This project focuses on analyzing environmental data to predict air pollution levels (**Low, Medium, High**). We implemented and compared **7 different Machine Learning Algorithms** to identify the most accurate model for air quality classification.

The project demonstrates the complete Data Science workflow: Data Cleaning, Preprocessing, Model Training, Evaluation, and Comparison.

## 📂 Dataset Details
- **Source:** [Air Quality Data (Kaggle)](https://www.kaggle.com/datasets/khushikyad001/air-quality-data)
- **Features:** The dataset includes sensor readings for CO, NOx, Temperature, Humidity, and other chemical concentrations.
- **Target:** `Pollution_Level` (Categorized based on Air Quality Index).

## 🤖 Algorithms Implemented
We trained the following models to classify pollution levels:
1. **Logistic Regression**
2. **Decision Tree Classifier**
3. **Random Forest Classifier (🏆 Winner)**
4. **K-Nearest Neighbors (KNN)**
5. **Support Vector Machine (SVM)**
6. **Linear Regression** (Adapted for classification analysis)
7. **Artificial Neural Network (ANN / MLP)**

## 📊 Performance Comparison
After testing on a 20% test split, here are the final evaluation metrics:

| Algorithm | Accuracy | Precision | Recall | F1-Score |
|-----------|----------|-----------|--------|----------|
| **Random Forest** | **80.50%** | **0.65** | **0.81** | **0.72** |
| Logistic Regression | 80.50% | 0.65 | 0.81 | 0.72 |
| SVM | 80.50% | 0.65 | 0.81 | 0.72 |
| Linear Regression | 80.25% | 0.65 | 0.80 | 0.72 |
| KNN | 78.75% | 0.66 | 0.79 | 0.71 |
| ANN (Neural Network) | 70.50% | 0.67 | 0.70 | 0.69 |
| Decision Tree | 64.12% | 0.64 | 0.64 | 0.65 |

> **Observation:** While Logistic Regression, SVM, and Random Forest achieved similar accuracy, **Random Forest** provided the most stable performance across different metrics and is robust against overfitting compared to Decision Trees.

## 🏆 Final Verdict
**Random Forest Classifier** is selected as the best model for this project due to its ensemble nature, high accuracy (**80.50%**), and ability to handle complex data patterns effectively.

## ⚙️ How to Run
1. Click the **"Open in Colab"** button at the top of this file.
2. Download the dataset from the Kaggle link provided above.
3. Upload the `AirQualityData.csv` file to the Colab session.
4. Go to **Runtime > Run all** to execute the project.

---

## 👨‍💻 Project Team
**Developed By:**
* **Muhammad Mohsin**
* **Usman Siddique**
* *(5th Semester Students)*

**Submitted To:**
* **Sir Awais Rasool**