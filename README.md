# ⚡ EV Sales Analysis & Forecasting with Machine Learning

## 📌 Introduction
Electric Vehicles (EVs) are reshaping the future of mobility. This project explores EV sales data, identifies adoption trends, and applies machine learning techniques to forecast future sales. It provides data-driven insights for manufacturers, governments, and sustainability-focused stakeholders.

📍 View the Python code here: [ElectricVehicleSalesbyStateInIndia
](EV_Sales_Analysis_ML.ipynb)


## 📚 Background
With increasing climate concerns and global efforts to reduce carbon emissions, the demand for EVs has surged. This project was initiated to:
- Understand key players and sales trends in the EV market
- Compare BEV vs. PHEV adoption patterns
- Forecast EV sales using a machine learning model

## 🛠️ Tools Used
- **Python**: Data manipulation and modeling  
- **Jupyter Notebook**: Interactive analysis  
- **Libraries**:
  - `pandas`, `numpy`: Data preprocessing
  - `matplotlib`, `seaborn`: Data visualization
  - `xgboost`, `sklearn`: Machine learning
- **Model**: XGBoost Regressor for time series forecasting

## 📊 The Analysis
- **Data Preprocessing**:
  - Cleaned missing values
  - Parsed and structured dates
  - Categorized vehicle types (BEV, PHEV)
- **Exploratory Data Analysis**:
  - 📈 Yearly and monthly sales trends
  - 🚗 Top manufacturers (e.g., Tesla, Nissan)
  - 🗺️ State-wise distribution of EV adoption

![Monthly_EV_Sales_Trend](Assets/Monthly_EV_Sales_Trend.png)
![Top10_States_by_Total_EVSales](Assets/Top10_States_by_Total_EVSales.png)
![Sales_by_Vehicle_Class](Assets/Sales_by_Vehicle_Class.png)
![Monthly_Seasonality_Heatmap](Assets/Monthly_Seasonality_Heatmap.png)


- **Machine Learning Forecasting**:
  - Created time-series features
  - Trained XGBoost Regressor
  - Evaluated model with RMSE & MAE
  - Visualized predictions vs. actual sales

![Time_Series_Forecasting](Assets/Time_Series_Forecasting.png)
![Linear Regression Actual vs Predicted](Assets/Linear_Regression_Actual_vs_Predicted.png)

## 📈 What I Learned
- Data cleaning and time-based feature engineering are critical for time-series ML.
- BEVs are gaining dominance over PHEVs in recent years.
- Regional policies and infrastructure play a key role in EV adoption.
- XGBoost performs well on structured, temporal datasets.

## 💡 Conclusion & Insights
- EV adoption is growing consistently with strong market momentum.
- Tesla continues to lead, but new players are gaining traction.
- Sales show seasonality — policy incentives and infrastructure investments impact surges.
- Forecasts suggest sustained growth, especially with expanding support networks.

## 🙌 Closing Thoughts
This project demonstrates how machine learning and data analytics can drive insights into the evolving EV market. Future enhancements could include:
- LSTM-based deep learning forecasting
- Integration of charging station and fuel price data
- Sentiment analysis from EV reviews or social media

---

📁 Explore the full notebook: `EV_Sales_Analysis_ML.ipynb`  

