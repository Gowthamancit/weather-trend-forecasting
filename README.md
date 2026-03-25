🌍 Global Weather Trend Forecasting
> Advanced Data Science Assessment | PM Accelerator Tech Internship

---

## 🚀 PM Accelerator Mission
PM Accelerator empowers aspiring Product Managers through real-world
projects, mentorship, and a global community — bridging the gap between
ambition and opportunity.

---

## 📌 Project Overview
End-to-end weather forecasting pipeline on the Global Weather Repository
dataset (100,164 rows × 45 features), covering data cleaning, EDA,
anomaly detection, multi-model forecasting, SHAP analysis, and
interactive spatial visualizations.

---

## 📁 Project Structure
```
weather-trend-forecasting/
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda_anomaly_detection.ipynb
│   ├── 03_forecasting_models.ipynb
│   ├── 04_advanced_analyses.ipynb
│   └── 05_final_evaluation.ipynb
├── outputs/
│   ├── figures/         # All charts & maps
│   └── model_results/   # CSV metrics
├── requirements.txt
└── README.md
```

## 🔬 Key Analyses
- ✅ Data cleaning with interpolation & IQR outlier removal
- ✅ Anomaly Detection — Isolation Forest (5,009 anomalies)
- ✅ Forecasting: SARIMA, Prophet, XGBoost, LSTM + Ensemble
- ✅ SHAP Feature Importance (bar + beeswarm)
- ✅ Interactive World Temperature Map (Plotly)
- ✅ Air Quality vs Weather Correlation Analysis
- ✅ Climate Seasonal Decomposition
- ✅ Geographical Patterns across countries

---

## 📊 Model Results
| Model    | RMSE  | MAE   | MAPE   |
|----------|-------|-------|--------|
| SARIMA   | {results[results.Model=='SARIMA']['RMSE'].values[0]:.3f} | {results[results.Model=='SARIMA']['MAE'].values[0]:.3f} | {results[results.Model=='SARIMA']['MAPE'].values[0]:.2f}% |
| Prophet  | {results[results.Model=='Prophet']['RMSE'].values[0]:.3f} | {results[results.Model=='Prophet']['MAE'].values[0]:.3f} | {results[results.Model=='Prophet']['MAPE'].values[0]:.2f}% |
| XGBoost  | {results[results.Model=='XGBoost']['RMSE'].values[0]:.3f} | {results[results.Model=='XGBoost']['MAE'].values[0]:.3f} | {results[results.Model=='XGBoost']['MAPE'].values[0]:.2f}% |
| LSTM     | {results[results.Model=='LSTM']['RMSE'].values[0]:.3f} | {results[results.Model=='LSTM']['MAE'].values[0]:.3f} | {results[results.Model=='LSTM']['MAPE'].values[0]:.2f}% |
| Ensemble | {results[results.Model=='Ensemble']['RMSE'].values[0]:.3f} | {results[results.Model=='Ensemble']['MAE'].values[0]:.3f} | {results[results.Model=='Ensemble']['MAPE'].values[0]:.2f}% |

---

## 🚀 How to Run
1. Open each notebook in Google Colab in order (01 → 05)
2. Mount your Google Drive
3. Install dependencies: `pip install -r requirements.txt`

---

## 📦 Requirements
See `requirements.txt`
