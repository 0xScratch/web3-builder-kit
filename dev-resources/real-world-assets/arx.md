# Arx

[Arx Research](https://arx.org/) is a pioneering company in the Web3 ecosystem that specializes in creating secure chips and protocols designed to transform physical items into digital assets. These chips can be integrated into a wide variety of products, including fashion items, collectibles, and art, enabling brands and creators to develop perpetual physical crypto assets. By using Arx's technology, these assets maintain their authenticity and provenance on the blockchain without relying on centralized servers, making them secure and tamper-proof. Arx serves as a manufacturing hub for various decentralized autonomous organizations (DAOs) and Web3 projects, facilitating the creation of unique digital experiences tied to physical goods, such as membership cards or interactive merchandise

## Table of Contents

- [Key Features](#key-features)
- [Use Cases](#use-cases)
- [How Arx Works](#how-arx-works)
- [References and Links](#references-and-links)
- [README Contributors](#readme-contributors)

## Key Features

- **AES-Based Security:** Arx primarily uses AES encryption to ensure strong security guarantees. It embeds computations into the encryption scheme without relying on special hardware or trusted execution environments (TEEs)
- **Client-Side Encryption:** Queries are intercepted by client proxies, encrypted, and then forwarded to untrusted servers through server proxies. This setup maintains data integrity and prevents unauthorized access patterns
- **Open ERS Protocol:** Arx supports custom platforms and integrations with services like iyk. Users can build their own experiences or connect existing protocols seamlessly, ensuring flexibility in deployment options
- **Embedded Chips:** Secure chips embedded in items like fashion products, collectibles, art pieces, and membership cards enable decentralized provenance verification. These chips integrate with blockchain technologies to authenticate ownership and history immutably
- **Native Support for Ethereum and Bitcoin:** Arx chips support native [secp256k1](https://en.bitcoin.it/wiki/Secp256k1) signing, allowing seamless integration with popular blockchain platforms. Users can store tokens, create claimable digital physical NFTs, or use these assets in decentralized finance applications

## Use Cases

1. **Hot Wallet Validation:** A HaLo chip can function as a hot wallet to validate ownership of a cold wallet, enhancing security in platforms like [Delegate.cash](https://delegate.xyz/).
2. **Multisig Wallet Integration:** By adding a HaLo chip as a signer in multisig wallets, such as [Gnosis Safe](https://app.safe.global/welcome), organizations can require multiple approvals for transactions, increasing overall security.
3. **Privacy-Preserving Stamps:** HaLo chips can be utilized to distribute privacy-preserving zero-knowledge stamps like [Zupass](https://pse-team.notion.site/Zupass-Stamps-v1-Retrospective-6bd7aa223f4d41cdb59b4ecf8aafb130), allowing users to prove information without revealing underlying data.
4. **Governance Token Distribution:** Arx technology facilitates the distribution of governance tokens to newly formed DAOs in real life, bridging the gap between physical and digital governance.
5. **Physical Access Control:** HaLo chips can be used to unlock doors through chip signatures, providing a secure method for physical access control.
6. **Authenticating Physical NFTs:** The HaLo chip supports the creation of physically backed tokens (PBTs), maintaining authenticity without relying on centralized servers.
7. **Decentralized Identity Verification:** Brands can leverage HaLo chips to create self-certifying products that authenticate their origin on public blockchains, enhancing trust in product authenticity.

## How Arx Works

1. **Cryptographic Identity:** Each Arx secure chip contains a unique cryptographic identity that allows for permissionless on-chain authentication, utilizing [ECDSA](https://cryptobook.nakov.com/digital-signatures/ecdsa-sign-verify-messages) signatures.
2. **Chip Types:** The main chip types include SiLo and [HaLo](https://docs.arx.org/HaLo/overview), both designed to authenticate and perform on-chain actions securely.
3. **Linking Digital Assets:** Users can connect digital assets, such as ERC-20 tokens and NFTs, to chips through custom function calls or escrow contracts that release assets upon signing.
4. **Physically Backed Tokens (PBTs):** [PBTs](https://wagmi.tips/guides/physical-backed-tokens/) are non-fungible tokens that link physical assets immutably on-chain, ensuring transfers can only occur through chip signatures.
5. **Ethereum Reality Service (ERS):** [ERS](https://docs.arx.org/ERS/overview) is an open protocol that resolves secure chips to smart contracts and attests to the creator of each chip, enhancing traceability and trust.
6. **Default Lookups:** Every HaLo chip directs to [vrfy.ch](https://bulk.vrfy.ch/) for lookups on ERS, allowing for efficient resolution of chips to their intended resources.
7. **Demonstration Minting App:** Each HaLo chip comes with a user-friendly minting app that guides users in creating EIP-712 signatures, facilitating the minting of assets on-chain.
8. **Ownership Claims:** The PBT allows chip holders to link content like images and videos to chips while enabling them to claim ownership on-chain through chip signatures.
9. **Decentralized Storage Integration:** Arx supports integration with decentralized storage solutions, ensuring that the data linked to chips remains secure and accessible over time.
10. **Compatibility with Blockchains:** The chips are compatible with multiple blockchains, including Ethereum and Bitcoin, thanks to native secp256k1 signing capabilities.

## References and Links

- [Dev Workshop](https://www.youtube.com/watch?v=vCalkFm7rYg)
- [Getting Started](https://docs.arx.org/#getting-started)
- [LibHaLo](https://github.com/arx-research/libhalo) - Programmatically interact with HaLo tags from the web browser, mobile application or the desktop.
- [Sending Commands](https://docs.arx.org/HaLo/command)
- [Chip Integration](https://docs.arx.org/HaLo/integration)
- [Browser Apps](https://docs.arx.org/Examples/browser-apps)
- [Highlighted Projects](https://docs.arx.org/projects)
- [GitHub](https://github.com/arx-research)

## README Contributors

[@0xScratch](https://github.com/0xScratch)
