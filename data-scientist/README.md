# Data Scientist at Bruno

Hi ! You have successfully applied to our Data Scientist position. We are glad you are looking to join us. Before we go any further, we would like to look at this exercise so that we can better evaluate your data science skills.

Take your time. You don't have to do everything. You will then meet someone from the Bruno team to comment your work.

## Exercise

### Context

We are trying to forecast the future balance of one's account. We want to be able to forecast the balance on different time horizons. This forecast can then be used within other functions such as smart warnings or our microsaving feature.

### Data

The transactions.csv file has 1 year of historical transactions for about 100 Bruno users. Data in balances.csv is a snapshot of Bruno users current accounts as of February 22nd, 2019.

In transactions.csv, there are 6 columns.
- account ID, ID of the account linked to the transaction
- ID, the ID of the transaction
- channel, the transaction channel
- application date, the date the transaction happened
- amount cents, the amount of the transaction in cents

In balances.csv, there are 2 columns.
- account ID, ID of the account
- balance, the balance of the account in cents

### Questions

Describe the dataset.

*Seasonality*

Write code that generates the time serie of a user balance.

What seasonality can you find in balance time series ?

*Recurring transactions*

A recurring transaction is defined by its amount and its period.

How would identity recurring transactions ?

Write code that generates the recurring transactions of a given user.

*Forecast*

Build a model to forecast the balance of a given user. Explain its parameters.

How would you test the performance of your model.

Write code to forecast the balance of all the users on March 22nd, 2019.
