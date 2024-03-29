# Analyzing the crypto market landscape between 2018 and 2021

The goal of this project is to, through data visualiztion, investigate the performance and usability of different cryptocurrencies. 

An article going into a detailed analysis of each plot can be found here:
https://medium.com/coinmonks/is-bitcoin-still-the-king-a-deep-dive-into-the-recent-crypto-landscape-2018-2021-1b849eb704fd

The dataset being used is available at:
https://www.kaggle.com/competitions/g-research-crypto-forecasting/data

The attributes of the dataset are the following:

timestamp - A timestamp for the minute covered by the row.

Asset_ID - An ID code for the cryptoasset.

Count - The number of trades that took place this minute.

Open - The USD price at the beginning of the minute.

High - The highest USD price during the minute.

Low - The lowest USD price during the minute.

Close - The USD price at the end of the minute.

Volume - The number of cryptoasset units traded during the minute.

VWAP - The volume weighted average price for the minute.

Target - 15 minute residualized returns. See the 'Prediction and Evaluation' section of this notebook for details of how the target is calculated.
