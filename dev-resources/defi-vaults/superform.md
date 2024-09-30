# Superform

[Superform](https://www.superform.xyz/) is a universal yield marketplace designed to simplify the process of discovering, executing, and managing yield opportunities across multiple blockchain networks. It consists of a suite of non-upgradeable, non-custodial smart contracts that serve as a central repository for yield and a routing mechanism for users. With Superform, users can deposit or withdraw assets into any compliant vault from any chain using a single transaction, eliminating the need for complex token swaps or bridging processes. This protocol also enables DeFi protocols to easily list their vaults and manage yield opportunities, making it a powerful tool for both developers and yield seekers in the decentralized finance ecosystem.

## Table of Contents

- [Key Features](#key-features)
- [Use Cases](#use-cases)
- [References and Links](#references-and-links)
- [README Contributors](#readme-contributors)

## Key Features

- **Universal Yield Marketplace**: Superform acts as a non-custodial platform where users can discover, deposit into, and manage yield across multiple blockchain networks.
- **SuperPositions**: When users deposit into a vault, they receive a tokenized representation called a [SuperPosition](https://docs.superform.xyz/periphery-contracts/superpositions), which allows for easy management of yield positions across different chains.
- **Permissionless Vault Listing**: DeFi protocols can easily list their [ERC-4626](https://eips.ethereum.org/EIPS/eip-4626) compliant vaults on Superform without needing extensive development, enabling instant access to users across all supported chains.
- **Cross-Chain Transactions**: Users can deposit or withdraw assets from any chain using any token in a single transaction, simplifying the process of managing yield portfolios.
- **Batch Actions**: Superform allows users to perform multiple actions across different vaults and chains simultaneously, enhancing efficiency.
- **Automated Yield Management**: Users can automate the compounding of their yield positions and manage their portfolios from any chain seamlessly.
- **Modular Architecture**: The platform supports various adapters ([Forms](https://docs.superform.xyz/periphery-contracts/forms)) to accommodate different yield types and protocols, making it versatile for diverse DeFi applications.
- **Enhanced Security**: Superform employs multiple Arbitrary Message Bridges ([AMBs](https://docs.superform.xyz/core-contracts/amb-implementations)) for secure cross-chain transactions and data validation to protect against malicious activities.

## Use Cases

1. **Cross Chain Yield Farming**: Users can leverage Superform to access yield farming opportunities across multiple chains without the need for complex bridging solutions.

2. **Portfolio Diversification**: Investors can diversify their yield portfolios by depositing assets into various vaults on different chains, reducing risk exposure and maximizing returns.

3. **Automated Investment Strategies**: DeFi developers can create automated investment strategies using Superform's modular architecture to optimize yield generation and portfolio management.

4. **Cross-Chain Arbitrage**: Traders can utilize Superform to execute arbitrage opportunities across different chains by leveraging the platform's batch actions and cross-chain transaction capabilities.

## References and Links

- [Dev Workshop](https://www.youtube.com/watch?v=HQQkBmT6x8g)
- [Superform Labs](https://www.superformlabs.org/)
- [Guidelines and Resources](https://github.com/ERC4626-Alliance/vault-bounties)
- [Subgraphs](https://docs.superform.xyz/resources/subgraphs)
- [Infrastructure Integrations](https://docs.superform.xyz/resources/infrastructure-integrations)
- [ERC-4626 Alliance](https://erc4626.info/)
- [Yearn Tokenized Strategy Kit](https://github.com/yearn/tokenized-strategy-foundry-mix)
- [Guide to Create Tokenized Strategies](https://docs.yearn.fi/developers/v3/strategy_writing_guide)
- [Compound V3 Tokenized Strategy](https://github.com/Schlagonia/tokenized-comp-v3)
- [Ajna Leverage Farming Strategy](https://github.com/fp-crypto/yv3-ajna-summerfi-lev-farming)
- [Gearbox Strategy](https://github.com/dudesahn/gearbox-lender/tree/dev)
- [Centrifuge Reference Implementation](https://github.com/centrifuge/liquidity-pools/blob/main/src/ERC7540Vault.sol)
- [GitHub](https://github.com/superform-xyz)

## README Contributors

[@0xScratch](https://github.com/0xScratch)
