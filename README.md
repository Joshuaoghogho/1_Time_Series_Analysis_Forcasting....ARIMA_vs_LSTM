## ✅ PROJECT TITLE:
 Time Series Forecasting of Monthly Milk Production Using ARIMA & LSTM
## 🔹 PROJECT PURPOSE – Time Series Forecasting of Milk Production
 This project aimed to develop predictive models using 168 months (14 years) of historical data.
 The objective was to understand seasonal trends, remove fluctuations, & build robust forecasting systems for better dairy supply chain decision-making. 
ARIMA Model: Trained on the first 12 years & tested on the last 2 years.
LSTM Model: Used the ‘Production’ feature, with 85% of the data for training & 15% for testing. 
These models help enhance production planning, reduce waste, & support business strategies with data-driven forecasts.
## 🔹 PROBLEM STATEMENT – Forecasting Milk Production
 Milk production is highly seasonal and impacted by biological cycles and weather. Without proper forecasting, the industry faces:
Overstocking or shortages due to poor demand estimation
Wastage of perishable products. Inefficiencies in budgeting and supply chain operations
## 🔹 TECHNOLOGIES USED – Python, I built a Seasonal ARIMA model (SARIMA(2,0,0)(0,1,1)[12]) 
using stepwise AIC optimization and validated predictions using visual and statistical analysis.
## 📈 AIC: 1072.066
## 📉 MAE:~173 
## RMSE: ~195. 
The model also forecasted production 24 months ahead for strategic planning.
In parallel, I developed an LSTM Deep Learning model using scaled time-window sequences to capture complex temporal dependencies. 
It provided significantly improved accuracy.
## 🔹 MODEL EVALUATION COMPARISON
Metric ARIMA LSTM 
MAE 172.96 23.56 
MSE 38068.86 1023.72 
RMSE 195.11 32.00 
## ✔Interpretation: LSTM outperformed ARIMA across all metrics, capturing complex patterns & reducing forecast error significantly.
## 🔹 FINDINGS: The original time series was non-stationary with upward trend & seasonality. Applied ADF test to confirm stationarity after differencing.
ARIMA(2,1,2) was selected based on ACF/PACF & AIC.
Residuals showed no autocorrelation, validating model reliability.
## 🔹 SCENARIO PLANNING FOR GROWTH & SUPPLY CHAIN STRATEGY
 I simulated company growth scenarios using model forecasts:
📊 What if: Demand increases by 10%? There’s a 10% supply chain delay?
## Example Forecast Output:
## Date        Forecast          +10% Demand           -10% Supply 
Jan 1976       859.93             945.92                773.94 
Feb 1976       867.15             953.87                780.44
Mar 1976       899.50             989.45                809.55  
→ Result: Helps assess capacity, resource needs, avoid under/overproduction, and improve responsiveness.
## 🔹 DECISION-MAKING STRATEGY
Enable data-driven production planning
Improve inventory control and reduce operational waste
Support long-term budgeting & logistics efficiency
## 🔹 AUTOMATION & DASHBOARDING
Setup automated forecasting pipelines
Create dashboards using Python, Power BI, or Tableau
Continuously retrain models for accuracy
## 🔹 TECHNIQUES APPLIED
✅ Augmented Dickey-Fuller (ADF) Test for stationarity
✅ Auto-ARIMA with AIC optimization
✅ Deep LSTM Network for long-sequence learning
✅ Custom Matplotlib visualizations
✅ Model validation using train-test split
✅ Metrics: MAE, MSE, RMSE for performance
## 🔹 BUSINESS IMPACT
✔ Dairy producers can align feeding schedules with predicted peaks
✔ Supply chain managers reduce wastage and streamline distribution
✔ Retailers can match supply with forecasted demand
✔ Enabled Scenario Planning (e.g., +10% growth, delays) to inform strategic decisions
✔ Adaptable to other domains like Retail, Energy, Healthcare, etc.
## 📌 This project not only showcases statistical modeling and deep learning skills but also emphasizes real-world business impact and strategic foresight.

