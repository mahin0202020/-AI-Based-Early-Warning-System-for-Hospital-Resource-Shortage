# AI-Based-Early-Warning-System-for-Hospital-Resource-Shortage
An intelligent time-series forecasting system designed to predict daily hospital bed occupancy and generate automated early warnings to prevent resource shortages. 

## 💡 The Problem
During medical emergencies or sudden disease outbreaks, hospitals often face severe shortages of beds and resources. Without prior forecasting, management fails to accommodate incoming patients efficiently.

## 🚀 The Solution
This project utilizes Machine Learning (Demand Forecasting) to predict the number of patients expected the next day based on historical admission data. If the predicted number crosses a specific capacity threshold, the system triggers a **Warning** or **Critical Alert**, allowing hospital staff to prepare in advance.

## 🛠️ Key Features
* **Time-Series Feature Engineering:** Extracts meaningful patterns using `Lag_1`, `Lag_7`, and `Rolling_Mean_7`.
* **Comparative AI Analysis:** Evaluates multiple algorithms to find the most efficient forecasting engine.
* **Automated Alert Dashboard:** A threshold-based logic system that outputs actionable insights (e.g., Status Normal, Warning, Overcapacity).
* **High-Quality Visualizations:** Includes Actual vs Predicted trend lines, Goodness of Fit scatter plots, and Feature Importance tracking.

## 📊 Machine Learning Leaderboard (Performance)
Extensive testing was done on a sample dataset. The simpler, lightweight model outperformed complex ensemble and statistical models due to the strong linear relationship in daily patient flow.

| Rank | Model Name | Accuracy (R² Score) | Average Error (MAE) |
| :--- | :--- | :--- | :--- |
| **🥇 1st** | **Linear Regression** | **1.00** | **4.93** |
| 🥈 2nd | Gradient Boosting | 1.00 | 5.23 |
| 🥉 3rd | Random Forest | 1.00 | 5.23 |
 

## 💻 Tech Stack
* **Language:** Python
* **Data Processing:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn, Statsmodels
* **Data Visualization:** Matplotlib, Seaborn

## 🔮 Future Scope
* **Phase 2:** Exporting the trained model (`.pkl`) and building a robust backend REST API using **FastAPI / Flask**.
* **Phase 3:** Developing a real-time Interactive Web Dashboard for hospital administration.

---
**Developed by:** Abdullah Mahin  
*Department of Software Engineering, Daffodil International University*
