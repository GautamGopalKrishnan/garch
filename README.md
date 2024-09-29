# GARCH
Mathematical model to predict volatility of stock prices.

Information about GARCH models can be found here in the wiki for this project in this github repository.

## Installation
Install by cloning the repository with

    git clone https://github.com/GautamGopalKrishnan/garch.git

## Volatilities of stock indices
We use historical data and hyperparameter tuning to implement GARCH(1,1) model for the following stock indices.

- NIFTY 50
- NIFTY 100
- NIFTY 200
- NIFTY 500
- NIFTY Next 50
- BSE 500

Historical Data for each of these indices from January, 1990 to August, 2004 is publicly available (courtesy of National Stock Exchange of India for indices owned by NSE). They are available on this github repository and have been used to estimate prices in the future.

## Testing and predictions
- We can use our implementation of the GARCH(1,1) model to predict the future volatilities and we demonstrate it for NIFTY 50.

- We test the robustness of our models by comparing with volatility estimations from rolling averages.

- We also calculate the Ljung-Box statistic to show how our GARCH model largely removes autocorrelation and explains the data.

Details about the Ljung-Box are available on the wiki page for this project in this github repository and can be found here: 
