# Warden Orderbook Project Overview

## About Warden Orderbook

Warden Orderbook is a cutting-edge decentralized trading platform built on the Ethereum blockchain. By harnessing the power of the Optimistic Ethereum layer, it achieves greater scalability and efficiency. The platform facilitates trading across a variety of ERC-20 token pairs such as OP/USDC, WBTC/USDC, and WETH/USDC, catering to a broad spectrum of trading strategies and preferences.

### Key Features

- **Decentralized Trading**: Offers a secure environment where trading activities are not governed by any central authority, thus ensuring users' privacy and autonomy.
- **Smart Contract Implementation**: Employs smart contracts for efficient trade order management, fee collection, and ensuring operational security.
- **Diverse Token Support**: Facilitates trading in major cryptocurrencies and stablecoins, meeting various investment and trading requirements.
- **Advanced Fee Management**: Features a detailed fee structure with specific roles assigned for fee collection and management, enhancing the platform's financial operations.
- **Security Measures**: Integrates `ReentrancyGuard` and other security protocols to mitigate common vulnerabilities and ensure a secure trading experience.
- **Role-Based Access Control**: Utilizes `AccessControl` for assigning roles and permissions, ensuring a flexible yet secure platform governance.
- **Optimistic Ethereum Integration**: Leverages Optimistic Ethereum to benefit from lower transaction fees and faster processing times, enhancing the trading experience.

Warden Orderbook exemplifies the transformative potential of decentralized finance by merging robust blockchain technology with sophisticated trading mechanisms, thereby creating a marketplace that is secure, transparent, and efficient.

## Deployment Guide

### Trading Pairs and Contract Addresses

#### OP/USDC Pair
- **Contract Address**: [0x718d11531097E3B7c5039a75D6145DA58be1d2cC](https://optimistic.etherscan.io/address/0x718d11531097E3B7c5039a75D6145DA58be1d2cC)

#### WBTC/USDC Pair
- **Contract Address**: [0x69B5Add9f72046D66689044A04Bec351b4765E61](https://optimistic.etherscan.io/address/0x69B5Add9f72046D66689044A04Bec351b4765E61)

#### WETH/USDC Pair
- **Contract Address**: [0xBb3B4661a6A01df8A29dDc4cbCafdfB4B918EBB6](https://optimistic.etherscan.io/address/0xBb3B4661a6A01df8A29dDc4cbCafdfB4B918EBB6)

### Supported Tokens

- **OP Token**: `0x4200000000000000000000000000000000000042`
- **WBTC Token**: `0x68f180fcCe6836688e9084f035309E29Bf0A2095`
- **WETH Token**: `0x4200000000000000000000000000000000000006`
- **USDC Token**: `0x0b2C639c533813f4Aa9D7837CAf62653d097Ff85`

### Compiler Details

- **Solidity Version**: v0.8.19+commit.7dd6d404
