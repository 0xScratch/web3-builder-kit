# Worldcoin

[Worldcoin](https://worldcoin.org/) is an innovative initiative co-founded by Sam Altman, aimed at creating a global identity and financial network that is inclusive and accessible to all. At its core, Worldcoin utilizes biometric technology, specifically iris scans, to establish a unique digital identity known as [World ID](https://whitepaper.worldcoin.org/#world-id). This system allows individuals to verify their humanity without revealing personal information, addressing the challenge of distinguishing humans from AI online. Users can receive a digital currency called [WLD](https://worldcoin.org/worldcoin-token) simply for being verified as unique individuals. The project seeks to enhance economic opportunities globally while ensuring privacy and security through advanced cryptographic methods. Overall, Worldcoin represents a significant step towards a more inclusive digital economy, particularly in regions with limited access to traditional banking systems.

## Table of Contents

- [Key Features](#key-features)
- [Use Cases](#use-cases)
- [How it Works](#how-it-works)
- [References and Links](#references-and-links)
- [README Contributors](#readme-contributors)

## Key Features

- **Proof of Personhood**: This foundational concept ensures that each individual can verify their uniqueness as a human without revealing personal information. This is achieved through biometric iris scans using the [Orb](https://whitepaper.worldcoin.org/#the-orb), a specialized device that captures iris patterns to create a unique identifier known as an IrisCode.
- **World ID**: The digital identity system allows users to authenticate themselves online while maintaining privacy. Users receive a World ID after their iris is scanned, enabling them to prove their human status in various digital interactions without disclosing personal data.
- **Privacy Preservation**: Worldcoin emphasizes user privacy by ensuring that biometric data is not stored in identifiable forms. The iris images are deleted after verification, and only the anonymized IrisCode is kept, which is linked to a public key on the blockchain.
- **World App**: This application serves as the primary interface for users to manage their World IDs and interact with the Worldcoin ecosystem. It allows for seamless integration with other applications, enhancing usability and accessibility.
- **Digital Currency (WLD)**: Users can earn WLD tokens simply for being verified as unique individuals. This cryptocurrency facilitates transactions within the Worldcoin network and aims to promote financial inclusion globally.
- **Global Reach**: Worldcoin aims to establish its network across diverse regions, focusing on areas with limited access to traditional banking systems, thereby enhancing economic opportunities for all individuals.

## Use Cases

1. **Financial Inclusion**: Worldcoin aims to provide universal access to digital financial services, allowing individuals in underserved regions to participate in the global economy. By enabling instant, borderless transactions, it can facilitate remittances and aid distribution more efficiently.
2. **Digital Transactions**: Users can own and transfer digital money securely and efficiently. This capability is particularly beneficial in crisis situations where traditional banking may be inaccessible, allowing for rapid aid distribution and financial support.
3. **Identity Verification**: Worldcoin addresses the growing issue of online identity fraud by offering a reliable proof of personhood solution. This can help filter out bots and spam in digital communications, enhancing the quality of interactions on platforms like social media.
4. **Decentralized Governance**: With its sybil-resistant identity verification, Worldcoin can facilitate more equitable governance models in decentralized applications (dApps). This could lead to fairer decision-making processes that include a broader demographic, reducing the influence of wealth on governance.
5. **Fraud Prevention**: In sectors like e-commerce and loyalty programs, Worldcoin's frictionless identity verification can help align incentives between consumers and businesses, reducing fraud related to coupons and referrals.
6. **Equitable Resource Distribution**: By employing proof of personhood, Worldcoin can enhance the fairness of social welfare programs. This is particularly relevant in developing economies where fraudulent identities often exploit resource distribution systems.
7. **Universal Basic Income (UBI)**: As AI technologies advance, Worldcoin could play a role in implementing AI-funded UBI initiatives. By ensuring that each individual registers only once, it can facilitate equitable distribution of resources generated through AI advancements.

## How it Works

Worldcoin operates through a combination of biometric technology, cryptographic methods, and blockchain infrastructure, centered around the following key components:

- **World ID**: At the heart of Worldcoin is the World ID, a privacy-preserving digital identity that allows individuals to prove their uniqueness as humans. This is achieved through a biometric verification process using a device called the Orb.
- **The Orb**: The Orb is a specialized imaging device equipped with multispectral sensors that capture the unique patterns of an individual's iris. This scan generates an IrisCode, which serves as a unique identifier for the user. Importantly, the raw iris images are deleted immediately after verification to protect user privacy.
- **Identity Wallet**: Users download the World App, which functions as their identity wallet. Upon verification at an Orb, a unique and random private key is generated and securely stored on the user's device. This key is essential for creating a public identity commitment that is recorded on the blockchain.
- **Zero-Knowledge Proofs (ZKPs)**: For every verification request, the user's wallet generates a ZKP. This cryptographic method allows users to prove their identity without revealing their private key or any personal information, ensuring that verifications cannot be linked across different applications.
- **Public Identity Commitment**: The public identity commitment, akin to a public key, is published on-chain, acting as the source of truth for the protocol. However, this commitment does not disclose any identifiable information about the user.
- **Nullifier Hashes**: After successful verification, a unique nullifier hash is returned to the application. This serves as the user's identifier within that specific application and cannot be linked to other transactions or verifications, further enhancing privacy.
- **Decentralized Infrastructure**: Worldcoin's system is designed to be decentralized and inclusive, allowing individuals worldwide to engage in digital interactions without compromising their privacy or personal data.

## References and Links

- [Dev Workshop](https://www.youtube.com/watch?v=plm5YN87FMo)
- [World ID Quick Start Guide](https://docs.worldcoin.org/quick-start/installation)
- [Awesome ZKML Repo](https://github.com/worldcoin/awesome-zkml)
- [WorldID in Action](https://docs.worldcoin.org/try)
- [Developer Portal](https://developer.worldcoin.org/login)
- [Worldcoin Simulator](https://simulator.worldcoin.org/select-id)
- [Template Repositories](https://docs.worldcoin.org/quick-start/templates)
- [Cloud Verfication (Incognito Actions)](https://docs.worldcoin.org/id/cloud)
- [Verifying Proof On-Chain](https://docs.worldcoin.org/id/on-chain)
- [Sign in With World ID](https://docs.worldcoin.org/sign-in)
- [API Reference](https://docs.worldcoin.org/reference/api)
- [Worldcoin Apps](https://worldcoin.org/apps)
- [GitHub](https://github.com/worldcoin)

## README Contributors

[@0xScratch](https://github.com/0xScratch)
