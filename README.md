# Heart Disease Prediction using Machine Learning

This project predicts the presence of heart disease using three machine learning models: Decision Tree, Random Forest, and Support Vector Classifier (SVC). The dataset is from the UCI Machine Learning Repository.

## 📁 Files Included
- `Heart Disease.ipynb` – Jupyter Notebook with full data cleaning, EDA, model building, and evaluation.
- `Heart Disease.pptx` – Presentation summarizing the project insights and results.

## 📊 Dataset
- Source: UCI ML Repo (id=45)
- 303 samples, 13 features
- Target: Presence of heart disease (Num: 0–4)

## 🛠️ Models Used
- Decision Tree
- Random Forest ✅ (Best Performing Model)
- Support Vector Classifier

## ⚙️ Accuracy Summary
| Model          | Accuracy | F1 Score |
|----------------|----------|----------|
| Decision Tree  | 75–80%   | 75–80%   |
| Random Forest  | 80–85%   | 80–85%   |
| SVC            | 80–85%   | 80–85%   |

## ✅ Best Model: Random Forest
- Handles outliers and noisy data well
- Less prone to overfitting
- Provides feature importance

## 🔍 Confusion Matrix (Random Forest)
- True Positives (TP): 53
- True Negatives (TN): 45
- False Positives (FP): 5
- False Negatives (FN): 7

## 📌 Conclusion
Random Forest performed the best overall. This project highlights how proper preprocessing, EDA, and model selection can lead to reliable predictions in healthcare analytics.

