# Time-Series
Projetos envolvendo a modelagem de séries temporais

O objetivo desse projeto é comparar os resultados na predição de séries temporais usando métodos da estatística clássica (Holt Winters e ARIMA), o Facebook Prophet, API do Facebbok utilizada para projeção de séries temporais, por fim, transformar um problema de séries temporais em um problema supervisionado, e a partir daí testar outros algoritimos de Machine Learning.

Os dados foram extraídos do Kaggle (https://www.kaggle.com/c/web-traffic-time-series-forecasting).

----------------------

Using public Kaggle data (https://www.kaggle.com/c/web-traffic-time-series-forecasting) on ​​the number of visits to Wikipedia pages, I developed an analysis comparing econometric and machine learning models applied to time series.
In addition to improving my skills with data analysis, this project was important to identify practical advantages in the use of machine learning compared to traditional approaches.
The results obtained were the development of a larger set of variables to improve the predictive capacity of the model, less time in preparing the data for modelling, simultaneous testing with several models to choose the most accurate prediction.

The error metric used in the project was the MAPE (Mean Absolute Percentage Error), a measure of the forecast accuracy of a forecasting method in statistics, for example, in the trend estimation, also used as a loss function for regression problems in machine learning.

The MAPE results and the tested models were as follows:
Modelo / MAPE
FB Prophet (baseline) / 28.5876
Holt Winters / 17.59
ARIMA / 16.0134
FB Prophet w/ all NFL's dates / 29.8722  
FB Prophet w/ all NFL's dates regularized / 29.542
FB Prophet w/ most relevant NFL's dates regularized  / 29.4947
Logistic Regression / 38.71
Ridge Regression / 19.99
Support Vector Regressor / 16.17
Decision Tree Regressor / 22.32
KNN Regressor / 16.32
Random Forest Regressor / 16.09
Light GBM / 22.39
XGBoost / 18.85
LSTM / 20
