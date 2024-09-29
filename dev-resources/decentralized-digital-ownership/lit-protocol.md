# Lit Protocol

Lit is a decentralized platform designed to enable developers to create secure and programmable applications without relying on centralized services. It provides tools for user-friendly wallet management, robust encryption, and decentralized compute capabilities, allowing users to control their data and access permissions seamlessly. With features like identity-based encryption and conditional signing, Lit facilitates innovative solutions for digital ownership, privacy-preserving AI, and cross-chain interactions in the evolving web3 ecosystem, empowering users to manage their digital identities and assets securely.

## Table of Contents

- [Key Features](#key-features)
- [Use Cases](#use-cases)
- [How it Works](#how-it-works)
- [References and Links](#references-and-links)
- [README Contributors](#readme-contributors)

## Key Features

- **User Wallets**:
  - Web3 onboarding through social logins and passkeys.
  - Claimable wallets generated from human-readable identities (emails or phone numbers).
  - Session keys for performing actions like signing and decryption without repeated authentication.

- **Decentralized Encryption**:
  - Private data storage with flexible access control rules.
  - Identity-based encryption to safeguard data with client-side encryption.
  - Customizable access control conditions using boolean logic.
  - Support for JWT signing to load dynamic server content.

- **Decentralized Compute**:
  - Serverless signing and compute with Lit Actions for automation and cross-chain messaging.
  - Conditional signing using JavaScript logic to generate signatures based on specified conditions.
  - Fetching off-chain data without trusted third-party oracles.
  - Secure infrastructure featuring tamper-proof code execution.

- **Lit Network**:
  - Utilizes advanced cryptography and peer-to-peer networking for secure non-custodial key management.
  - Distributed trust with multi-party computation (MPC) and threshold secret schemes (TSS) for key shares.
  - Native interoperability across blockchains and systems.

## Use Cases

1. **Identity Management**: Enables selective disclosure of encrypted data and credentials, allowing users to control access to their information.
2. **Developer Tooling**: Provides SDKs for projects like Alchemy and Lens Protocol, facilitating account abstraction, private data handling, and mobile wallet integration.
3. **Data Marketplaces**: Supports protocols like Cheqd and Streamr in creating trustless marketplaces through data encryption.
4. **Content Authenticity and Licensing**: Powers secure signing backend for content storage and licensing, as seen in Blockchain Creative Labs’ Verify platform.
5. **Digital Product NFTs**: Facilitates creative utility for digital assets, including unlockable NFTs and selective decryption for managing intellectual property rights.
6. **User Wallets**: Acts as a decentralized key management solution for various wallet applications, enhancing onboarding experiences across platforms like Telegram and Discord.

## How it Works

- **Lit Nodes**: Lit Protocol is made up of special servers called Lit Nodes, which run securely and keep their internal data hidden. This means no one can see what's happening inside them, ensuring privacy.
- **Key Management**: Each node helps create and handle keys (the digital passwords needed for security) without any one node having the complete key. This is done using a process called [Distributed Key Generation (DKG)](https://developer.litprotocol.com/resources/glossary#distributed-key-generation), where nodes share parts of a key.
- **Consensus**: For any important action, like signing a document, at least two-thirds of the nodes need to agree and work together. This makes it hard for anyone to cheat the system.
- **Secure Hardware**: The nodes use special hardware that keeps data safe and private, preventing unauthorized access or changes to the information.
- **JavaScript Environment**: Each node can run programmed tasks (called [Lit Actions](https://developer.litprotocol.com/resources/glossary#lit-actions)) written in JavaScript, which control how the signing and encryption of data happen.

## References and Links

- [Dev Workshop](https://www.youtube.com/watch?v=TYw6d99qOPc)
- [Awesome Lit Repository](https://github.com/LIT-Protocol/awesome/blob/main/README.md)
- [Installing the Lit SDK](https://developer.litprotocol.com/sdk/installation)
- [Lit Actions SDK Docs](https://actions-docs.litprotocol.com/)
- [Lit SDK Guides](https://developer.litprotocol.com/category/guides)
- [Developer Guides Code](https://github.com/LIT-Protocol/developer-guides-code/tree/master)
- [Lit Hackathon Guide](https://docs.google.com/document/d/1NjpIwfFG60eOpd7MxOU9DYXHey1P8YbYyjDrk9zowIs/edit#heading=h.fufsr34an28c)
- [Sign + Decrypt with Lit](https://spark.litprotocol.com/unlocking-new-possibilities-with-lit-actions/)
- [Using Lit Keys with Telegram Auth](https://github.com/LIT-Protocol/custom-auth-telegram-example/blob/main/README.md)
- [Ecosystem Ideas Page](https://github.com/LIT-Protocol/Ecosystem-Ideas/issues)
- [Projects Building with Lit](https://developer.litprotocol.com/Ecosystem/projects)
- [GitHub](https://github.com/LIT-Protocol)

## README Contributors

[@0xScratch](https://github.com/0xScratch)
