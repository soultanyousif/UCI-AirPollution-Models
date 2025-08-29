# UCI-AirPollution-Models
Predicting air quality trends using machine learning models on the UCI AirQuality dataset  Comparison of Linear Regression, XGBoost, and MLP models for UCI AirQuality time series data 
## 📖 Overview

This project explores air quality patterns using the [UCI AirQuality dataset](https://archive.ics.uci.edu/ml/datasets/air+quality).  
It focuses on predicting air pollution levels based on environmental factors and compares the performance of different regression models.  

---

## 🗂 Dataset
- **Source:** [UCI AirQuality Dataset](https://archive.ics.uci.edu/ml/datasets/air+quality)  
- **Description:** Contains hourly averaged responses from an array of gas sensors deployed in an Italian city.  
- **Features:**  
  - CO, NOx, NO2 concentrations  
  - Temperature, humidity, and other environmental variables  
- **Target:** Predict air pollution (e.g., CO concentration or another selected pollutant)

---

## ⚙ Methods
The following regression models were applied and compared:
1. **Linear Regression (LR)** – Baseline model for prediction.
2. **XGBoost (XGB)** – Gradient boosting regression for capturing non-linear patterns.
3. **Multi-Layer Perceptron (MLP)** – Neural network model for complex relationships.

**Evaluation Metrics:**  
- R² Score  
- Mean Absolute Error (MAE)  
- Mean Squared Error (MSE)  
- Root Mean Squared Error (RMSE)

---

## 📊 Results
- The notebook contains visualizations comparing model predictions vs actual values.  
- Performance metrics are calculated for all three models to determine the best-performing approach.

---

## 💻 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/UCI-AirQuality-Analysis.git
