# Intrusion Detection System using Machine Learning (UNSW-NB15)

This project applies Machine Learning techniques to detect cyber attacks using the UNSW-NB15 dataset. It includes model training using XGBoost, Random Forest, and ANN, along with performance visualization.

## 📂 Files
- `UNSW_NB15_Code_Final.ipynb`: Full pipeline from preprocessing to model evaluation.
- `UNSW_NB15_training-set.csv` / `UNSW_NB15_testing-set.csv`: Datasets used for model training and testing.
- `UNSW_NB15_Report.pdf`: Complete report and evaluation of the models.

## 🚀 Features
- Classifies network traffic as **normal** or **malicious**.
- Supports three ML models: **XGBoost**, **Random Forest**, and **ANN**.
- Handles class imbalance using **SMOTE**.
- Provides **ROC curves**, **Confusion Matrices**, and **Feature Importance** plots.

## 🧠 Tools & Technologies
- Python, Pandas, Scikit-learn, XGBoost, TensorFlow/Keras, Seaborn, Matplotlib

## 📈 Model Performance
- Best Accuracy: **93.66%** (Random Forest)
- Best AUC: **0.986** (ANN)

## 👨‍💻 Run the Notebook
1. Clone this repository.
2. Install dependencies using `pip install -r requirements.txt`
3. Open the notebook:  
   ```bash
   jupyter notebook UNSW_NB15_Code_Final.ipynb
