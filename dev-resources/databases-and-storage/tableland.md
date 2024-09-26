# Tableland

[Tableland](https://tableland.xyz/) is a decentralized network designed to provide relational database capabilities for Web3 applications, addressing the challenges faced by developers when storing application data. Unlike traditional approaches that force developers to choose between fully on-chain solutions or partial Web2 methods, Tableland allows for the storage of structured data in a web3-native environment. It leverages blockchain technology for access control and database instructions, enabling data to be mutable, queryable using familiar SQL syntax, and composable with other tables. This innovative approach empowers developers to create fully decentralized applications without sacrificing functionality, making Tableland an essential component for building robust and scalable Web3 ecosystems.

## Table of Contents

- [Key Features](#key-features)
- [Use Cases](#use-cases)
- [How it Works](#how-it-works)
- [References and Links](#references-and-links)
- [README Contributors](#readme-contributors)

## Key Features

- **Decentralized Database:** Tableland provides a web3-native solution for storing structured relational data, allowing developers to manage data without compromising on decentralization.
- **Cross-Chain Support:** It enables read-only queries across multiple blockchain networks, facilitating the development of multi-chain applications.
- **Access Control:** Offers row-level security and admin controls, allowing developers to manage data access permissions through smart contracts.
- **Real-Time Updates:** Supports monitoring of database changes, enabling applications to react dynamically to data updates.
- **Data Availability:** Data is materialized off-chain to reduce costs while ensuring accessibility.

## Use Cases

1. **Application Data Storage:** Tableland can be used to store user settings, comments, and session data for decentralized applications (dApps), allowing for high-volume data writes on cost-effective chains like Arbitrum Nova.
2. **Dynamic NFTs:** Developers can store dynamic metadata for NFTs in SQL tables, enabling user-controlled changes to NFT attributes and facilitating cross-chain storage for multichain NFTs.
3. **Gaming Data Management:** Tableland can manage game-related data such as global leaderboards, game state, and character inventories, providing a permissionless database for real-time querying.
4. **Data Pipelines and DAOs:** It allows for permissionless storage of datasets required for AI/ML workloads, with access controls integrated to enable collaborative data management within decentralized autonomous organizations (DAOs).
5. **Content Management Systems (CMS):** Tableland can store publicly shared data related to DAO operations or knowledge bases, ensuring open access while maintaining structured data organization.

## How it Works

Tableland operates by decomposing traditional relational database functions into two main components:

1. **On-Chain Registry:** Each table is minted as an ERC721 token on an EVM-compatible blockchain, establishing an on-chain table owner who can set access control logic (ACL) for the table.
2. **Permissionless Database Network:** A network of decentralized databases runs a web3-limited version of SQLite, managing the creation and mutations of tables off-chain.

The interaction between on-chain and off-chain components is facilitated through the Tableland gateway, which allows for off-chain read queries while ensuring core data availability remains on-chain.

### Workflow Overview

1. **Table Creation and Minting:** To use Tableland, a table must first be created and minted on-chain as an ERC721 token at the Tableland registry contract. The deploying address becomes the table owner and can set permissions for other users.
2. **User Interaction with dApp:** When a user interacts with a decentralized application (dApp) to update information in a Tableland table, the dApp calls the Tableland registry smart contract to execute the SQL statement while checking the user's permissions.
3. **Permission Check and SQL Execution:** If the user has the correct privileges, the validator node processes the SQL statement (e.g., inserting or updating data) and broadcasts confirmation to the Tableland network. If the user lacks permissions, no action is taken.
4. **Read Queries:** For read queries, anyone can access table data without restrictions, allowing for open data retrieval.

## References and Links

- [Dev Workshop](https://www.youtube.com/watch?v=oEP0jpTunuU)
- [Workshop Series Playlist](https://www.youtube.com/playlist?list=PLAc0xDyQDZbqTNM3lejUkVdiTprS2Gjob)
- [Documentation](https://docs.tableland.xyz/)
- [QuickStart](https://docs.tableland.xyz/quickstarts/)
- [Tutorials](https://docs.tableland.xyz/tutorials/)
- [Tableland Studio](https://docs.tableland.xyz/studio/)
- [Tableland SDK](https://docs.tableland.xyz/sdk/)
- [Projects Built on Tableland](https://docs.tableland.xyz/showcase)
- [GitHub](https://github.com/tablelandnetwork)

## README Contributors

[@0xScratch](https://github.com/0xScratch)
