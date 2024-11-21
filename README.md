# AIML CA2: Time Series Analysis and Clustering  
This project comprises two parts, focusing on predictive modeling tasks for stock price analysis and anomaly detection using machine learning techniques.

---

## Part A: Time Series Analysis  

### **Objective**  
To analyze and model stock price data to identify trends and predict future prices.

### **Key Steps**  
1. **Dataset Overview:**  
   - Used a stock price dataset with multiple time series features.  
   - Preprocessed the dataset and checked for missing or inconsistent data.

2. **Stationarity Check:**  
   - Evaluated the stationarity of the dataset using statistical tests.  
   - Applied differencing techniques to transform the data into a stationary format.

3. **Feature Engineering:**  
   - Calculated the Simple Moving Average (SMA) to identify long-term trends.

4. **Model Selection:**  
   - Built and tuned an **ARIMA model** for time series forecasting.  
   - Incorporated seasonality using the **SARIMAX model** for more accurate predictions.

5. **Hyperparameter Tuning:**  
   - Optimized ARIMA and SARIMAX hyperparameters to improve forecasting performance.

### **Conclusion**  
The SARIMAX model outperformed ARIMA by accurately capturing seasonality in the data, enabling more reliable stock price forecasts.

---

## Part B: Clustering and Anomaly Detection  

### **Objective**  
To group stock price data into clusters and detect anomalies using unsupervised learning.

### **Key Steps**  
1. **Dataset Overview:**  
   - Used scaled stock price data with features suitable for clustering.  
   - Applied feature scaling to standardize the dataset.

2. **Clustering:**  
   - Performed **K-Means clustering** to group data points based on similarity.  
   - Selected the optimal number of clusters using the elbow method.

3. **Anomaly Detection:**  
   - Identified anomalies in the stock price data by analyzing outlier clusters.

4. **Model Selection:**  
   - K-Means clustering was selected for its simplicity and effectiveness in grouping data.

5. **Hyperparameter Tuning:**  
   - Adjusted the number of clusters to optimize anomaly detection.

### **Conclusion**  
The clustering results provided meaningful insights into stock price patterns, and anomalies were effectively identified using K-Means clustering.

---

## **Summary**  
This project demonstrates the application of time series analysis for forecasting and clustering techniques for grouping and anomaly detection. By combining ARIMA/SARIMAX models with K-Means clustering, the project showcases how different machine learning approaches can solve real-world predictive and analytical problems effectively.
