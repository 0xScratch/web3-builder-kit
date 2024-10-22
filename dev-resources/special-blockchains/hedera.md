# Hedera

[Hedera](https://hedera.com/) is a public distributed ledger technology that employs a unique consensus mechanism known as [hashgraph](https://hedera.com/learning/hedera-hashgraph/what-is-hashgraph-consensus?). Unlike traditional blockchains, which rely on proof-of-work, Hedera operates on a proof-of-stake model, enabling it to achieve high transaction speeds—processing hundreds of thousands of transactions per second—while maintaining security and fairness. Its core services include Solidity-based smart contracts, which allow developers to create decentralized applications, and the [Hedera Token Service](https://docs.hedera.com/hedera/sdks-and-apis/deprecated/sdks/token-service), facilitating the minting and management of both fungible and non-fungible tokens. Governed by a council of leading global organizations, Hedera emphasizes decentralization and community-driven decision-making, making it an innovative option in the Web3 ecosystem for building scalable and efficient applications.

## Table of Contents

- [Key Features](#key-features)
- [Use Cases](#use-cases)
- [How it Works](#how-it-works)
- [References and Links](#references-and-links)
- [README Contributors](#readme-contributors)

## Key Features

- **Decentralized Governance:** Managed by a council of leading enterprises, universities, and Web3 projects, ensuring a collusion-resistant and decentralized decision-making process.
- **Asynchronous Byzantine Fault Tolerance (aBFT):** Provides high security and resilience against malicious attacks, allowing the network to reach consensus even if up to one-third of nodes act dishonestly.
- **High Throughput and Fast Finality:** Capable of processing hundreds of thousands of transactions per second with immediate finality, making it suitable for real-time applications.
- **Low and Predictable Fees:** Transaction costs are low and consistent, typically around $0.0001 USD, which enhances accessibility for developers and users.
- **Performance-Optimized Ethereum Virtual Machine (EVM):** Supports Solidity-based smart contracts that are optimized for speed and efficiency on the Hedera network.
- **Fair Transaction Ordering:** Consensus timestamps ensure fair ordering of transactions, preventing any single node from influencing the outcome.
- **Robust Codebase:** Built for scalability and reliability across its network infrastructure, ensuring that it can support a wide range of applications.
- **Open Source:** The Hedera codebase is open-source under the Apache 2.0 license, promoting transparency and community collaboration.

## Use Cases

1. **Real-World Asset Tokenization:** Hedera simplifies the tokenization of physical and digital assets, making them liquid, fractional, and transparent.
2. **Consumer Engagement & Loyalty:** Brands can issue NFT membership and reward tokens in real-time, enhancing customer engagement and trust through loyalty programs.
3. **Sustainability Solutions:** Leverage Hedera's low-energy network to build and deploy applications focused on sustainability, benefiting from its carbon-negative commitment.
4. **Decentralized Finance (DeFi):** Create or migrate decentralized exchanges, lending protocols, and other financial services using performance-optimized EVM smart contracts.
5. **Decentralized Identity Management:** Securely manage decentralized identity in a privacy-respecting manner, allowing users to control their personal information.
6. **Decentralized Logs:** Generate scalable and verifiable logs of data with native consensus timestamps for applications like supply chain tracking and IoT data management.
7. **Non-Fungible Tokens (NFTs):** Develop NFT marketplaces or communities to mint unique tokens representing digital media, physical assets, or collectibles.
8. **Payments:** Facilitate secure, real-time payments using HBAR or other cryptocurrencies with ultra-low transaction costs.

## How it Works

### 1. **Hashgraph Processing of a Transaction**

The process begins when a client creates a transaction:

- The transaction is cryptographically signed by the account responsible for paying the associated fees. Additional signatures may be required based on account properties.
- The client specifies the maximum fee they are willing to pay and, for smart contract operations, the maximum amount of gas.
- After signing, the transaction is submitted to any node on the Hedera network.
- The receiving node processes the transaction (e.g., verifying sufficient balance) and, if successful, submits it for consensus by adding it to an event and gossiping that event to other nodes.
- This event rapidly propagates through the network via the [gossip protocol](https://docs.hedera.com/hedera/core-concepts/hashgraph-consensus-algorithms/gossip-about-gossip), with each node independently calculating a consensus timestamp based on when they received the event.

### 2. **Public Ledger**

Hedera operates as a public ledger of transactions:

- It functions as a highly secure and distributed database accessible for reading and writing by all users.
- Each node stores a copy of the ledger that only retains the latest state, promoting trust through distributed consensus.

### 3. **Network Nodes**

The public ledger is maintained on the mainnet, which consists of:

- **Consensus Nodes**: Responsible for validating transactions and maintaining the latest state of the network. These nodes will transition to being permissionless in the future.
- **Mirror Nodes**: Offer developers a cost-effective solution for storing and querying historical data for analytics.

### 4. **Hedera Network Services**

Hedera provides a set of APIs that facilitate various functionalities:

- **Token Service**: Allows minting and management of fungible and non-fungible tokens (NFTs) for payments or digital collectibles.
- **Consensus Service**: Records immutable, verifiable event logs suitable for any application or permissioned blockchain framework.
- **Smart Contract Service**: Enables deployment of Solidity smart contracts to create decentralized applications (dApps).

Each API call incurs a predictable transaction fee based on processing needs. Hedera SDKs support popular programming languages like JavaScript, Java, and Go.

### 5. **Decentralized Applications**

Applications leveraging Hedera's public ledger foster greater transparency and trust:

- They enable innovative solutions such as direct payments to artists in music streaming services or decentralized ad networks that eliminate the need for audits.
- These applications collectively enhance network effects on Hedera, contributing to a more fair, secure, and decentralized future.

By utilizing hashgraph technology and robust network services, Hedera positions itself as a leading platform in the Web3 ecosystem.

## References and Links

### Learning Resources

- [Dev Workshop](https://www.youtube.com/playlist?list=PLcaTa5RR9SuBse39syxvMWCaWXVe4eyBj)
- [Getting Started](https://docs.hedera.com/hedera/getting-started)
- [Hedera Developer Course](https://hashgraphdev.com/?code=docs.hedera.com)
- [Tutorials](https://docs.hedera.com/hedera/tutorials)
- [Hedera Coding Tutorials](https://www.youtube.com/playlist?list=PLcaTa5RR9SuA__8rzCKru8Y_F6iMJPEUD)

### Developer Tools

- [Hedera Token Service](https://hedera.com/token-service)
- [Hedera Smart Contracts Service](https://hedera.com/smart-contract)
- [Stablecoin Studio](https://hedera.com/stablecoin-studio)
- [Asset Tokenization Studio](https://hedera.com/asset-tokenization-studio)
- [NFT Studio](https://docs.hedera.com/hedera/open-source-solutions/nft-studio)
- [Developer Toolings & Integrations](https://hedera.com/ecosystem/developer-tooling-integrations)
- [Hedera SDKs](https://docs.hedera.com/hedera/sdks-and-apis/sdks)

### Ecosystem

- [Hedera Networks](https://docs.hedera.com/hedera/networks)
- [HBAR](https://hedera.com/hbar) *(Hedera's native cryptocurrency)*
- [Hedera Ecosystem](https://hedera.com/ecosystem)

### Support

- [Awesome Hashgraph Repository](https://github.com/hashgraph/awesome-hashgraph)
- [Hedera Hivemind GPT](https://chatgpt.com/g/g-TuVHDmAdq-hedera-hivemind)
- [Hedera Hackathon Starter Cheatsheet](https://github.com/hedera-dev/hedera-cheatsheets/blob/master/hedera-hackathon-starter-cheat-sheet-v1.pdf)
- [GitHub](https://github.com/hashgraph)

## README Contributors

[@0xScratch](https://github.com/0xScratch)
