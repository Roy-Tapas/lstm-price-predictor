# LSTM based Bitcoin Price Predictor
---

This repository contains implementation of Long Short-Term Memory (class of Recurrent Neural Network). Two types of sequence data are used to build two separate LSTM networks. These are (a) Bitcoin past closing prices and (b) Crypto Greed and Fear index.
Both the betworks are with exact same configurations that enables us to compare preformances and evaluate predicitive power of the two types of sequence data.  

Following data analytics areas are are covered in this implementation: 
* Prepare the data for training and testing
* Build and train custom LSTM RNNs 
* Evaluate the performance of each model


## How to run the notebooks <br>
Clone the entire repository - "lstm-price-predictor"  into a local folder by issuing the following command from gitbash <br>
```
$git clone https://github.com/Roy-Tapas/lstm-price-predictor.git
```
Stay in the same gitbash directory and open Jupyter lab by issuing the following command from gitbash: <br>
```
$jupyter lab
```

Implementations are in following notebook in the directory 'lstm-price-predictor':
* lstm_stock_predictor_closing.ipynb
* lstm_stock_predictor_fng.ipynb

## Important points to note 
Retain the folder structure as cloned from github.  
Hierarchy inside repositoy should look like the following:
```
lstm-price-predictor 
        |------------> lstm_stock_predictor_closing.ipynb
        |------------> lstm_stock_predictor_fng.ipynb
        |------------> Resources
                            |-------------------> btc_historic.csv 
                            |-------------------> btc_sentiment.csv

                        
```



<hr style="border:2px solid blue"> </hr>

## Tapas Roy

**Email:** rtapask@gmail.com# lstm-price-predictor