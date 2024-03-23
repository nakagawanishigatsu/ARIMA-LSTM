# ARIMA-LSTM
---
## ARIMA-LSTM time series forecasting

将ARIMA模型的残差（即测试集和预测值的差值）作为构建LSTM模型的输入数据的原因是为了利用ARIMA模型对时间序列数据的趋势和季节性进行建模，然后使用LSTM模型来捕捉ARIMA模型无法捕捉到的非线性关系和长期依赖性。
>这里使用了我非常喜欢的NVIDIA公司的股票数据，但是它最近涨得太快了（让我买不起4070S），拟合效果不是非常好？😅
>
>[NVIDIA数据来源](https://finance.yahoo.com/quote/NVDA/history?period1=1552780800&period2=1710633600&interval=1d&filter=history&frequency=1d&includeAdjustedClose=true)

| 饼 | 介绍 |   |
|----|-----|---|
| 面板数据 | 暂时没找到教程 | 无思路（只有stata端的实现教程） |
