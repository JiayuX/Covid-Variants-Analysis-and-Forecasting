# Covid-Variants-Analysis-and-Forecasting
In this project, we analyse the data of covid-19 variants and build a LSTM model to do forecasting.

The dataset is from [Kaggle](https://www.kaggle.com/yamqwe/omicron-covid19-variant-daily-cases).

We fistly load in the data and analyze it via data visualisation. For example, we can know the percentage of the cases of each variant worldwide. We can also see their conntry distribution and time evolution.
<img src="https://raw.githubusercontent.com/JiayuX/Covid-Variants-Analysis-and-Forecasting/main/pie.png" width="400"/>
<img src="https://raw.githubusercontent.com/JiayuX/Covid-Variants-Analysis-and-Forecasting/main/bar.png" width="400"/>
<img src="https://raw.githubusercontent.com/JiayuX/Covid-Variants-Analysis-and-Forecasting/main/area.png" width="400"/>

We then build a simple LSTM model to do a time series forecasting with the covid cases. Here is the predicted vs original data:
<img src="https://raw.githubusercontent.com/JiayuX/Covid-Variants-Analysis-and-Forecasting/main/predict.png" width="400"/>

