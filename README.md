# AutoStaking-BOT

Automated staking bot for the Autostaking platform on Pharos testnet with intelligent portfolio allocation strategies.


## Features

- 🚀 Automated staking operations on Autostaking platform
- 💼 Multiple professional portfolio allocation strategies
- ⚡ Multi-account support with parallel processing
- 🔄 Proxy rotation with free and private proxy options
- 🔐 Secure authentication with asymmetric encryption
- 📊 Real-time balance monitoring
- ⏱️ Configurable delays between transactions
- 🔍 Transaction explorer links for verification

## Requirements

- Python 3.10+
- Testnet accounts with USDC, USDT, and MockUSD balances
- Internet connection
- (Optional) Proxy list for IP rotation

## Installation

1. Clone the repository:
```bash
git clone https://github.com/allowidn/AutoStaking-BOT.git
cd AutoStaking-BOT
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Add your accounts to `accounts.txt` (one private key per line)

4. (Optional) Add proxies to `proxy.txt` if using private proxies

## Configuration

Edit the following parameters directly in the script or configure during runtime:
- Staking count per wallet
- USDC/USDT/MockUSD amounts
- Min/Max delay between transactions
- Proxy usage options

## Usage

Run the bot:
```bash
python bot.py
```

Follow the interactive prompts to configure:
1. Enter staking count for each wallet
2. Set token amounts (USDC, USDT, MockUSD)
3. Configure delay between transactions
4. Choose proxy option:
   - Free proxies (automatically fetched)
   - Private proxies (from proxy.txt)
   - No proxies
5. Enable proxy rotation if needed

## Portfolio Strategies

The bot implements 6 professional portfolio allocation strategies:

1. **Balanced Strategy**  
   Selects 3 products with best combined APY/TVL ranking

2. **High APY Stability**  
   Focuses on consistent high APY performers

3. **Risk-Adjusted Returns**  
   Optimizes APY/TVL ratio with 4-product diversification

4. **Conservative Approach**  
   Capital preservation with established protocols

5. **Aggressive Growth**  
   Maximizes short-term returns with high APY products

6. **Multi-Strategy Allocation**  
   Combines TVL leaders, top APY, and risk-adjusted products

## Notes

- Testnet RPC: `https://testnet.dplabs-internal.com/`
- Contracts:
  - USDC: `0x72df0bcd7276f2dFbAc900D1CE63c272C4BCcCED`
  - USDT: `0xD4071393f8716661958F766DF660033b3d35fD29`
  - MockUSD: `0x7F5e05460F927Ee351005534423917976F92495e`
  - Staking Router: `0x11cD3700B310339003641Fdce57c1f9BD21aE015`
  
- All operations are performed on Pharos testnet
- Use testnet tokens only

## Disclaimer

This software is provided "as is" without warranty of any kind. Use at your own risk. The developers are not responsible for any financial losses or unintended consequences resulting from the use of this bot. Always test with small amounts first.

## Support

For issues and feature requests, please open an issue on [GitHub](https://github.com/allowidn/AutoStaking-BOT/issues).

---

**Note**: This bot is for educational purposes only. Always comply with the terms of service of the platforms you interact with.
