# Streamlit-App-Ganache
Deploy an application on Streamlit to automate Ganache Ethereum transactions

## Description ##
Fintech Finder is an application that customers can use to find fintech professionals among a list of candidates, hire them, and pay them in cryptocurrency (ETH).

Integrating the two files will enable automation of these tasks:

- Generate a new Ethereum account instance by using the mnemonic seed phrase provided by Ganache.

- Fetch and display the account balance associated with the Ethereum account address.

- Calculate the total value of an Ethereum transaction, including the gas estimate, that pays a Fintech Finder candidate for their work.

- Digitally sign a transaction that pays a Fintech Finder candidate, and send this transaction to the Ganache blockchain.

- Review the transaction hash associated with the validated blockchain transaction.

## Streamlit Application and Ganache ##
See the images below detailing application interface and transaction confirmation:

- Selecting candidate and inputting amount of hours for hire in Streamlit.

![x](/Images/Ash_selection.PNG)

- Sending successful payment transaction in Streamlit.

![x](/Images/Ash_tx.PNG)

- Account balance before payment in Ganache.

![x](/Images/Ganache_balance_start.PNG)

- Transaction details in Ganache.

![x](/Images/Ganache_tx.PNG)

- Account balance after payment in Ganache.

![x](/Images/Ganache_balance_end.PNG)