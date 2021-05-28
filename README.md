# Cryptocurrencies

During this project, I helped Accountability Accounting analyze and classify crypto data. They wanted the data cleaned, segmented, and grouped, so they could better understand which cryptocurrencies are the best to invest in. In turn, they can provide better support to their clients by understanding which cryptos show the most promise for the future.

The data used in this project was nowhere near perfect, so I had to prep it to work for the machine learning model. I decided to use an unsupervised machine learning model, because there was no known output. To group the cryptocurrencies, I decided on a clustering algorithm. In this deliverable we used data visualizations to share our findings with the board.

## Preprocessing the Data
I completed initial data pre-processing to remove any cryptocurrencies that are not suitable for being added to the investment portfolio, based on the following criteria:

The cryptocurrency is currently trading
- The cryptocurrency has a working algorithm
- The cryptocurrency does not have any null values in the dataset
- The cryptocurrency has a non-zero number of coins already mined

After removing the cryptocurrencies that do not meet the above criteria, and any unnecessary columns, I created the below DataFrame to hold the clean dataset. There are 532 cryptocurrencies that currently fit my clients investment criteria.



The complete findings of each of these methods are included in the "crypto_clustering" jupyter notebook file attached above.
