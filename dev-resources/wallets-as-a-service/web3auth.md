# Web3Auth

[Web3Auth](https://web3auth.io/) is a user-friendly infrastructure designed to simplify the onboarding of users into decentralized applications (dApps) and Web3 wallets. It enables seamless sign-in experiences through familiar OAuth providers like Google and Twitter, while ensuring users maintain full control of their cryptographic wallets in a non-custodial manner. Importantly, Web3Auth is not a wallet itself; rather, it serves as a foundational layer that enhances wallet functionality by managing user authentication and key management without requiring users to navigate complex blockchain transactions.

## Key Features

- **Wallet Creation**: Enables wallet creation in seconds while ensuring security through non-custodial methods and seed phrase-free setups using [Multi-Party Computation (MPC)](https://web3auth.io/mpc).
- **User-Friendly Login Options**: Supports social logins, allowing new users to create wallets without using seed phrases.
- **Customizable Design**: Provides a white-labeled wallet UI that can be fully customized for brands on both mobile and web platforms.
- **MPC Architecture**: Utilizes distributed partial keys for transaction signing, enhancing security and performance.
- **Account Abstraction**: Simplifies user interactions with blockchain through features like gas-less transactions and mobile External Owned Accounts (EOAs).
- **Headless SDKs**: Offers headless SDK solutions for developers to own the user engagement experience and host it themselves.
- **Fiat-to-Crypto API**: Partners with providers to facilitate cost-effective fiat-to-crypto conversion.
- **Identity Verification**: Allows verification of users through "Sign-in With Ethereum" and [CAIP proposals](https://chainagnostic.org/CAIPs/caip-1) for added security and compliance.
- **Blockchain Agnostic**: Compatible with various blockchains including Ethereum, Bitcoin, Solana, and Aptos.
- **Interoperability**: Facilitates connectivity with popular applications via WalletConnect.
- **Enterprise-Grade Security**: Complies with [SOC2](https://www.exceleron.com/2021/01/07/soc2-compliance-important-vendors/), [CCPA](https://brave.com/glossary/ccpa/), [CPRA](https://www.skyflow.com/post/what-is-cpra-how-can-you-prepare), and [GDPR](https://en.wikipedia.org/wiki/General_Data_Protection_Regulation), with a routinely audited codebase ensuring high security standards.
- **User Engagement Enhancements**: Designed to improve user engagement and onboarding, allowing projects to seamlessly scale their user base.

## How It Works

1. **User Authentication**: Web3Auth allows users to authenticate using familiar social login options (like Google, Facebook), making it easy to access decentralized applications (dApps).

2. **Web3Auth SDK**: Developers integrate Web3Auth into their applications using a Software Development Kit (SDK), which simplifies the login and authentication process.

3. **Key Generation**: When users log in, Web3Auth generates a unique cryptographic key for them. This key is essential for interacting with blockchain networks.

4. **Redirection Process**: Upon initiating the login, users are redirected to the Web3Auth portal where the login process occurs. They then authenticate using their chosen OAuth provider.

5. **Returning to the App**: After successful authentication, users are redirected back to the dApp with a derived key specific to that application.

6. **Single and Multi-Factor Authentication**: Web3Auth supports both single-factor (like social logins) and multi-factor authentication, enhancing security by requiring additional proofs of identity.

7. **Key Sharing**: Web3Auth uses techniques like Shamir's Secret Sharing to split users' keys into multiple shares, which are stored in various secure locations - neither the whole key nor its parts are kept in one place.

8. **Security with Multi-Party Computation**: In its advanced architecture, instead of reconstructing keys, Web3Auth uses Multi-Party Computation (MPC) to perform operations with split keys, enhancing security.

9. **Non-Custodial Wallet Management**: Users maintain control over their private keys, ensuring that no single entity (including Web3Auth) has full ownership. This non-custodial nature increases security and user trust.

10. **Web of Trust**: The decentralized nature of key management creates a "web of trust," where various elements (like trusted devices) are used to manage keys securely.

11. **User-Friendly Experience**: This entire process is designed to be seamless for users—allowing them to interact with dApps without needing to manage complex cryptographic keys manually.

## References and Links

- [Dev Workshop](https://www.youtube.com/watch?v=2R0uhfDfnRE)
- [Quick Start](https://web3auth.io/docs/quick-start?product=PNP&sdk=PNP_MODAL&framework=REACT&stepIndex=1)
- [Plug and Play SDKs](https://web3auth.io/docs/sdk?product=Plug%20and%20Play)
- [Core Kit SFA (Single Factor Authentication) SDKs](https://web3auth.io/docs/sdk?product=Core%20Kit%20SFA)
- [Core Kit MFA(Multi Factor Authentication) SDKs](https://web3auth.io/docs/sdk?product=Core%20Kit%20MFA)
- [Web3Auth Wallet Ecosystem](https://web3auth.io/docs/sdk?product=Wallet%20Ecosystems)
- [Helper SDKs](https://web3auth.io/docs/sdk?product=Helper%20SDKs)
- [Auth Provider Setup](https://web3auth.io/docs/auth-provider-setup)
- [Connecting Blockchains with Web3Auth](https://web3auth.io/docs/connect-blockchain)
- [Various Tutorials and Examples](https://web3auth.io/docs/examples)
- [Numerous Guides](https://web3auth.io/docs/guides)
- [Blog](https://blog.web3auth.io/)
- [Web3Auth Demo/Playground](https://demo.web3auth.io/)
- [GitHub](https://github.com/web3auth)

## README Contributors

[@0xScratch](https://github.com/0xScratch)
