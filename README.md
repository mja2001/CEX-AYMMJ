# CEX-AYMMJ
Full Trading Bot for Solana (SOL), Ethereum (ETH), and Sui (SUI)
# Crypto Trading Bot for Solana (SOL), Ethereum (ETH), and Sui (SUI)

This repository contains a Python-based trading bot for cryptocurrencies on centralized exchanges (CEX) like Binance, as well as basic on-chain trading examples for Solana, Ethereum, and Sui blockchains.

## Features
- **CEX Bot**: Automates trading SOL/USDT, ETH/USDT, and SUI/USDT using technical indicators (ADX for trends, ATR for volatility) with risk management.
- **On-Chain Examples**:
  - Solana: Swaps via Jupiter DEX aggregator.
  - Ethereum: Swaps via Uniswap V3.
  - Sui: Basic transaction builder (adaptable for DEXes like Cetus).
- Educational purpose only—test on testnets and backtest strategies.

## Installation
1. Clone the repo: `git clone https://github.com/yourusername/your-repo-name.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Set up API keys/wallets securely (never commit them).

## Usage
- For CEX bot: Edit `cex_bot.py` with your Binance API keys, then run `python cex_bot.py`.
- For on-chain: Edit private keys (use testnets!), then run the respective scripts.

## Warnings
- Trading involves financial risk; use at your own discretion.
- Handle private keys securely.
- Customize signals and add error handling for production use.

## License
MIT License - see LICENSE file.
