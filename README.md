# Crypto-Price-Movement-Prediction

This project analyzes high-frequency cryptocurrency order book data collected from four exchanges to predict short-term price movements. Order book data were aligned onto a unified time grid and forward-filled to handle missing observations. Hawkes-process intensity features and cross-exchange buy/sell pressure signals were engineered to capture self-exciting market activity and liquidity imbalances. A supervised multiclass classifier was then trained on over 400,000 observations to predict 5-second price movements as up, flat, or down.
