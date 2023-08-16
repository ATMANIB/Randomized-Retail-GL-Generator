# Randomized Retail GL Generator
_Procured by Analytical Ants LLC_

This repository hosts a Python script that generates a randomized, yet logical, general ledger dataset tailored for retail businesses. It's a perfect tool for financial modeling training, educational purposes, and for anyone who needs a quick mock-up of a general ledger without diving deep into manual data entry.

## Features
- Generates ledger entries based on typical retail business transactions, such as sales, inventory purchases, expenses, and more.
- Ensures logical sequencing of transactions. For instance, a sale is often followed by a corresponding deduction in inventory.
- Randomized transaction dates within a span of the past two years, ensuring a realistic time flow.
- Incorporates descriptions for transactions to emulate real-world scenarios.
- Error handling in place to warn users if the output CSV file is already open.

## Structure
The general ledger entries generated include the following fields:

- INDEX: A unique identifier for batches of entries.
- DATE: The date of the transaction.
- ACCOUNT: The account number.
- ACCOUNT DESCRIPTION: A brief descriptor of the account.
- DR (Debit): The debit amount, if any.
- CR (Credit): The credit amount, if any.

Every batch of entries is followed by a transaction description to provide context on the nature of the transaction.

## How to Use
1. Clone the repository.
2. Navigate to the directory containing the script.
3. Run the script using Python: `python your_script_name.py`.
4. A CSV file named `general_ledger.csv` will be generated in the same directory with the randomized ledger entries.

## Contribution
Feel free to fork this repository and make improvements or adapt the script to other industries or specific needs. Pull requests and enhancements are welcome!
