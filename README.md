# 🏥 Hospital Bed Occupancy Predictor Using AI

An AI-based system that forecasts hospital bed occupancy for the next 24–48 hours using machine learning and time-series forecasting models like LSTM, Prophet, and XGBoost. This helps hospitals plan resources, staff, and improve emergency preparedness.

---

## 📌 Problem Statement

During flu seasons, pandemics, or local health crises, hospitals often face a sudden surge in patient admissions, leading to bed shortages. This delays treatment, overwhelms staff, and affects emergency readiness. Most hospitals lack data-driven forecasting tools and rely on static or manual systems.

---

## 💡 Proposed Solution

This system leverages historical data and external factors (weather, holidays, local disease outbreaks) to accurately forecast short-term hospital bed demand using advanced machine learning models.

---

## 🛠️ Tech Stack

- **Programming Language:** Python  
- **Libraries & Tools:**  
  - Pandas, NumPy, Scikit-learn  
  - TensorFlow / Keras  
  - Facebook Prophet  
  - XGBoost  
  - Streamlit (for dashboard)  
- **Data Sources:**  
  - Historical hospital admission records  
  - Weather APIs  
  - Local disease trend data

---

## 🔍 Features

- Predict bed occupancy for the next 24–48 hours
- Integrates seasonal and real-time external factors
- Visualize predictions in an interactive dashboard
- Improves planning for staff, beds, and equipment

---

## 🧠 Machine Learning Models

- **LSTM:** Captures time-dependent patterns in admission data  
- **Prophet:** Handles trend, seasonality, and holiday effects  
- **XGBoost:** Processes structured features for high accuracy  

All models are evaluated using:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 📈 Results

- The model provides accurate short-term forecasts.
- Visual graphs compare predicted vs. actual bed occupancy.
- Helps hospitals proactively manage resources during peak demand.

---
## 🔮 Future Scope
Predict resource needs: ICU beds, oxygen, ventilators

Real-time integration with hospital databases

Expand to cover multiple hospitals/regions

Edge computing for on-site prediction

Track doctor availability and specialization

---

## 🚀 Deployment

The system includes a web-based dashboard (using Streamlit) that hospital staff can use to view predictions and plan accordingly.

To run locally:

```bash
git clone https://github.com/yourusername/hospital-bed-predictor
cd hospital-bed-predictor
pip install -r requirements.txt
streamlit run app.py
 ```



