# Aadhaar Seva Intelligence (ASI) 🇮🇳
### *Unlocking Societal Trends in Aadhaar Enrolment and Updates*

![Status](https://img.shields.io/badge/Status-Completed-success)
![Python](https://img.shields.io/badge/Python-3.x-blue)
![License](https://img.shields.io/badge/Hackathon-UIDAI_2026-orange)

## 📌 Project Overview
**Aadhaar Seva Intelligence (ASI)** is a data-driven framework designed to shift the Aadhaar ecosystem from a **Reactive** service model to a **Predictive** one.

By analyzing **2.1 Million+ transactional records**, this project correlates *Enrolment Saturation* with *Demographic Migration Patterns* to identify high-stress service zones ("Migration Hubs") and forecast future demand.

## 🚀 Key Features
* **Migration Pressure Index (MPI):** A proprietary metric to detect districts where update demand overwhelms enrolment infrastructure (e.g., Beawar, Balotra).
* **Service Delivery Matrix:** Classifies 700+ districts into 4 operational quadrants for dynamic resource allocation.
* **Lifecycle Forecasting:** A **Gradient Boosting (XGB)** model that predicts biometric update surges 12 weeks in advance with high accuracy.

## 📂 Repository Structure
* `UIDAI_Solution_Framework.ipynb` - The main Jupyter Notebook containing:
    * **Phase 1:** Data Ingestion & Cleaning.
    * **Phase 2:** Feature Engineering (MPI, Saturation Gap).
    * **Phase 3:** Visual Analysis (Radar Maps, Matrix).
    * **Phase 4:** Machine Learning (Model Competition & Forecast).

## 📊 Key Findings
1.  **The Migration Disconnect:** 10 Critical districts show an Update-to-Enrolment ratio of >200:1, indicating massive unserved migration influx.
2.  **Predictive Accuracy:** Our Gradient Boosting model outperformed Linear Regression, predicting a **20% surge** in Biometric Updates for Q1 2026 due to school lifecycle patterns.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, Seaborn, Scikit-Learn (LinearRegression, RandomForest, XGBoost)

* ## 📂 Data Setup
**Note:** The raw datasets (CSV) are not included in this repository due to size constraints.
To run this notebook:
1. Download the official datasets from the [UIDAI Hackathon Portal](https://event.data.gov.in).
2. Place all `api_data_*.csv` files in the same folder as the notebook.
3. Run the cells sequentially.

---
*Submitted for the UIDAI Data Hackathon 2026.*
