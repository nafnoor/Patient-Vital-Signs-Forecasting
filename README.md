
# Patient Vital Signs Forecasting

## 1. Project Overview
This project analyzes historical patient vital signs and forecasts future values to help clinicians identify early signs of deterioration.

---

## 2. Objectives
- Predict Heart Rate (HR) and Systolic Blood Pressure (SBP) for the next 6 hours.
- **Use case:** Early Warning System in healthcare settings.
- **Performance Metric:** Mean Absolute Error (MAE) < 5% for both HR and SBP.

---

## 3. Data Sources
- **Dataset:** MIT-BIH Arrhythmia Database  
- **Link:** [MIT-BIH Database](https://www.physionet.org/content/mitdb/1.0.0/)  
- **Reason:** Open-source, free, rich ECG & BP data for forecasting tasks.

---

## 4. Data Preprocessing
1. Load ECG & BP signals using `wfdb`.
2. Resample data to consistent intervals.
3. Handle missing values.
4. Normalize vital signs.

---

## 5. Modeling Approach
- **Models Used:**  
  - ARIMA / SARIMA  
  - LSTM / GRU (Deep Learning)  
- **Evaluation Metrics:** MAE, RMSE

---

## 6. Code Structure
1. **Data Loading & Exploration**  
2. **Feature Engineering**  
3. **Model Training**  
4. **Forecasting & Visualization**  
5. **Model Evaluation**  

---

## 7. Results & Insights
- Achieved MAE < 5% for best-performing model.
- LSTM outperformed ARIMA for long-range forecasting.
- Visualizations show predicted vs actual trends.

---

## 8. Future Improvements
- Add more vital signs like oxygen saturation.
- Deploy as a real-time API.
- Try hybrid statistical + deep learning models.

---

## 9. Dependencies
- Python 3.10+  
- Libraries: `wfdb`, `pandas`, `numpy`, `matplotlib`, `scikit-learn`, `tensorflow` or `pytorch`  
