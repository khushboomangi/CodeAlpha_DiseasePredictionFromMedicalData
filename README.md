# Disease Prediction from Medical Data — CodeAlpha Machine Learning Task 4

## 📌 Project Overview
This project builds a Machine Learning model to predict the presence of disease based on clinical patient parameters (such as blood pressure, cholesterol levels, chest pain type, and maximum heart rate). The model assists healthcare practitioners in early risk detection and clinical decision-making.

## 🛠️ Tech Stack & Libraries
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn

## 📊 Workflow
1. **Clinical Data Synthesis & Loading:** Generated benchmark clinical patient records with key health features.
2. **Feature Scaling:** Standardized numerical clinical features using `StandardScaler`.
3. **Model Training:** Trained a `RandomForestClassifier` on 80% of the dataset.
4. **Evaluation:** Evaluated performance using Accuracy, ROC-AUC Score, Confusion Matrix, and Feature Importance analysis.

## 📈 Key Findings
- **High Predictive Performance:** Strong classification metrics for risk detection.
- **Top Clinical Factors:** Features like chest pain type, max heart rate, and cholesterol levels were identified as key drivers for risk classification.

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/CodeAlpha_DiseasePredictionFromMedicalData.git](https://github.com/YOUR_USERNAME/CodeAlpha_DiseasePredictionFromMedicalData.git)