# Momentum Finance (MMT) Swap Script
![image](https://github.com/user-attachments/assets/34359bea-2443-4937-8dad-9374a9221ca3)


A powerful automation script designed to facilitate auto swaps tokens on Momentum Finance DEX (https://app.mmt.finance) on the Sui blockchain. This script helps users perform automated swaps to increase trading volume efficiently.

## Features

- Automated token swaps on Momentum Finance
- Supports multiple tokens:
  - SUI (Native token)
  - USDC
  - WAL
  - USDT
- Easy configuration through environment variables
- More features coming soon!

## Installation

1. Clone the repository:
```bash
git clone https://github.com/dexter515/momentum-finance-mmt.git
cd momentum-finance-mmt
```

2. Install dependencies:
```bash
npm install
```

3. Configure environment variables:
   - Change file `env.example` to `.env`
```bash
     cp env.example .env`
```
   - Edit `.env` file in the root directory
   - Add your Sui wallet mnemonic:
```bash
SUI_MNEMONIC=your_wallet_mnemonic_here
```

4. Run the script:
```bash
node index.js
```

## Security Notice

- Never share your mnemonic phrase with anyone
- Keep your `.env` file secure and never commit it to version control
- Always verify transaction details before executing swaps

## Disclaimer

This is an unofficial tool. Use at your own risk. Always verify transactions before confirming them.
