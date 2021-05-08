# Blockchain Ledger System

![](Images/bc.png)

You’re a fintech engineer who’s working at one of the five largest banks in the world. You were recently promoted to act as the lead developer on their decentralized finance team. Your task is to build a blockchain-based ledger system, complete with a user-friendly web interface. This ledger should allow partner banks to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger.


---

## Technologies

This project leverages python 3.7 with the following packages:

* [Streamlit](https://streamlit.io/) - Python library for building web interfaces for your Python applications.

---

## Installation Guide

    
To install Streamlit, open a terminal window, and then complete the following steps:

Activate your Conda dev environment.

Run the following command:

    pip install streamlit


---

## Usage

Make the following changes to the Pychain ledger structure:  

1) Create a new data class named Record. This class will serve as the blueprint for the financial transaction records that the blocks of the ledger will store.

2) Change the existing Block data class by replacing the generic data attribute with a record attribute that’s of type Record.

3) Create additional user input areas in the Streamlit application. These input areas should collect the relevant information for each financial record that you’ll store in the PyChain ledger.

4) Test your complete PyChain ledger.


## Outcome 
Video of the deployed Streamlit application: 

![](Images/streamlit.gif)

---

## Contributors

Brought to you by Edgar Coronado

---

## License

MIT