# Cryptocurrencies
Module 18 Unsupervised Machine Learning

##  Overview

The porpose of this analysys was to determine which cryptocurrencies are worth trading.The data presented was then cleaned, reducedand then presented using k-means before being visualised.

## Resources

Jupyter Notebook
Pandas
Crypto_data.csv

## Data Preprocessing

The following were done to the initial data:

Remove cryptocurrencies not being traded.
Keep the cryptocurrencies that have a working algorithm
The IsTrading column it was dropped.
Rows that have null value were dropped.
Filter dataset with only mined coins.
Create a new DataFrame CoinNames, and use the index from the previous dataset as the index for this new DataFrame

![Preprocessed Data](https://github.com/hmohabir/Cryptocurrencies/blob/main/Preprocessing.PNG)


### Data reduction

PCA was then applied to further reduce the ddimensions to three components:

![PCA](https://github.com/hmohabir/Cryptocurrencies/blob/main/PCA.PNG)

### K-means

The data was then passed to K-means 

![K-means](https://github.com/hmohabir/Cryptocurrencies/blob/main/k-means.PNG)

There are 4 clusters at the initial data point.

![Scatterplot with PCA Data](https://github.com/hmohabir/Cryptocurrencies/blob/main/Scatter%20with%20PCA.PNG)

They are seen in the scatterplot 

## Results

![Tradable cryptocurrencies](https://github.com/hmohabir/Cryptocurrencies/blob/main/Tradable%20Cryptocurrencies.PNG)

Tradable Cryptos were pulled out and presented as a table

![hvplot](https://github.com/hmohabir/Cryptocurrencies/blob/main/hvplot.PNG)

Coin supply vs coins mines hvplot.
