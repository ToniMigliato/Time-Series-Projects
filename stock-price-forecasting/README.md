# Time Series Forecasting

### Forecasting Stock Prices

![]()
Image by <a href="https://pixabay.com/users/moritz320-1260270/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=3346988">moritz320</a> from <a href="https://pixabay.com/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=3346988">Pixabay</a>


# 1. Problem

This problem consists in accomplish some analysis and price forecasts in an asset from the brasilian stock market using the Yahoo Finance library. The asset corresponde to a petroleum enterprise known as PETROBRAS S/A.

# 2. Objective

The goal is to extract patterns and use them in order to preview some future trend in price for the next 5 days. In this analysis I'll use a recurrent neural network (LSTM) to forecast the stocks prices. The performance of the LSTM will be compared to a statistical model, used here as a baseline, known as SARIMA. Besides that, other two studies of forecastings will be accomplished: One aim to show if the opening price of the asset can be used to forecasting the closing price, of the same day. And the second study uses a Machine Learning algorithm to forecast the closing price of the asset of the next day.