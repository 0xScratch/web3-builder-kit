# Celestia

[Celestia](https://celestia.org/) is a [modular](https://docs.celestia.org/learn/how-celestia-works/monolithic-vs-modular) [data availability network](https://blog.celestia.org/celestia-a-scalable-general-purpose-data-availability-layer-for-decentralized-apps-and-trust-minimized-sidechains/) designed to enhance blockchain scalability and usability. By decoupling the functions of consensus (ordering transactions) and execution (processing transactions), Celestia allows developers to easily launch their own blockchains tailored to specific needs. It employs a technique called [data availability sampling](https://arxiv.org/abs/1809.09044), which enables [light nodes](https://docs.celestia.org/nodes/light-node) to verify that transaction data is accessible without requiring them to download the entire blockchain. This innovative architecture not only improves efficiency and reduces costs but also increases the overall throughput of the network, making it suitable for a wide range of applications while maintaining security and decentralization

## Table of Contents

- [Key Features](#key-features)
- [Use Cases](#use-cases)
- [References and Links](#references-and-links)
- [README Contributors](#readme-contributors)

## Key Features

- **Modular Architecture**: Separates consensus from execution, enabling customized blockchains (rollups) to utilize its data availability layer.
- **Data Availability Sampling (DAS)**: Allows light nodes to efficiently verify data availability by sampling small portions of blocks, reducing resource requirements.
- **Byzantine Fault-Tolerant Consensus**: Ensures data integrity and availability even in the presence of malicious nodes.
- **Scalability and Performance**: Designed to handle high transaction volumes with low latency, optimizing resource utilization.
- **Interoperability**: Facilitates seamless integration with various blockchain platforms for cross-chain communication.

## Use Cases

1. **Decentralized Applications (dApps)**: Developers can build scalable dApps that utilize Celestia for data availability, allowing them to focus on execution without worrying about underlying data management.
2. **Cross-Chain Interoperability**: Celestia facilitates seamless data sharing and communication between different blockchain networks, enabling use cases such as cross-chain token transfers and decentralized exchanges (DEXs).
3. **Decentralized Finance (DeFi)**: By providing a reliable data availability layer, Celestia supports the development of DeFi protocols that require secure and efficient transaction processing across multiple platforms.
4. **Data Storage Solutions**: Organizations can use Celestia's distributed storage capabilities to securely store sensitive data in a tamper-resistant manner, ensuring redundancy and fault tolerance.
5. **Tokenization Platforms**: Celestia can support asset tokenization projects, allowing for the representation of real-world assets on the blockchain while ensuring their data is securely managed and accessible.
6. **Gaming Applications**: Game developers can leverage Celestia to create blockchain-based games that require high scalability and low latency for real-time interactions among players.
7. **Supply Chain Management**: Celestia can enhance transparency and traceability in supply chains by providing a secure platform for recording transactions and verifying data availability across different stakeholders.

## References and Links

- [Dev Workshop](https://www.youtube.com/watch?v=PaSa6vvbeRk&t=161s)
- [Quick Start Guide for running a Node](https://docs.celestia.org/nodes/quick-start)
- [Build On Celestia](https://docs.celestia.org/developers/build-whatever)
- [Developer Portal](https://celestia.org/build/)
- [Celestia's Networks](https://docs.celestia.org/nodes/participate)
- [Wallet Integrations for Celestia](https://docs.celestia.org/developers/wallets)
- [Rollkit](https://rollkit.dev/) - A sovereign rollup framework for deploying customizable blockchains
- [Awesome Celestia Repo](https://github.com/celestiaorg/awesome-celestia/)
- [Celestia Node API](https://node-rpc-docs.celestia.org/?version=v0.17.1)
- [TIA](https://docs.celestia.org/learn/tia) - Celestia's Native Asset
- [Celestia Ecosystem](https://celestia.org/ecosystem/)
- [GitHub](https://github.com/celestiaorg)

## README Contributors

[@0xScratch](https://github.com/0xScratch)
