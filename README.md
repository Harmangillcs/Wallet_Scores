# Wallet Risk Scoring (DeFi / Compound Protocol)

This project assigns a **risk score (0–1000)** to a list of Ethereum wallets based on their simulated activity on the **Compound Protocol (V2/V3)**.

## What It Does

- Loads a list of wallet addresses
- Simulates borrowing, repayment, collateral, and liquidation data
- Creates useful features (like repayment ratio, collateral-to-borrow ratio)
- Normalizes the data and calculates a final risk score for each wallet
- Exports results to a CSV file

##  Technologies Used

- Python
- Pandas
- NumPy
- Jupyter Notebook

## Output

A CSV file:  
```csv
wallet_id,score  
 
