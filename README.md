# Drug Classification using Machine Learning

This project applies various machine learning algorithms to classify drug types based on patient attributes.  
It includes data preprocessing, outlier handling, feature selection, and model training with multiple classifiers.

# Dataset
- Features:
  - Age
  - Sex
  - BP (Blood Pressure)
  - Cholesterol
  - Na_to_K (Sodium-Potassium ratio)
- Target: `Drug` (categorical)

# Workflow
1. **Data Preprocessing**
   - Outlier detection & clipping (IQR method)  
   - Label encoding (target variable)  
   - One-hot encoding (categorical features: Sex, BP, Cholesterol)  
   - Standardization of numerical features  

2. **Feature Selection**
   - ANOVA F-test  
   - ExtraTreesClassifier (tree-based feature importance)  

3. **Models Implemented**
   - Logistic Regression  
   - Decision Tree  
   - Random Forest  
   - Support Vector Machine (SVM)  
   - K-Nearest Neighbors (KNN)  
   - XGBoost  

4. **Evaluation**
   - Accuracy score  
   - Classification report  
   - Correlation heatmap  
   - Feature importance plots  

# Usage
Clone the repository and install dependencies:
```bash
git clone https://github.com/prathana-192/drug-classification-ml.git
cd drug-classification-ml
pip install -r requirements.txt
