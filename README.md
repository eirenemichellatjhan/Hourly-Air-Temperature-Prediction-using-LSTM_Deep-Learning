# Hourly-Air-Temperature-Prediction-using-LSTM_Deep-Learning

This project aimed to forecast the next hour’s air temperature (AT) based on the previous 5 hours of air quality and meteorological data. The dataset included multiple environmental factors such as particulate matter (PM2.5, PM10), gases (CO, NOx, SO2), and weather parameters (humidity, wind speed, solar radiation). By combining these features, the model learned short-term temperature patterns useful for urban planning, public health, and energy management.

**Tools**: Python, TensorFlow, Keras, Pandas, Matplotlib

**Approach**: Compared three models, a simple LSTM, a bidirectional LSTM, and a tuned version with fewer layers and dropout.

**Results**: The baseline LSTM achieved the best performance with the lowest MAE and MAPE and highest R², outperforming the more complex models.

**Key Insight**: Good data and clear temporal patterns can make a simple model outperform deeper, more complex ones.
