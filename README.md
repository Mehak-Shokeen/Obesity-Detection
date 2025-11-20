# 🌟 Obesity Level Detection using Machine Learning
A machine learning project that predicts 7 different obesity levels based on lifestyle, nutritional, and physical health indicators. Built using Python, Scikit-learn, and Jupyter Notebook.

## 🚀 Project Overview
This project focuses on analyzing health and lifestyle habits to classify individuals into obesity categories such as:

● Insufficient Weight <br>
● Normal Weight <br>
● Overweight Level I & II <br>
● Obesity Type I, II & III <br>

The dataset used contains a mix of dietary habits, physical activity levels, consumption patterns and basic physical measurements.
The model uses only numeric health metrics, standardized using StandardScaler for accurate classification.

## 📊 Dataset Features
Numeric features used (model inputs):

● Age <br>
● Height <br>
● Weight <br>
● FCVC — Vegetable consumption frequency <br>
● NCP — Number of daily meals <br>
● CH2O — Daily water intake <br>
● FAF — Physical activity frequency <br>
● TUE — Time spent on technology <br>

**Target label: NObeyesdad (7 obesity categories)**

## Models Used

The following algorithms were trained and compared:
| Model                   | Accuracy |
|-------------------------|----------|
| Logistic Regression     | 88.42%   |
| K-Nearest Neighbors     | 82.03%   |
| Decision Tree           | 92.91%   |
| Support Vector Machine  | 95.27%   |
| Random Forest           | 95.27%   |

**🔥 Best models: SVM & Random Forest**

## 📌 Future Improvements
● Add categorical encoding <br>
● Use full dataset features <br>
● Implement deep learning models <br>
● Build a Streamlit / Flask app <br>
● Deploy as API <br>
