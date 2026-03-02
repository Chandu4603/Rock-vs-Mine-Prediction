# Rock-vs-Mine-Prediction
## 📌 Project Overview
1. The Rock vs Mine Prediction project is a supervised machine learning classification problem where the objective is to predict whether an object detected by a sonar signal is a Rock (R) or a Mine (M).
2. This project uses the Logistic Regression algorithm to build a binary classification model based on sonar signal frequency data.
3. The dataset contains sonar readings bounced off different surfaces. Each record has 60 numerical features representing energy at different frequency bands, and one target variable indicating whether the object is a rock or a mine.

## 🎯 Objective
To build and evaluate a machine learning model that can accurately classify underwater objects as:
R → Rock
M → Mine
using Logistic Regression.

## 📊 Dataset Information
Dataset Name: Sonar Dataset
- <a href = "https://github.com/Chandu4603/Rock-vs-Mine-Prediction/blob/main/Copy%20of%20sonar%20data.csv"> Data Set </a>

Total Features: 60 numeric attributes
- < a href = "https://github.com/Chandu4603/Rock-vs-Mine-Prediction/blob/main/Screenshot%202026-03-02%20193327.png"> Loaded DataSet </a>

Target Variable: Object Type (R/M)
Type: Binary Classification
Domain: Defense / Underwater Object Detection
Each feature represents the strength of sonar signal returns at different frequencies.

## 🛠️ Technologies & Tools Used
Python
NumPy
Pandas
Scikit-learn
Matplotlib / Seaborn (for visualization)
Jupyter Notebook

## 🔄 Project Workflow
Data Collection & Loading
Imported the sonar dataset.
Checked for missing values and data types.
- <img width="1761" height="726" alt="Screenshot 2026-03-02 193904" src="https://github.com/user-attachments/assets/51a41ecd-d405-423c-9116-c08991bf0cf9" />

Data Preprocessing
Converted categorical labels (R/M) into numeric format.
Split dataset into training and testing sets.
Model Building
- <img width="1802" height="591" alt="Screenshot 2026-03-02 194052" src="https://github.com/user-attachments/assets/f350a884-3f7a-463f-9bbc-22d1a32bf27f" />

Applied Logistic Regression algorithm.
Trained model on training dataset.
Model Evaluation
Calculated Accuracy Score.
Compared training and testing performance.
Evaluated model generalization ability.
Prediction System
Built a predictive system where new sonar readings can be provided as input.
Model predicts whether it is a Rock or a Mine.

## 🤖 Why Logistic Regression?
Suitable for binary classification problems
Simple yet powerful linear classifier
Provides probability-based predictions
Performs well on structured numerical data
- <img width="1802" height="591" alt="Screenshot 2026-03-02 194052" src="https://github.com/user-attachments/assets/b7670eb1-7fb6-4923-90c1-5a85b4b1f79c" />

## 📈 Results
Achieved high classification accuracy on test data.
Model successfully distinguishes between rock and mine signals.
Demonstrates practical application of logistic regression in real-world detection systems.
- <img width="1664" height="483" alt="Screenshot 2026-03-02 195629" src="https://github.com/user-attachments/assets/02a2e66e-73b2-4bbd-b59e-eb0eba04c3ff" />

## 💡 Key Learnings
Understanding binary classification problems
Data preprocessing and feature handling
Model training and evaluation
Building a real-time prediction system
Importance of avoiding overfitting


## 🌍 Real-World Applications
Naval mine detection systems
Submarine sonar analysis
Defense and underwater robotics
Signal classification systems
