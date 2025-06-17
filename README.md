# 📊 Supply Chain Greenhouse Gas (GHG) Emissions Prediction Project

---

## 🎯 Project Goal

To analyze and predict greenhouse gas (GHG) emissions from various U.S. industries and commodities using official supply chain data sourced from [data.gov](https://www.data.gov/).

The aim is to build robust regression models that can predict **GHG Emissions (kg CO₂ equivalent)** based on industry, commodity, and quality-related descriptive features.

---

## 🌐 Data Source

- **Dataset Name:** Supply Chain Greenhouse Gas Emission Factors  
- **Source:** data.gov  
- **Years Covered:** 2010 – 2016

---

## 📂 Dataset Overview

The dataset contains annual supply chain GHG emission factors across various U.S. industries and commodities.

---

## 🧹 Data Preprocessing Workflow

### 1️⃣ Data Loading

- Multiple Excel sheets loaded from 2010–2016.
- Combined Industry and Commodity data into one dataset.

### 2️⃣ Data Cleaning

- Handle missing values (drop or impute).
- Convert data types to appropriate formats.
- Standardize column names.
- Remove duplicate rows.

### 3️⃣ Feature Engineering

- Encode categorical features (e.g., Industry_Name, Commodity, Substance, Source).
- Normalize/scale numeric columns for model compatibility.

---

## 🔎 Exploratory Data Analysis (EDA)

- Analyzed distributions of GHG emissions.
- Investigated relationships between descriptive metrics and emission factors.
- Detected outliers and patterns across industries and commodities.

---

## 🤖 Model Building & Evaluation

### ✅ Target Variable

- `GHG_Emissions_kgCO2e`

### ✅ Features Used

- Industry & Commodity Codes
- Reliability and Correlation scores
- Year, Source, Substance, Units (encoded)

### ✅ Models Applied

- Linear Regression (Baseline)
- Random Forest Regression
- *(Optional: Other regressors like XGBoost, SVR for comparison)*

### ✅ Evaluation Metrics

| Metric | Description |
|--------|-------------|
| RMSE   | Root Mean Squared Error |
| MAE    | Mean Absolute Error |
| R² Score | Coefficient of Determination |

---

## 🔧 Tools & Technologies Used

- **Language:** Python 3.x
- **Libraries:**
  - Pandas
  - NumPy
  - Scikit-learn
  - Matplotlib
  - Seaborn

---

## 🔬 Modeling Workflow

1️⃣ Step 1: Import Required Libraries  
2️⃣ Step 2: Load Dataset  
3️⃣ Step 3: Data Preprocessing (Cleaning + EDA + Encoding)  
4️⃣ Step 4: Split Dataset (Train-Test Split)  
5️⃣ Step 5: Model Training  
6️⃣ Step 6: Prediction and Evaluation  
7️⃣ Step 7: Hyperparameter Tuning  
8️⃣ Step 8: Comparative Study and Best Model Selection

---

## 📌 Author

**Satyam Mishra**

---

