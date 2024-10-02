# Fluence

[Fluence](https://fluence.network/) is a decentralized serverless platform and computing marketplace that leverages blockchain technology to offer a scalable, secure, and permissionless alternative to traditional cloud computing services. Often referred to as a "Cloudless Platform," Fluence allows developers to build and deploy applications across a network of diverse compute providers, ranging from professional data centers to personal devices. Unlike centralized platforms, Fluence empowers developers to manage their applications' execution while verifying that computations are performed correctly through on-chain proofs. This innovative ecosystem not only incentivizes providers with cryptographic tokens for their contributions but also fosters a community-driven governance model, enabling users to participate in decision-making processes. Overall, Fluence represents a significant shift towards decentralized application development, enhancing flexibility and trust in the computing landscape.

## Table of Contents

- [Key Features](#key-features)
- [Use Cases](#use-cases)
- [How it Works](#how-it-works)
- [References and Links](#references-and-links)
- [README Contributors](#readme-contributors)

## Key Features

- **Decentralization:** Fluence operates on a peer-to-peer network, eliminating reliance on centralized entities. This structure enhances security and reduces the risk of single points of failure, making it resilient against censorship and manipulation.
- **Permissionless Access:** Anyone can join the Fluence network as either a provider or a customer without undergoing approval processes or identity verification. This open access fosters inclusivity and encourages a diverse range of participants.
- **Censorship Resistance:** The platform is designed to resist censorship, ensuring that users can execute applications without interference from external authorities. This feature is vital for maintaining freedom of expression and protecting against government overreach.
- **Trust Minimization:** Fluence employs cryptographic proofs to authenticate application requests and verify computations. This reduces the need to trust individual providers, as users can rely on the protocol's integrity instead.
- **Collective Governance:** Managed by the [Fluence DAO](https://fluence.dev/docs/learn/governance/overview) (Decentralized Autonomous Organization), the platform allows token holders to participate in governance decisions. This community-driven approach empowers users to influence the development and direction of the network.
- **Economic Incentives:** Providers are rewarded with Fluence tokens for their contributions, creating a competitive marketplace that encourages high performance and reliability. This incentivization model aligns the interests of providers with those of developers and users.
- **Interoperability:** Fluence integrates both Web2 and Web3 data storage solutions, enabling seamless data management for applications. This flexibility allows developers to build diverse applications that leverage existing technologies while benefiting from decentralized advantages.

## Use Cases

1. **Peer-to-Peer Applications**

    Fluence empowers the development of truly decentralized peer-to-peer (P2P) applications that operate without intermediaries. This includes:
    - **Messaging Apps:** Secure and private communication tools that do not rely on central servers.
    - **Social Networks:** Platforms where users control their data and interactions.
    - **Streaming Services:** Decentralized audio and video streaming solutions that enhance user experience while ensuring data privacy.

2. **Decentralized Protocols**

    Fluence simplifies the creation of complex network protocols using the Aqua programming language. Use cases include:
    - **Messaging Protocols:** Building robust communication frameworks.
    - **Consensus Mechanisms:** Developing systems for agreement among distributed nodes.
    - **File Sharing Solutions:** Enabling secure and efficient file distribution without central control.

3. **Community-Run Applications**

    With Fluence, applications can be hosted and managed collectively by community members, eliminating the need for centralized administration. Examples include:
    - **DAO-Managed Platforms:** Social media or content-sharing platforms governed by decentralized autonomous organizations.
    - **Creator Economy Tools:** Applications that empower creators to monetize their work without intermediaries.

4. **Computations on Decentralized Data**

    Fluence supports dynamic computations on data stored in decentralized systems like IPFS (InterPlanetary File System). This includes:
    - **Decentralized Applications (dApps):** Apps that leverage decentralized storage for enhanced security and performance.
    - **Mutable NFTs:** Non-fungible tokens that can be updated or modified over time.

5. **Cloud-Native Computing**

    Fluence enables cloud-native applications to manage microservices without relying on a central server, allowing for:
    - **Distributed Microservice Orchestration:** Efficiently coordinating multiple services across the network.
    - **Serverless Architectures:** Running applications without managing server infrastructure, reducing operational complexity.

6. Blockchain Infrastructure

    Fluence optimizes blockchain-related applications by moving certain operations off-chain to reduce costs and improve efficiency. Use cases include:
    - **Cryptocurrency Exchanges:** Facilitating trades while minimizing gas fees.
    - **Multi-Signature Wallets:** Enhancing security for cryptocurrency transactions.

## How it Works

### The Protocol

1. **Fluence Network Overview:** This network is designed to run computations through a process called the Aqua protocol, which allows secure and distributed task execution. Think of Aqua as a set of rules that help computers work together while ensuring that everything is safe and verifiable.

2. **Cloudless Functions:** When you use [Aqua](https://fluence.dev/docs/aqua-book/introduction) to create code, these codes are called Cloudless Functions. They can run across different clouds and servers without needing a centralized management system. This code can handle functions like finding services, managing tasks, and balancing loads across resources, making sure everything runs smoothly.

3. **Compute Functions and Marine:** To perform the actual computations, the Fluence network uses [Marine](https://fluence.dev/docs/marine-book/introduction), which is a runtime environment that operates on WebAssembly. Marine allows the execution of code similar to traditional serverless functions, where tasks can be processed by various servers. Developers can write code in languages like Rust and C++ to create these functions.

4. **Subnets:** To ensure reliability, the protocol uses something called [Subnets](https://fluence.dev/docs/build/glossary#subnet), which are groups of replicated Compute Functions. If one node (or computer) fails, others in the Subnet can take over, ensuring that the tasks are still completed. This potential for replication helps manage data storage efficiently.

5. **Proofs of Compute:**

    Every task that is executed in the Fluence network generates cryptographic proofs. These proofs validate that the work done is correct, ensuring that customers only pay for computations that are verified.
    - **Aqua Security:** Every time a Cloudless Function is called, the process checks that everything is operating correctly before moving forward. If any part of the process isn't validated, it will stop, ensuring that nothing faulty gets executed.

    - **Proof of Processing and Execution:** This method ensures that all tasks executed in the network are validated. If providers want to earn rewards, they must show proof of their task execution.

### The Marketplace

Fluence has an open marketplace where customers can find compute providers and pay for the resources they need. This marketplace works directly with the Fluence network, enabling smooth transactions and resource rentals.

1. **Proof of Capacity:** Providers in the network must prove they have the necessary hardware available to fulfill requests. They continuously generate proofs demonstrating their computing power is ready for customers.

2. **Resource Pricing and Billing Model:** Customers can pick providers based on price and requirements. Payments occur upfront for using the resources over time, with the rental cost calculated based on how long the resources are employed. Additional billing models will be introduced later.

## References and Links

- [Dev Workshop](https://www.youtube.com/watch?v=PxQPDXmd9Sc&t=1s)
- [Getting Started](https://fluence.dev/docs/build/overview/getting_started)
- [Setting Up](https://fluence.dev/docs/build/setting-up/setting_up)
- [Fluence Quickstart](https://github.com/fluencelabs/examples/tree/main/quickstart)
- [Fluence Examples](https://github.com/fluencelabs/examples)
- [Cloudless Scheduler](https://fluence.dev/docs/build/how-to/schedule_functions)
- [Awesome Community Contributions](https://github.com/fluencelabs/examples/tree/main/community)
- [GitHub](https://github.com/fluencelabs)

## README Contributors

[@0xScratch](https://github.com/0xScratch)
