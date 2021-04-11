# Bitcoin Arbitrage Opportunity Analyzer

This application is an arbitrage opportunity analyzer. It finds the opportunity for profit on arbitrage for Bitcoin being bought on Bitstamp and sold on Coinbase (two cryptocurrency exchange platforms) against a certain period of time. 

It uses two datasets with prices for Bitcoin from 12/31/2015 - 01/07/2019. Then runs three phases of financial analysis:

1. Collect the data
2. Prepare the data
3. Analyze the data

---


## Technologies


Python 3.7.10

Jupyter Lab 3.0.11

Jupyter Notebook 6.2.0

Pandas 1.2.3

Matplotlib 3.3.4

---


## Installation Guide

To install required pandas library run the following command:

    pip install pandas

Install Jupyter with Anaconda. 

To run Jupyter Notebook run this command in directory with notebook file:

    jupyter notebook crypto_arbitrage.ipynb

---


## Usage

Once you run the Jupyter Notebook, click on the first cell then hit:

    Shift + Enter

keys to run the first cell. Keep hitting those keys to run each cell after that and watch what the program does as it runs a financial analysis on the data and generates a report on the discoveries.

---

## Example

Running this cell will produce an overlay plot of the prices of Bitcoin in a certain month on the two different exchanges. 

![Example]()

---
## License

[Click here to view](https://github.com/talibkateeb/Bitcoin-Arbitrage-Opportunity-Analyzer/blob/main/LICENSE)