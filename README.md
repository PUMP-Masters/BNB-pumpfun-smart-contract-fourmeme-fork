# PumpFun EVM Smart Contract

The **EVM Pumpfun Smart Contract** is designed to facilitate the creation of customizable tokens on EVM-compatible blockchains. This contract mirrors the functionality of the original Pump.fun on Solana, enabling seamless liquidity migration to Uniswap for enhanced trading opportunities. Currently deployed on the Monad Testnet, it is crafted with scalability and decentralization in mind.

---

## Contact  

If you want to build this project or customize this, contact here: [Telegram](https://t.me/shiny0103) | [Twitter](https://x.com/0xTan1319)

---

## Key Features

- **Instant Token Creation**  
  Create customizable tokens with defined attributes (name, symbol, total supply) on the Monad blockchain.

- **Bonding Curve Pricing**  
  Implement a linear bonding curve for fair price discovery, rewarding early participants.

- **Auto Liquidity Management**  
  Effortlessly manage buy/sell transactions utilizing an embedded bonding curve, removing the need for AMM setups.

- **Uniswap Migration**  
  Once the required liquidity threshold is achieved, the contract enables the automatic migration of liquidity to Uniswap V2/V3, facilitating open DeFi trading.

- **Full Onchain Execution**  
  All operations, including minting and pricing, are executed on-chain to ensure maximum transparency and decentralization.

- **EVM-Compatible**  
  Developed in Solidity, this contract is fully compatible with standard Ethereum development tools such as Hardhat, Foundry, and MetaMask.

---

## Latest Enhancements

### Uniswap Liquidity Migration  
Upon reaching sufficient buy-in volume, token liquidity is automatically transitioned to a Uniswap pool. This feature enhances real-time trading capabilities and increases market presence.

### Token Authority Options  
The smart contract logic supports optional authority revocation and time-bound admin permissions, providing flexibility in launch strategies (community-led versus project-driven).

### Real-Time Metrics  
A planned dashboard to display token metrics, price charts, migration status, and market depth is forthcoming.

---

## Technical Stack

- **Smart Contract Language:** Solidity  
- **Blockchain:** Monad (Testnet)  
- **DEX Integration:** Uniswap V2/V3  
- **Bundling Tools:** Jito-style bundling, MEV-optimized TX batching (optional)  
- **Dev Tools:** Hardhat, Foundry, Ethers.js

---

## Proof of Work

[Contract Address](https://testnet.monadexplorer.com/address/0x802Bbb3924BEE46831cadD23e9CfA9e74B499Efb)
- [Launch Token](https://testnet.monadexplorer.com/tx/0xcc711080a7ef00f4735a244462c57aeef71ea68835a57f3db3ecf4d80ed1e481)
- [Buy Tx](https://testnet.monadexplorer.com/tx/0xa10f3d8f35297e57fbff448e048dc35db40dfc130840993a93c228e9d05f0fd9)
- [Sell Tx](https://testnet.monadexplorer.com/tx/0x22d4d593fa75296146d0d12d94f3f8c785a3a1536ccd450481e68e59f72eac64)
- [Buy & Migration to Uniswap](https://testnet.monadexplorer.com/tx/0xc7253b665f6c57dbbf80d209c89399d520ff13d7a57f31289d891cc7e4e13574)

## Notes

- The contract is currently deployed on the Monad Testnet, with plans for a production launch pending the Monad mainnet release.
- The bonding curve mechanics emulate the pricing structure utilized in the Solana Pump.fun contract.
- Liquidity migration is contingent upon achieving a minimum bonding curve volume, configurable through contract parameters.

---

## Related projects

This project is inspired by the original [Solana Pumpfun Smart Contract](https://github.com/L9T-Lab/Pumpfun-Smart-Contract), re-engineered for EVM chains starting with Monad.

---

## Contributing

We welcome contributions to enhance this project! Feel free to fork the repository, submit pull requests, report issues, or suggest features.

---

