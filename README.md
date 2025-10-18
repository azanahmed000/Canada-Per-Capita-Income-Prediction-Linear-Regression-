# 🇨🇦 Canada Per Capita Income Prediction (Linear Regression)

### 📖 Project Overview
This is a **beginner-level machine learning project** that uses a simple **linear regression** model to predict **Canada's per capita income (US$)** based only on **year** (1970–2016).  
The goal is to understand how regression fits data, evaluates accuracy, and visualizes results — **not** to forecast real economic outcomes.

---

### 📊 Dataset
- **File:** `canada_per_capita_income.csv`  
- **Columns:**
  - `year` — from 1970 to 2016  
  - `per capita income (US$)` — average annual income in USD  
- Source: Common public dataset used for ML education purposes.

---

### ⚙️ Model Details
- **Algorithm:** Linear Regression (`sklearn.linear_model.LinearRegression`)
- **Input feature:** Year  
- **Target:** Per capita income (US$)
- **Train/Test split:** 80% training, 20% testing  
- **Random seed:** 42 (for reproducibility)

---

### 📈 Results
| Metric | Value | Meaning |
|--------|--------|----------|
| **R² Score** | 0.875 | Model explains 87.5% of data variation |
| **RMSE** | \$3,892 | Average prediction error (≈10% of income value) |

✅ The model captures the long-term upward trend of income growth.  
⚠️ It doesn’t model short-term fluctuations (expected with one feature).

---

### 🖼️ Visual Output
- Scatter plot of historical data  
- Regression line fitted on training data  
- Test data points highlighted  
- Simple residual check  

---

### 🧰 Libraries Used
