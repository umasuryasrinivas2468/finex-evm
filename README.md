# finex-evm

Electronic Voting Machine (EVM) with Finex Token Integration
This repository contains the smart contracts necessary to build an Electronic Voting Machine (EVM) integrated with the Finex Token. The purpose of this project is to provide a transparent and secure voting system using blockchain technology, while also incorporating the Finex Token for voting privileges or other related functionalities.

Files:
EVM.sol: This Solidity smart contract implements the core functionalities of the Electronic Voting Machine (EVM). It includes features such as managing the owner of the EVM, implementing access control via modifiers, and can be extended to include additional EVM functionalities.

FinexToken.sol: This contract defines the Finex Token, an ERC20-compatible token implemented using OpenZeppelin's ERC20 standard. It includes functionality for minting initial tokens and can be expanded to include features like token transfers, allowances, etc.

VotingApp.sol: The VotingApp contract provides the main voting application logic. It includes a struct to represent voters, mapping to track voting status and choices, functions to cast votes, and events to emit voting-related information.

Migrations.sol: This contract is used for managing smart contract deployment and migration using Truffle framework. It includes functions to set completed migrations and upgrade contracts.

Usage:
This repository serves as a foundation for building a secure and decentralized voting system integrated with the Finex Token. Developers can extend the provided contracts to include additional features such as multi-candidate voting, voter authentication, result tabulation, and more. Unit tests and further documentation can be added to ensure reliability and transparency in the voting process.

Feel free to fork this repository and customize it according to your project requirements. Contributions and suggestions are welcome!
