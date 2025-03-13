
# v2-core

## Overview

**v2-core** is the core module for **BaptswapV2**, a decentralized exchange built on the **Aptos** blockchain. This repository contains the essential smart contracts and logic required to operate the core functionalities of the protocol.

## Features

-   **Decentralized Exchange**: Provides the foundation for token swaps on the Aptos blockchain.
    
-   **Liquidity Pools**: Implements automated market-making (AMM) functionality.
    
-   **Efficient Transactions**: Optimized for low gas fees and high-speed execution.
    
-   **Secure and Transparent**: Built with Aptos' Move language to ensure safety and reliability.
    

## Prerequisites

To work with this project, ensure you have the following:

-   **Aptos CLI** installed: Aptos CLI Installation
    
-   **Move Language** understanding: Move Documentation
    
-   Rust (for development and testing)
    

## Installation

1.  Clone the repository:
    
    ```
    git clone https://github.com/jessicameyer198162/v2-core.git
    cd v2-core
    ```
    
2.  Install dependencies:
    
    ```
    aptos move compile
    ```
    
3.  Run tests:
    
    ```
    aptos move test
    ```
    

## Deployment

To deploy the modules to the Aptos blockchain:

```
aptos move publish --profile default
```

Ensure your Aptos account is set up and funded before deployment.

## Contributing

We welcome contributions to improve **v2-core**! Please follow these steps:

1.  Fork the repository.
    
2.  Create a new branch: `git checkout -b feature-branch`.
    
3.  Commit changes: `git commit -m "Add new feature"`.
    
4.  Push to your branch: `git push origin feature-branch`.
    
5.  Create a pull request.
    

## License

This project is licensed under the **MIT License**.

## Contact

For any inquiries or support, please open an issue on GitHub or reach out to the development team.
