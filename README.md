# Covid-Variants-Analysis-and-Forecasting
In this project, we analyse the data of covid-19 variants and build a LSTM model to do forecasting.

The dataset is from [Kaggle](https://www.kaggle.com/yamqwe/omicron-covid19-variant-daily-cases).

We fistly load in the data and analyze it via data visualisation. For example, we can know the percentage of the cases of each variant worldwide. We can also see their conntry distribution and time evolution.

<img src="https://raw.githubusercontent.com/JiayuX/Covid-Variants-Analysis-and-Forecasting/main/pie.png" width="600"/>

<img src="https://raw.githubusercontent.com/JiayuX/Covid-Variants-Analysis-and-Forecasting/main/bar.png" width="800"/>

<img src="https://raw.githubusercontent.com/JiayuX/Covid-Variants-Analysis-and-Forecasting/main/area.png" width="800"/>

We then build a LSTM model to do a time series forecasting with the covid cases. Here is the predicted vs original data:

<img src="https://raw.githubusercontent.com/JiayuX/Covid-Variants-Analysis-and-Forecasting/main/pred.png" width="800"/>

Although we have quite limited amount of data, the model can successfully predict the overall increasing trend up to 2021/12/13. However, it failed to predict the abrupt drop from 2021/12/13 to 2022/01/05.

To use a more complex model and get more accurate and reliable forecasting, we need more data to train the model.
