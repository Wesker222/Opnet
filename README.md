# Opnet

**Opnet** is a Python automation tool designed to streamline interactions with the OP Network testnet ecosystem. It automates key user workflows such as connecting an OP Wallet, binding social accounts, completing on-chain tasks, interacting with Discord for wallet verification, and performing staking and swapping operations on Motoswap.

## Features

- Automates connection to the OP Network faucet and wallet integration.
- Supports social account binding and task completion on the OP testnet portal.
- Automates Discord interactions for wallet linking and verification.
- Provides groundwork for automating staking, swapping, and token transfers on Motoswap.
- Built using Pyppeteer for browser automation in Python.

## Background

The OP Network (built on OP Stack) enables developers to build scalable Ethereum-compatible Layer 2 chains. Testing on OP Stack chains is similar to Ethereum but requires specific workflows for wallet connection, social verification, and on-chain interactions.

This tool helps automate these repetitive steps to accelerate testing and development on OP testnets.

## Getting Started

### Prerequisites.

- Python 3.8+
- Pyppeteer (`pip install pyppeteer`)

### Installation.

Clone the repository:

```bash
git clone https://github.com/Wesker222/Opnet.git
cd Opnet
pip install -r requirements.txt  # if requirements file exists, else just pyppeteer
```

### Usage

Edit the script to add your OP Wallet public key, social account username, and Discord server/channel IDs.

Run the automation script:

```bash
python opnet_automation.py
```

Follow on-screen instructions for manual steps such as wallet connection and Discord login.

## Notes

- Wallet connection automation may require manual interaction due to browser extension security.
- Discord automation uses web UI interaction; for full automation, consider Discord bot integration.
- Staking and swapping automation on motoswap.org is partially manual and can be extended.

## Resources

- [OP Stack Documentation](https://docs.optimism.io/)
- [OP Network Faucet](https://faucet.opnet.org)
- [OP Network Points Portal](https://opnet.org/points)
- [Motoswap](https://motoswap.org)
- [Discord](https://discord.com)

## Contributing

Contributions and improvements are welcome! Please open issues or submit pull requests.

## License

This project is licensed under the MIT License.

