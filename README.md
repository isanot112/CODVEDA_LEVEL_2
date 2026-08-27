# 🚀 Codveda Data Analytics Internship - Level 2 (Intermediate)

Welcome to my repository for the **Codveda Data Analytics Internship**. This project covers intermediate-level data science and analytics tasks executed using **Python**, **Google Colab**, and the **Stock Prices Dataset** (`2) Stock Prices Data Set (1).csv`).

---

## 📂 Repository Structure

```text
├── 2) Stock Prices Data Set (1).csv   # Raw dataset
├── cleaned_stock_prices.csv           # Cleaned dataset post-preprocessing
├── Codveda_L2.ipynb                   # Jupyter / Google Colab Notebook containing all tasks
└── README.md                          # Project documentation
```

---

## 📊 Tasks Implemented

### **Task 1: Regression Analysis**
* **Objective**: Predict a target financial variable (`close`) based on an independent variable (`open`).
* **Approach**: Built a **Simple Linear Regression** model using `scikit-learn`. Split the dataset into 80% training and 20% testing sets.
* **Key Metrics**:
  * **Coefficient / Slope ($m$):** `0.9998`
  * **Intercept ($c$):** `0.0313`
  * **Mean Squared Error (MSE):** `2.5302`
  * **Root Mean Squared Error (RMSE):** `1.5907`
  * **R-Squared ($R^2$):** `0.9998` *(indicating a 99.98% variance explanation)*

### **Task 2: Time Series Analysis**
* **Objective**: Analyze stock market movements to detect macro trends and periodicity.
* **Approach**: Converted date fields into datetime indices and utilized `statsmodels` for time series decomposition.
* **Key Visualizations**:
  * **Moving Average Smoothing**: Implemented 30-day (medium-term momentum) and 365-day (long-term macro trend) moving averages to eliminate day-to-day market noise.
  * **Decomposition**: Separated the series into Trend, Seasonality, and Residual components.

### **Task 3: Clustering Analysis (K-Means)**
* **Objective**: Group stock trading sessions into distinct clusters based on pricing and volume features.
* **Approach**: Standardized features using `StandardScaler` to ensure equal weight distribution. Applied the **Elbow Method** to determine the optimal cluster count.
* **Findings**: An optimal cluster count of **$k = 3$ to $4$** effectively categorizes market sessions into distinct behavioral segments (e.g., liquidity tiers and price brackets).

---

## 🛠️ Tools & Libraries Used
* **Language**: Python 3
* **Environment**: Google Colab
* **Libraries**: 
  * `pandas` & `numpy` (Data manipulation & cleaning)
  * `scikit-learn` (Linear regression & K-Means clustering)
  * `statsmodels` (Time series decomposition)
  * `matplotlib` & `seaborn` (Data visualization)

---

## ⚙️ How to Run the Code
1. Clone or download this repository.
2. Upload the `Codveda_L2.ipynb` notebook and `2) Stock Prices Data Set (1).csv` file into **Google Colab**.
3. Run the notebook cells sequentially to reproduce the data cleaning pipeline, regression models, time series plots, and clustering analysis.

---

### **Author**
* **Isaac Salifu Nortey Tetteh**  
* *Data Analyst Trainee | BSc. Mathematics and Statistics Student, University of Cape Coast*
