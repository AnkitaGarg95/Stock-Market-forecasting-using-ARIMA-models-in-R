## Stock forecasting for retail giants using ARIMA models in R

The project aims to compare the standing of Walmart, Costco, Kroger and Target by analysing the trends in monthly closing stock prices for these
organizations and to predict the future price values using Autoregressive Integrated Moving Average (ARIMA) models for these
stock prices.

(Refer the report Project_final.pdf for complete explaination of each steps and conclusion reached, please go through appendix to understand the analysis completely)

# The methodology is explained here as:
● Getting the Data: Monthly closing stock prices are collected for the past 15 years for these four companies and stored in a
tidy data format which is manipulated for further analysis. <br>
● Exploratory data analysis: Visual analysis of data pattern and central tendency statistics are observed along with a
background information for each of these retail players. <br>
● Decomposition: Understanding basic time series components by decomposing it into fundamental time series properties.
● Transforming data: Data is transformed using mathematical techniques to make variance stable,i.e. preparing it for better
fits ARIMA models.  <br>
● Stationarity and ACF, PACF plots: Determining data stationarity, plotting ACF and PACF plots to get an intuition for ARIMA
model parameters.  <br>
● Fitting and selecting ARIMA models: Fitting best seasonal ARIMA models (using auto.arima() in R) and evaluating their
performance on out of sample data.  <br>
● Model features selection, forecasting and diagnostics: Understanding the best ARIMA model for a given company and
predicting the stock prices for next three years and performing diagnostic checks on trained models.  <br>
● Conclusion and Future work: The predicted stock prices values are compared across these four companies., results and
limitations of the model and commenting on the forward path from the project outcomes.

# Few snapshots of the above methods are shown below

● EDA
![EDA](/images/EDA.PNG)

● Time series Decomposition into individual components
![Decomposition](/images/Walmart_Time_Series_decomposition.png)

● Stationarity and ACF PACF plots
![Decomposition](/images/ACF_and_PACF_plots_for_seasonality.PNG)

● Prediction with 80% and 95% CI 
![Prediction all ](/images/forecasting_Walmart_montly_closing prices.PNG)

● Prediction results in tabluar form
![Prediction all ](/images/Stock-Market-forecasting_prediction_for_all_four.png)




Format: ![Alt Text](url)
