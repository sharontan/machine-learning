# S&P 500

We will be using a dataset that consists of historical prices of the S&P 500 index from 1950 to 2015. This datset consists of the following columns:

- Date: The date of the record.
- Open: The opening price of the day (when trading starts).
- High: The highest trade price during the day.
- Low: The lowest trade price during the day.
- Close: The closing price for the day (when trading is finished).
- Volume: The number of shares traded.
- Adj Close: The daily closing price, adjusted retroactively to include any corporate actions.

Due to the nature fof the stock market, three additional time series columns are computed:

- Ave_5: Average prices of the past five days
- Ave_30: Average prices of the past thirty days
- Std_5: Standard deviation of prices over the past five days

We will split the dataset into two:

- Train: data from January 3, 1950 to December 31, 2012
- Test: data from January 1, 2013 to December 7, 2015

We will be using the **Train** dataset to train our model. We will then validate the model using the **Test** dataset.

