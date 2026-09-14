# Crypto-Price-Movement-Prediction

This project analyzes high-frequency cryptocurrency order book data collected from four exchanges to predict short-term price movements. Order book data were aligned onto a unified time grid and forward-filled to handle missing observations. Hawkes-process intensity features and cross-exchange buy/sell pressure signals were engineered to capture self-exciting market activity and liquidity imbalances. A supervised multiclass classifier was then trained on over 400,000 observations to predict 5-second price movements as up, flat, or down.

## Data

Due to the large size of the high-frequency cryptocurrency order book dataset, the raw data files are not included in this repository.

The dataset contains high-frequency order book observations collected from four cryptocurrency exchanges. During preprocessing, the raw observations were aligned onto a unified time grid and forward-filled to handle missing timestamps. The processed data were then used to construct Hawkes-process intensity features and cross-exchange order book signals for short-term price movement prediction.

The analysis code and methodology are provided in this repository, but the full dataset is omitted because of its storage size.
