# Kinto

[Kinto](https://www.kinto.xyz/) is an innovative Layer 2 blockchain network built on Ethereum that bridges the gap between traditional finance (TradFi) and decentralized finance (DeFi). It is designed to support both financial institutions and DeFi protocols by providing a secure, compliant, and user-friendly environment. Kinto integrates essential features such as Know Your Customer (KYC) verification and fraud monitoring at the blockchain level, ensuring that all participants are verified and compliant with regulations. This unique approach allows for seamless interactions between TradFi and DeFi, enabling users to access a wide range of financial services while minimizing regulatory risks. With its focus on safety, transparency, and community governance, Kinto aims to create a more interconnected financial ecosystem that benefits users, developers, and investors alike.

## Table of Contents

- [Key Features](#key-features)
- [Use Cases](#use-cases)
- [How it Works](#how-it-works)
- [References and Links](#references-and-links)
- [README Contributors](#readme-contributors)

## Key Features

- **KYC & AML Compliance:** Kinto implements Know Your Customer (KYC) and Anti-Money Laundering (AML) protocols at the blockchain level. All participants are verified, ensuring that transactions are conducted only by compliant users. Personal information is securely stored off-chain and can only be linked to on-chain accounts at the user's discretion.
- **Built-in Insurance:** The network provides insurance against unexpected events for all smart contracts and applications built on Kinto. This feature enhances user confidence by mitigating risks associated with potential failures.
- **Default Revenue Stream:** Kinto introduces Contract Secured Revenue, where sequencer fees are distributed among smart contracts based on their transaction volume, creating a sustainable revenue model.
- **Account Abstraction:** Users can engage with Kinto's services without the complexities of traditional crypto wallets, such as seed phrases or browser extensions. This feature allows for easy onboarding through familiar methods like username/password or two-factor authentication while maintaining non-custodial ownership.
- **Full On-chain Governance:** Governance is managed entirely on-chain, allowing community members to vote on critical parameters, treasury management, and integrations. This ensures transparency and accountability in decision-making.
- **Focus on Financial Use Cases:** Kinto is dedicated to financial applications, providing a robust infrastructure that connects seamlessly with major DeFi protocols and oracles, facilitating the development of innovative financial products.
- **Enhanced Security Measures:** The network prevents anonymous exploits by enabling the identification of wallet owners in case of hacks. This feature significantly reduces the risk of fraud and enhances overall security.

## Use Cases

1. **Asset Management Protocols:** Create platforms that offer access to real-world assets through tokenization, allowing for easier management and trading.
2. **Investment Clubs:** Develop applications where users can pool funds to invest collectively in various digital assets, enhancing community-driven investment opportunities.
3. **Secondary Offering Markets:** Facilitate liquidity for employees and early investors in private companies through compliant tokenized securities.
4. **Tokenized ETFs:** Implement traditional exchange-traded funds (ETFs) as liquidity providers within automated market makers (AMMs), bridging traditional finance with DeFi.
5. **Mortgage Automation:** Link banks to wallets for automatic approval and issuance of mortgages using tokenized assets as collateral, streamlining the lending process.

## How it Works

### 1. Network Architecture

- **Arbitrum Nitro Stack:** Kinto is built on the [Arbitrum Nitro stack](https://docs.arbitrum.io/how-arbitrum-works/why-nitro), an open-source development framework that enhances scalability and efficiency. It functions as an Optimistic Rollup, settling transactions on the Ethereum mainnet while maintaining a fully compatible Ethereum Virtual Machine (EVM).
- **Transaction Processing:** Kinto collects sequencer fees from all transactions. The network's profit comes from the difference between these fees and the costs associated with settling batched transactions on Ethereum.

### 2. KYC Architecture

- **Identity Nodes:** These specialized nodes perform KYC-related tasks, ensuring that only verified users can transact on the network. They interact with a smart contract called [Kinto ID](https://docs.kinto.xyz/kinto-the-safe-l2/general/terminology#kinto-id), which mints non-transferable NFTs to users who complete the KYC process.
- **KYC Providers:** Users select from approved KYC providers (e.g., [Plaid](https://plaid.com/products/identity-verification/), [Onfido](https://onfido.com/use-cases/kyc/), [Synaps](https://synaps.io/)) to verify their identity. Personal data is stored securely by these providers, ensuring that it cannot be linked to on-chain identities without user consent.

### 3. User Privacy

- **Data Management:** Kinto does not store any user data directly. Instead, personal information is kept by chosen KYC providers, protecting users in case of data breaches.
- **Kinto ID NFT:** This unique NFT grants users access to the network and indicates their KYC status without revealing personal data. Each user can only hold one NFT, enhancing security against Sybil attacks.

### 4. Transaction Process

- **Creating a Wallet:** Users must complete the KYC process to create a wallet on Kinto. Once verified, they receive their Kinto ID NFT and can begin transacting.
- **Delegated Addresses:** Users can create secondary addresses linked to their primary identity, allowing for flexible transaction management while maintaining security.

### 5. Security Features

- **Built-in Insurance:** Kinto offers insurance against unforeseen events for all smart contracts operating on its network, enhancing user confidence.
- **Emergency Protocols:** In cases of identity theft or hacks, governance can access information about malicious actors to assist authorities.

### 6. User Experience Enhancements

- **Account Abstraction:** Users interact with Kinto through a simplified interface that eliminates the need for seed phrases or browser extensions. This approach allows for easier onboarding and transaction management.
- **Non-Custodial Wallets:** All users must utilize a non-custodial wallet, ensuring they retain control over their assets while benefiting from enhanced security measures.

### 7. Governance

- **On-chain Governance:** The network is governed by a community-driven model where token holders elect guardians to oversee treasury management and protocol parameters, ensuring transparency and accountability.

## References and Links

- [Dev Workshop](https://www.youtube.com/watch?v=9lBtoD-e3e8&t=150s)
- [Podcasts, media appearances and articles featuring Kinto](https://docs.kinto.xyz/kinto-the-safe-l2/general/links)
- [Development Guide](https://docs.kinto.xyz/kinto-the-safe-l2/building-on-kinto/development-setup)
- [Interacting with your Kinto App](https://docs.kinto.xyz/kinto-the-safe-l2/building-on-kinto/interacting-with-your-kinto-app)
- [React SDK Sample Application](https://github.com/KintoXYZ/react-sdk-sample)
- [Kinto Wallet Web SDK](https://docs.kinto.xyz/kinto-the-safe-l2/building-on-kinto/kinto-wallet-web-sdk)
- [List of Tools to enhance developer experience](https://docs.kinto.xyz/kinto-the-safe-l2/building-on-kinto/tools)
- [Kinto Token](https://docs.kinto.xyz/kinto-the-safe-l2/governance/kinto-token)
- [GitHub](https://github.com/kintoxyz)

## README Contributors

[@0xScratch](https://github.com/0xScratch)
