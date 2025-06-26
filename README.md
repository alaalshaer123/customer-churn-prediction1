# Customer Churn Prediction Using Random Forest

This project uses the Telco Customer Churn dataset from Kaggle to build a predictive machine learning model that classifies whether a customer will churn.

## 🔍 Problem
Customer churn prediction helps telecom companies reduce loss by targeting at-risk customers with retention offers.

## 🧠 Model Used
- **Random Forest Classifier**
- Evaluation metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC
- Interpretability using SHAP values

## 🛠️ Workflow
1. Data preprocessing: Imputation, encoding, scaling
2. Model training: Random Forest with GridSearchCV
3. Cross-validation: 5-fold Stratified
4. Evaluation and visualization
5. Clustering: KMeans for customer segmentation

## 📊 Sample Results

| Metric     | Score  |
|------------|--------|
| Accuracy   | 83.5%  |
| Precision  | 76.2%  |
| Recall     | 68.9%  |
| F1 Score   | 72.3%  |
| ROC AUC    | 0.88   |

## 📁 Files
- `churn_model.ipynb`: Full notebook with all steps
- `requirements.txt`: Python package requirements
- `images/`: Visuals (confusion matrix, ROC curve, SHAP)

## 📚 Dataset
- [Kaggle - Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

## ✅ How to Run
1. Clone this repo
2. Run `pip install -r requirements.txt`
3. Open and run `churn_model.ipynb`

## 👩‍💻 Author
Ala Alshaer — MSc Business Analytics, ADSM
