# ❤ Heart Disease Prediction

This project is focused on predicting the presence of heart disease using machine learning models. It takes various medical attributes as input to assess the risk of heart disease in a patient.

## Files

- `heart_disease.ipynb` - Main Jupyter Notebook with data preprocessing, EDA, model building, and evaluation.
- `plots/` - Folder containing visualizations and model performance plots.

##  Models Used

- Logistic Regression  
- Random Forest  
- Decision Tree

##  Dataset Features

Typical features include:

- Age  
- Sex  
- Chest Pain Type  
- Resting Blood Pressure  
- Cholesterol  
- Fasting Blood Sugar  
- ECG Results  
- Max Heart Rate  
- Exercise-induced Angina  
- ST Depression  
- Number of major vessels  
- Thalassemia

*(Assumes standard UCI Heart Disease dataset; update as per your dataset)*

## ⚙️ How to Run

1. Open `heart_disease.ipynb` in Jupyter or Google Colab.
2. Run all cells in order.
3. Evaluate the performance of each model.

##  Results

Each model is evaluated using accuracy, precision, recall, and ROC-AUC scores. Final comparisons help select the most effective model for deployment.

##  Future Improvements

- Hyperparameter tuning using GridSearchCV or RandomizedSearchCV  
- Deploy best model with Flask or Streamlit  
- Include model explainability (e.g., SHAP or LIME)

---

Feel free to modify this based on your actual models, results, or dataset used!
