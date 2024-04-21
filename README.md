# Time Series Project (Facebook Popularity Analysis)

Data source: https://www.kaggle.com/datasets/michau96/social-media-popularity-2009-2023

### Abstract

In this project, Facebook popularity between 2009 and 2023 on in a monthly basis is studied.

Three approaches have been followed, using auto.arima() from forecast library, extracting p and q from ACF and PACF of the first difference of data, and using BIC and AIC. Model diagnosis is made for each model to see to what extent the residuals form a white noise for more accurate result

Then a small forecasting is done with a comparaison of RMSE score between all model

### Introduction:

Nowadays, we cannot hide the influence social media made on humans life. Their influence reached an extent it can affect counties politics (like what's happening in Gaza's war now)

So this study aims to see the popularity of the most famous social media - Facebook -