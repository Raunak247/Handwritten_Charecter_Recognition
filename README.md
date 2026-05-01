# Disease Prediction from medical data

# Disease Prediction Model

This project predicts the presence of a disease based on medical data.

## 📌 Overview
A machine learning model is trained using structured patient data like medical test results.

0 -> Malignant
1 -> Benign

## ⚙️ Approach
- Removed missing values
- Split dataset into training and testing sets
- Used Random Forest classifier

## 📊 Evaluation
Accuracy: 0.956140350877193


              precision    recall  f1-score   support

           0       0.95      0.93      0.94        43
           1       0.96      0.97      0.97        71

    accuracy                           0.96       114
   macro avg       0.96      0.95      0.95       114
weighted avg       0.96      0.96      0.96       114

## 🛠️ Technologies Used
- Python
- Pandas
- Scikit-learn

## ▶️ How to Run
1. Place the dataset file (`disease_data.csv`) in the same folder  
2. Run:
