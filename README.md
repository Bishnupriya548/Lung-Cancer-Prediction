# Lung-Cancer-Prediction
🫁 Lung Cancer Prediction Using Machine Learning
📌 Project Overview

This project focuses on predicting lung cancer risk using machine learning techniques based on medical and lifestyle attributes. The goal is to analyze patterns in the data, perform exploratory data analysis (EDA), and compare multiple machine learning models to identify the most effective approach for classification.


🎯 Objectives

Perform exploratory data analysis (EDA) to understand data distribution and feature relationships

Build and compare multiple machine learning models

Evaluate model performance and identify the best-performing algorithm

Analyze feature importance contributing to lung cancer prediction

📊 Dataset Description

The dataset contains structured medical and lifestyle information, including:

Gender

Age

Smoking

Yellow fingers

Anxiety

Peer pressure

Chronic disease

Fatigue

Allergy

Wheezing

Alcohol consumption

Coughing

Shortness of breath

Swallowing difficulty

Chest pain

Target Variable:

LUNG_CANCER (YES / NO)

🧪 Exploratory Data Analysis (EDA)

The following analyses were performed:

Distribution of lung cancer cases

Age comparison between cancer and non-cancer patients

Impact of smoking and chest pain on lung cancer

Correlation heatmap to identify influential features

EDA helped validate feature relevance and supported model selection.

🧠 Machine Learning Models Used
Model	Purpose
Linear Regression	Baseline analysis and feature relationship understanding
Logistic Regression	Binary classification of lung cancer risk
Random Forest Classifier	Final high-accuracy predictive model
📈 Model Performance

Logistic Regression Accuracy: ~85–90%

Random Forest Accuracy: ~90–95%

Random Forest performed best due to its ability to capture non-linear feature interactions

Feature importance analysis highlighted smoking, chest pain, and breathing difficulty as key predictors

🛠️ Technologies Used

Python

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn
