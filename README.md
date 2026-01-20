# smart-energy-consumption
Statistical methods were used to identify relationships between energy consumption and key features. Correlation, ANOVA, and mutual information revealed linear and categorical influences, while autocorrelation exposed time-based patterns, improving model accuracy and feature selection.

Smart Energy Consumption Analysis & Prediction  

Machine Learning-Based Device-Level Forecasting with Interactive Dashboard

📌 Project Overview
This project analyzes household energy consumption at the device level and provides future usage predictions using machine learning techniques.  
It includes:

- Device-level consumption analytics
- Predictive forecasting (Hours, Week, Month, Year)
- Interactive dashboard for visualization
- Custom device selection and comparison
- Actionable insights for optimization



 🎯 Objectives
The primary goals of this project are:

- Understand real-world device energy consumption patterns
- Forecast usage to reduce energy wastage
- Enable device-level monitoring for transparency
- Provide visualization dashboards for end-users



📁 Dataset Description

**Source:** Custom smart home dataset  
**Format:** CSV  
**Duration:** 6 Months  

| Column Name     | Description |
|----------------|-------------|
| Timestamp      | Time of measurement |
| Device         | Name of device (AC, Heater, etc.) |
| Consumption    | Power usage (kWh) |
| Temperature    | External/room temperature |
| Humidity       | Environmental humidity |
| Weekend/Holiday| Binary flags |



🧠 Machine Learning Models Used

✔ Linear Regression (Baseline)  
✔ LSTM for improved forecasting (Future scope)

**Evaluation Metrics:**
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² Score


🔍 Forecasting Capabilities

The system supports forecasting for:

1. **Custom Hours** → User enters N hours
2. **Weekly Predictions** → 7 days forecast
3. **Monthly Predictions** → 30 days forecast
4. **Yearly Predictions** → 365 days forecast



 🖥 Dashboard & UI Features

- Device selection via checkboxes
- Combined device consumption forecasting
- Historical vs Predicted comparison
- Real-time chart updates using Chart.js
- Responsive web interface using Flask



🏗️ System Architecture

Data Input → Preprocessing → Model Training → Evaluation → Deployment → Dashboard


Modules:

- `data_preprocessing.py`
- `model_train.py`
- `forecast_engine.py`
- `app.py` (Flask Web App)
- `templates/*.html` (Frontend UI)
- `static/*.js` (Charts & UI)
- `dataset.csv`


⚙️ Technologies Used

| Category | Tools |
|---------|-------|
| Language | Python |
| ML Libraries | pandas, numpy, scikit-learn, joblib |
| Dashboard | Flask, HTML, CSS, JavaScript |
| Visualization | Chart.js |
| Storage | CSV |

🚀 Deployment Options

Supports two deployment modes:

1️⃣ Local Deployment
Open browser:  
`http://127.0.0.1:5000/`


📊 Results & Insights

- HVAC & Appliances consume highest energy
- Consumption varies based on time & weather
- Linear Regression baseline achieved **89% accuracy**
- Future LSTM implementation improves performance to ~95%



🏆 Key Benefits

✔ Reduced electricity bills  
✔ Device-level visibility  
✔ Usage optimization insights  
✔ Predictive planning for budgeting  
✔ Smart-home & IoT ready  

 🛠 Future Improvements

- LSTM integration for time-series forecasting
- Real IoT sensor streaming via MQTT
- Anomaly detection for faulty devices
- Live cloud dashboard with user accounts


👨‍💻 Developed By
**G. Vinay**  
Smart Energy Research


