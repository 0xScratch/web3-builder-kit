# Galadriel

[Galadriel](https://galadriel.com/) is the first Layer 1 blockchain designed for decentralized AI applications, enabling developers to create AI apps and agents that work like smart contracts on Ethereum. It offers high speed and low costs through its parallel-execution EVM stack and uses teeML for efficient, verifiable AI processing. Galadriel aims to empower developers by eliminating the risks of centralized AI platforms, promoting user ownership and democratic governance of AI technology, ensuring that its benefits are shared more widely rather than controlled by a few large companies.

## Table of Contents

- [Galadriel's Mission](#galadriels-mission)
- [Key Features](#key-features)
- [Use Cases](#use-cases)
- [How it Works](#how-it-works)
- [References and Links](#references-and-links)
- [README Contributors](#readme-contributors)

## Galadriel's Mission

To build safe, citizen-owned AI by establishing a decentralized infrastructure for AI applications. This mission can be summarized in the following key points:

- **Build the first Layer 1 blockchain for AI:** Acts as a settlement layer for AI, driving real GDP growth.
- **Provide direct ownership and democratic governance over AI:** Ensures that users have control and say in how AI is governed.
- **Become the most secure platform for AI deployment:** Establishes a robust safety network where crypto-incentives align humanity with AI development.

## Key Features

- **Decentralized AI Applications:** Enables developers to build AI apps and agents that operate on-chain, similar to smart contracts.
- **High Throughput and Low Latency:** Built on a parallel-execution EVM stack, which allows for efficient processing of AI tasks.
- **teeML Integration:** Utilizes Trusted Execution Environment Machine Learning (teeML) for low-cost, verifiable AI inference, allowing querying of both open and closed-source large language models (LLMs).
- **Familiar Developer Experience:** Provides a development environment that is similar to Solidity, making it accessible for Ethereum developers.
- **User Ownership and Governance:** Promotes direct ownership and democratic governance over AI applications, ensuring that users have control over their AI tools.

## Use Cases

1. **On-chain ChatGPT:** A decentralized application (dApp) that allows users to chat with an AI model on-chain, with conversations stored directly on the blockchain.
2. **AI-Powered Gaming:** Interactive games, such as the "VitAIlik" RPG, where users battle against a powerful on-chain AI, dynamically generated using large language models (LLMs) and image generation tools like DALL-E.
3. **AI-Generated NFTs:** dApps that utilize text-to-image AI models to create unique NFTs based on user prompts, allowing for personalized contributions to NFT collections.
4. **AI Agents:** Versatile agents capable of performing tasks such as web searching and report generation, providing detailed insights and research capabilities based on user-defined parameters.
5. **Agent Swarms:** Coordinated groups of AI agents that can work together to accomplish complex tasks or simulations in various domains.

## How it Works

Galadriel enables the creation of decentralized AI applications, particularly AI agents, by using an oracle that facilitates communication between smart contracts and external AI models. Here’s a simplified overview of how it works:

### Key Components

- **Oracle:** The core component that allows smart contracts to make asynchronous calls to external APIs, including large language models (LLMs) and other tools. It operates in a [trusted execution environment (TEE)](https://evervault.com/blog/what-is-a-trusted-execution-environment-tee) to ensure secure and verifiable processing.

### Functionality

1. **API Calls:** The oracle can call LLMs and other models, enabling developers to integrate advanced AI capabilities into their applications.
2. **Data Storage:** It allows for the permanent storage of data, which can be retrieved on-demand, enhancing the AI's ability to learn and adapt.
3. **External Service Integration:** The oracle can make requests to external services, like search engines, to provide real-time information.
4. **Long-Running Processes:** Galadriel supports extended execution times necessary for complex AI tasks, allowing for iterative processing that improves reasoning.

### Execution Flow

When building an AI application on Galadriel:

- **Asynchronous Calls:** Unlike typical contracts that return results immediately, calls to the oracle are asynchronous. Developers use callback functions to handle results once the oracle processes the request off-chain.
- Example Process:
  - A smart contract requests an image from a generative model (e.g., DALL-E).
  - The oracle processes this request off-chain and retrieves the result.
  - Once ready, the oracle calls back the contract with the result.

### AI Agents

For more complex applications like AI agents, the oracle allows for iterative decision-making:

- Agents can loop through actions based on previous outputs until a task is completed or terminated.
- This is achieved using callback functions that dictate the next steps based on the agent's logic.

### Security

The oracle runs within a TEE (specifically AWS Nitro Enclaves), ensuring that all operations are secure and verifiable. This setup generates a private key used for signing transactions and posts attestations on-chain to confirm correct execution.

**By combining these elements, Galadriel provides a powerful framework for developing decentralized AI applications that are both secure and capable of complex interactions.**

## References and Links

- [Dev Workshop](https://www.youtube.com/watch?v=4Vz3aoEmoDs)
- [Quickstart](https://docs.galadriel.com/quickstart)
- [Tutorials](https://docs.galadriel.com/tutorials/simple_llm)
- [Galadriel Playground](https://teeml.galadriel.com/)
- [LLMs](https://docs.galadriel.com/teeML-features)
- [Example Contracts](https://github.com/galadriel-ai/contracts/tree/main/contracts/contracts)
- [Dev Docs](https://docs.galadriel.com/overview)
- [GitHub](https://github.com/galadriel-ai)

## README Contributors

[@0xScratch](https://github.com/0xScratch)
