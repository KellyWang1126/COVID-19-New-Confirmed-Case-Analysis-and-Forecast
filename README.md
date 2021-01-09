# COVID-19-New-Confirmed-Case-Analysis-and-Forecast

At the beginning of year 2020, a pandemic disease named COVID-19 started to spread all over the world. Around 6.42 million people confirmed with the disease and 383 thousand people died until today. Unfortunately, the numbers are still increasing. Under the severe situation, this project intends to forecast the new confirmed cases of COVID-19 in the world in order to provide some useful information related to COVID-19 for the unknown future.

The project is based on time series analysis techniques including stationarity transformation, model selection, diagnostic checking and forecast. The final model chosen to do forecast is an ARIMA(1, 1, 6) model. The model past most of the tests and provided an eective forecast to the future situation of COVID-19.

The dataset came from public resources of European Centre for Disease Prevention and Control (ECDC). It recorded the daily new confirmed COVID-19 cases of the world and every country separately. Instead of using the whole dataset, I extracted only the numbers of new confirmed cases of the world and period from 2020-01-01 to 2020-05-31 which contains 153 observations. (The project was done by 06/05/2020)
