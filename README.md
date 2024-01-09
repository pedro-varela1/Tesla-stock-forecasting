# Tesla Stock Price Prediction with LSTM
> By: [Pedro Artur Varela](https://github.com/pedro-varela1)

The purpose of this notebook is to study the application of LSTM with PyTorch in Stock Forecasting. For this, we use the following database available on Kaggle: [Tesla Stock Price](https://www.kaggle.com/datasets/rpaguirre/tesla-stock-price). It contains the following data:
1. The date - "Date"
2. The opening price of the stock - "Open"
3. The high price of that day - "High"
4. The low price of that day - "Low"
5. The closed price of that day - "Close"
4. The amount of stocks traded during that day - "Volume"
5. The stock's closing price that has been amended to include any distributions/corporate actions that occurs before next days open - "Adj[usted] Close"

## Files
- _Tesla.csv_: Data used for analyses.
- _model.py_: LSTM model used for training and predictions.
- _tesla-stock-forecasting.ipynb_: Jupyter Notebook used for data analyses, prepocessing, training and test the data.

## Results

### Plot loss
![Plot Loss](<results/plot_loss.png>)

### Predict Test Prices (Unseen Data)
![Predict Test Prices](<results/predict_prices.png>)
