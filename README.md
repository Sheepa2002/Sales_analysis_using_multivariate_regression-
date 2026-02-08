# 📊 Multivariate Sales Analysis (BigMart Dataset)

## 📌 Project Overview  
This project applies **Multiple Linear Regression** to analyze and predict product sales using the BigMart dataset. The objective is to understand how multiple product and outlet-level variables influence sales and to build a statistically validated regression model.



## 🎯 Objectives  
- Identify key factors affecting `Item_Outlet_Sales`  
- Handle missing values and perform feature engineering  
- Apply multivariate regression modeling  
- Evaluate model performance using statistical metrics  



## 📂 Dataset  
The dataset contains product-level and outlet-level features such as:  
- Item Weight  
- Item Visibility  
- Item MRP  
- Item Type  
- Outlet Size  
- Outlet Location Type  
- Outlet Type  
- Outlet Establishment Year  

**Target Variable:** `Item_Outlet_Sales`



## ⚙️ Methodology  

### 1️⃣ Data Preprocessing  
- Imputed missing values using group-based mean/mode  
- Replaced zero visibility with mean value  
- Cleaned categorical inconsistencies  
- Created new features:  
  - `New_Item_Type`  
  - `Age_of_Outlet`  
- Applied Label Encoding and One-Hot Encoding  

### 2️⃣ Exploratory Data Analysis  
- Correlation heatmap analysis  
- Multivariate relationship analysis  

### 3️⃣ Model Development  
- Log transformation of target variable  
- Multiple Linear Regression  
- Cross-validation (5-fold)  
- Statistical modeling using Statsmodels (OLS summary)  

### 4️⃣ Model Diagnostics  
- R² Score evaluation  
- Mean Squared Error (MSE)  
- Variance Inflation Factor (VIF) for multicollinearity detection  
- Comparison with single-variable regression models  



## 🛠️ Tools & Technologies  
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Statsmodels  



## 📊 Key Insights  
- Item MRP showed strong influence on sales  
- Multivariate model significantly improved performance compared to single regressor models  
- Multicollinearity was evaluated and reduced using VIF analysis  



## 🚀 Conclusion  
The project demonstrates how multivariate regression techniques can be used to extract meaningful insights from structured sales data and support data-driven business decision-making.
