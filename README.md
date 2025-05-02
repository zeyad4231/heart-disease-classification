# 🫀 Heart Disease Classification

This project uses machine learning to classify whether a patient is likely to have heart disease based on clinical data. The dataset contains features like age, sex, chest pain type, blood pressure, cholesterol levels, and more.

## 📁 Files

- `end-to-end-heart-disease-classification.ipynb`: Main Jupyter notebook with all code and analysis
- `heart-disease.csv`: Dataset used in the project

## 🚀 Project Highlights

- Explored the dataset using visualizations and correlations
- Preprocessed data and handled categorical features
- Trained multiple classification models:
  - Logistic Regression
  - K-Nearest Neighbors
  - Random Forest
  - Support Vector Machines
- Tuned hyperparameters using `GridSearchCV`
- Evaluated models using:
  - Accuracy, Precision, Recall, F1-score
  - Confusion Matrix
  - Cross-validation
  - ROC Curve & AUC Score
- Selected the best-performing model based on metrics

## 🛠 Technologies

- Python
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## 📈 Results

Logistic Regression with tuned hyperparameters performed best in terms of balanced accuracy and interpretability.

## ✅ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/zeyad4231/heart-disease-classification.git

   cd heart-disease-classification
jupyter notebook end-to-end-heart-disease-classification.ipynb

