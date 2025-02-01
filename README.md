# 🌍 Life Expectancy Prediction (Applied Statistics & Machine Learning)  

🚀 **Statistical Regression Analysis on WHO Dataset (2000-2015)**  
This project applies **regularized linear regression (Lasso, Ridge, Elastic Net) and Support Vector Regression (SVR)**  
to analyze factors influencing **life expectancy** using WHO data. It compares models and identify key health  
and economic indicators affecting life expectancy.

---

## 📖 Project Overview  

Life expectancy is influenced by a range of socioeconomic, health, and environmental factors.  
This project aims to **analyze the key predictors** of life expectancy and evaluate different regression models  
to optimize prediction accuracy.

The dataset includes:
- **Demographics**: Year, Country, Country Status (Developed/Developing)  
- **Health Factors**: Adult Mortality, Infant Deaths, Polio, Hepatitis B, HIV/AIDS  
- **Lifestyle & Economic Factors**: Alcohol Consumption, Healthcare Expenditure, Income Composition, Schooling  

📌 **Models Used**:  
✔ **L1 (Lasso) Regression** – Feature selection by shrinking coefficients to zero  
✔ **L2 (Ridge) Regression** – Reduces coefficient magnitudes to prevent overfitting  
✔ **Elastic Net** – Combination of Lasso & Ridge for improved balance  
✔ **Support Vector Regression (SVR)** – Captures nonlinear relationships  
✔ **Random Forest Regression** – Non-parametric ensemble method for performance comparison  

---

## 🎯 Objectives  

1️⃣ **Data Preparation**: Cleaning, Encoding, Feature Selection  
2️⃣ **Regularization Techniques**: Analyzing L1, L2, and Elastic Net impact on regression  
3️⃣ **SVR vs. Ridge Regression**: Comparing performance & interpretability  
4️⃣ **Random Forest Regression**: Evaluating non-parametric predictions  
5️⃣ **Life Expectancy Prediction**: Using the best model to forecast new data  

---

## 📂 Dataset  

📌 **Source**: WHO Life Expectancy Dataset (2000-2015)  
📊 **Features**:  
- **Health Metrics**: Adult Mortality, Infant Deaths, BMI, Under-5 Mortality  
- **Economic & Social Factors**: Income, Schooling, Government Health Expenditure  
- **Categorical Variables**: Country Status (Developed/Developing)  

### 🛠️ **Data Cleaning & Processing**  
✔ Handling missing values with **mean imputation**  
✔ Encoding categorical variables (**Binary & One-Hot Encoding**)  
✔ Feature correlation analysis using **heatmaps**  
✔ Standardization using **StandardScaler()**  

---

## ⚙️ Tools & Techniques  

✔ **Programming**: Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)  
✔ **Regularization Techniques**: L1 (Lasso), L2 (Ridge), Elastic Net  
✔ **Regression Models**: Support Vector Regression (SVR), Random Forest Regression  
✔ **Model Evaluation**: R² Score, Adjusted R², Feature Importance  

---

## 📊 Key Deliverables  

✅ **Preprocessed Dataset** (Cleaned & Engineered for ML)  
✅ **Feature Importance Analysis** (Regularization Impact)  
✅ **Model Performance Comparison** (Regression Models)  
✅ **Life Expectancy Prediction** (Best Model Deployment)  

---

## 🔍 Insights & Findings  

📌 **Best Performing Model**: **Random Forest Regression** (Highest R² Score)  
📌 **Lasso Regression** eliminated **irrelevant features**, improving efficiency  
📌 **SVR provided strong predictive ability but was harder to interpret**  
📌 **Income, Adult Mortality & Healthcare Expenditure were key predictors**  

---
