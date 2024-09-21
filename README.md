# ArbiFund: Micro-Donation Platform for African Startups

ArbiFund is a decentralized application (dApp) built on the Arbitrum network, designed to facilitate micro-donations to African tech startups. This platform leverages blockchain technology to create a transparent, low-cost, and efficient donation system.

## Features

- List and browse African tech startups
- Make micro-donations using cryptocurrency
- Transparent tracking of donations
- Low transaction costs thanks to Arbitrum's Layer 2 scaling solution

## Technology Stack

- Solidity: Smart contract development
- Foundry: Smart contract testing and deployment
- React: Frontend user interface
- ethers.js: Ethereum wallet and contract interaction

## Prerequisites

- Node.js (v14 or later)
- npm or yarn
- Foundry (for smart contract development and testing)
- MetaMask or another Web3 wallet

## Setup

1. Clone the repository:
   ```
   git clone https://github.com/gboigwe/arbifund.git
   cd arbifund
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Compile the smart contract:
   ```
   forge build
   ```

4. Run tests:
   ```
   forge test
   ```

5. Deploy the contract (make sure you have your Arbitrum testnet configured):
   ```
   forge create --rpc-url $ARBITRUM_RPC_URL --private-key $PRIVATE_KEY src/ArbiFund.sol:ArbiFund
   ```

6. Update the `contractAddress` in `src/App.js` with your deployed contract address.

7. Start the development server:
   ```
   npm start
   ```

## Usage

1. Connect your Web3 wallet (e.g., MetaMask) to the Arbitrum network.
2. Browse the list of startups on the platform.
3. Enter the amount you wish to donate and click the "Donate" button.
4. Confirm the transaction in your Web3 wallet.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Acknowledgements

- This project was created as part of the Web3 Afrika Mini-Hack.
- Thanks to the Arbitrum team for their Layer 2 scaling solution.