# Desctiprion
The aim of this project is to experiment with a Google stock dataset 
using recurrent neural networks (RNNs) with Long Short-Term Memory (LSTM) cells. 

# Dateset Reference
“Google Stock Prediction,” www.kaggle.com. https://www.kaggle.com/datasets/shreenidhihipparagi/google-stock-prediction/data (accessed Mar. 28, 2024).

# Dataset description
Feature explanation:
symbol : - Name of the company (in this case Google).
*   date :- year and date
*   close:- closing of stock value
*   high:- highest value of stock at that day
*   low:- lowest value of stock at that day
*   open:- opening value of stock at that day
*   volume:- the total number of shares or contracts traded for the stock on the given date
*   adjClose
*   adjHigh
*   adjLow
*   adjOpen
*   adjVolume
*   divCash: This represent any cash dividends paid out by the company on that date
*   splitFactor: This attribute indicate if there was any stock split that occurred on that date and by what factor.
Adjusted features refers to how stock prices are adjusted for corporate actions like stock splits or dividends. In this project the adjusted features droped.