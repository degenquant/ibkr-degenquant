# IBKR Tax Calculator
This tool calculates the tax liability from options and stock transactions.

## Description
This program analyzes the account statement, i.e., the cash flow statement, from Interactive Brokers. It recognizes and sums up or analyzes in detail the following entries:

- Dividends
- Interest
- Stock transactions
- Options transactions (including breakdown into individual trades)
- Deposits and withdrawals
- Currency conversions
- Market data subscriptions

## Usage
This program is available online at: [IBKR Tax Calculator](https://ibkr-steuerrechner.streamlit.app/)

It is hosted on Streamlit Community Cloud. If the program is not active, you can start it using the button displayed in this case.

Alternatively, you can download the program to your own computer and run it there. Basic knowledge of Python is required, and all dependencies are listed in `requirements.txt`. The program is started with the command:

streamlit run src/app.py


## Development
This program is open source. You are invited to make modifications or program extensions and contribute them back via a pull request.

Unit tests can be run locally with the following command:

PYTHONPATH=$PWD/src python -m unittest
