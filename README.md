# 🚗 Electric Vehicle Range Prediction (Random Forest Model)

Electric vehicle range depends on multiple factors like the model, vehicle type, manufacturing year, and price.  
This project uses these features to predict the **Electric Range** using a machine learning pipeline.

✅ Data Cleaning  
✅ Feature Engineering  
✅ One-Hot Encoding for Categorical Features  
✅ Random Forest Regressor  
✅ Model Evaluation (MAE & R² Score)  
✅ Exporting the trained model  

## 📊 Dataset Description

The dataset contains the following key columns:

- `Model Year`  
- `Make`  
- `Model`  
- `Electric Vehicle Type`  
- `Base MSRP`  
- `State`  
- `Electric Range` (Target variable)

Before training, the dataset is cleaned:

- Non-numeric ranges converted to numeric  
- Missing values handled  
- Categorical variables encoded  

## 🧠 Machine Learning Model

A **Random Forest Regressor** is used because it performs well on mixed data types and handles categorical encoding through pipelines.

### **Final Model Performance**
- **MAE:** ~0.67  
- **R² Score:** ~0.995  

✅ Very high accuracy  
✅ Excellent generalization  
✅ Low prediction error

## 🛠️ Technologies Used

- Python  
- Pandas  
- Scikit-learn  
- Google Colab  
- Random Forest Regressor  
- OneHotEncoder  
- Joblib (to save model)

##Dataset : https://www.kaggle.com/datasets/yashdogra/ev-bhebic-c
