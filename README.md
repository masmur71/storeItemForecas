# Time Series Sales Forecasting Using ARIMA - Project Overview

This repository contains a Jupyter Notebook that demonstrates the process of performing time series forecasting on sales data using  SARIMAX models. The notebook is structured to guide the user from raw data exploration to final forecast generation.

## Notebook File: `ForeCastArima_Masmur_Toloni_Harefa.ipynb`

### **Purpose**
The notebook focuses on forecasting daily sales based on historical transaction data. This approach can be useful for demand prediction, stock management, or competition tasks involving time series forecasting.

---

## **Notebook Workflow Breakdown**

### **1. Library Installation and Import**
- Essential libraries:
  - `pandas`, `numpy` for data handling
  - `matplotlib`, `seaborn` for visualization
  - `statsmodels` for ARIMA/SARIMAX modeling

### **2. Data Access**
  - `train.csv`: Contains historical sales data, including `date`, `store`, `item`, and `sales` columns.
  - `test.csv`: Test dataset where sales values need to be predicted.
  - `sample_submission.csv`: Template for submitting forecast results.

---

### **3. Exploratory Data Analysis (EDA)**
- Inspects the structure of the datasets.
- Checks for missing values.
- Analyzes:
  - Total number of items per store
  - Unique item counts
- Visualizes:
  - Daily total sales trends
  - Sales distribution (histogram)
- Performs **feature engineering**:
  - Extracts date-based features: `year`, `month`, `day_of_week`, `is_weekend`
- Examines average sales by:
  - Day of the week
  - Month

---

### **4. Time Series Modeling (ARIMA/SARIMAX)**
- Applied ARIMA and/or SARIMAX models to forecast sales.
- Model selection, fitting, and forecast generation are performed based on historical patterns.
- Visualizations compare actual sales and model predictions to evaluate model performance.

---

### **5. Output**
- Forecast results for the test dataset.
- Visualization of trends and model performance.
- Optional generation of a `submission.csv` file based on the required format.

---



