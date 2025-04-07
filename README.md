# Heart Failure Ensemble Classification - ALDA Project

This project explores the performance of different ensemble machine learning models—specifically homogeneous and heterogeneous ensembles on the Heart Failure Prediction Dataset. Our goal is to determine whether combining multiple base classifiers of different types (e.g., Decision Tree + KNN) leads to better predictive performance than using ensembles of a single classifier type.

## 📦 Setup Instructions

Follow these steps to set up your virtual environment and install dependencies:

### 1. Create and activate a virtual environment
```bash
python -m venv venv
```
Windows

```bash 
.\venv\Scripts\activate
```
macOS/Linux

```bash 
source venv/bin/activate
```
Install required packages
```bash 
pip install -r requirements.txt
```

We use the Heart Failure Prediction Dataset from Kaggle:
https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction

🧠 Models & Approaches

✅ Single Decision Tree 

✅ Single KNN

✅ Ensemble Decision Tree (Random Forest)

✅ Ensemble KNN (Bagging)

✅ Heterogeneous Ensemble (VotingClassifier: DT + KNN)

📈 Evaluation Metrics

- Accuracy

- Precision, Recall, F1-score

- Confusion Matrix

- ROC-AUC
