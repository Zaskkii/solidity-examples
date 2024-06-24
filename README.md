# Solidity Tutorials and Examples

This repository contains step-by-step tutorials and practical examples to learn Solidity, the programming language used to develop smart contracts on Ethereum.

## Repository structure

The repository is organised as follows for ease of navigation and use:

solidity-tutorials-examples/
│
├── tutorials/ # Directory containing step-by-step tutorials.
│ ├─── 01-intro-to-solidity.md # Introduction to Solidity and Ethereum
│ ├─── 02-creating-contracts.md # Creation and basic contract structure
│ ├─── 03-interacting-with-contracts.md # Interacting with contracts from the web and console
│ └── ...
│
├─── examples/ # Practical examples of smart contracts.
│ ├─── token-contracts/ # Examples related to ERC-20 token-contracts
│ │ ├─── ERC20Token.sol # Implementation of a basic ERC-20 contract
│ │ ├─── Crowdsale.sol # Contract for the sale of tokens during an ICO
│ │ └── ...
│ │
│ ├─── voting-contracts/ # Examples related to voting contracts
│ │ │ ├─── Voting.sol # Basic contract for voting systems
│ │ │ ├─── ProxyVoting.sol # Example of proxy voting using a proxy contract
│ │ └── ...
│ │
│ └── ...
│
├─── tests/ # Unit tests for smart contracts.
│ ├─── token-tests/
│ │ ├─── ERC20Token.test.js # Tests for the ERC-20 contract
│ │ └── ...
│ │
│ ├├─── voting-tests/
│ │ │ ├─── Voting.test.js # Tests for voting contract
│ │ └── ...
│ │
│ └── ...
│
└└── resources/ # Additional resources and useful links
├─── solidity-docs.md # Links to official Solidity documentation.
    ├─── best-practices.md # Smart Contract Security Best Practices
    ├─── additional-resources.md # Additional useful resources for developers
    └── ...

### Details about the Main Directories

- tutorials/**: Contains detailed tutorials that guide developers from basic concepts to advanced Solidity and Ethereum techniques.
- **examples/**: Includes practical examples of smart contracts implemented in Solidity, organised by types such as ERC-20 tokens, voting contracts, among others.
- tests/**: Here are the unit tests to ensure the functionality and security of the smart contract examples.
- **resources/**: Provides additional useful links and documents, such as the official Solidity documentation, security best practices and other relevant resources for developers.

## Use and Contribution

### Usage

To use the examples and tutorials in this repository, follow these steps:

1. Clone the repository on your local machine:
   ````bash
   git clone https://github.com/tu-usuario/solidity-tutorials-examples.git
   
2.	Explore the tutorials/ and examples/ directories to learn and experiment with the different Solidity examples.

3.	Check out the resources under resources/ for more information and useful links.

### Contribution 

Contributions are welcome! If you want to improve this project with new examples, tutorials or corrections, follow these steps:

	1. Open an issue to discuss your ideas or problems encountered.
	2.	Fork the repository and make your changes in a new branch.
	3.	Send a pull request detailing your changes and implemented improvements.

## Usage Example - ERC-20 Token Contract

To implement a basic ERC-20 contract using Solidity from this repository, follow the steps below:

1. Go to the `examples/token-contracts/` directory.
2. Open the `ERC20Token.sol` file and copy the code.
3. Compile and deploy the contract to your preferred Ethereum development environment.

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for more details.

## Contact

If you have any questions or suggestions about this project, please do not hesitate to contact me via [email](isaac.s.ginard@gmail.com) or [Twitter](https://twitter.com/@zaskki).
