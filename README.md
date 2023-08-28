# Box Smart Contract Upgrades

This Foundry project demonstrates an example of smart contract upgrades using the OpenZeppelin framework. It showcases the process of upgrading a smart contract's logic while preserving its storage.

## Overview

The main contract in this project is the `BoxV1` contract, serving as the initial implementation of the upgradeable logic. The contract stores a single unsigned integer. The project includes scripts for deploying and upgrading the contract, as well as tests to ensure correct behavior.

## Contracts

- `BoxV1.sol`: The initial version of the Box contract with version 1.
- `BoxV2.sol`: The upgraded implementation of the Box contract with version 2.

## Scripts

- `DeployBox.sol`: A script for deploying the initial version of the Box contract using an upgradeable proxy.
- `UpgradeBox.sol`: A script for upgrading the Box contract's logic to version 2.

## Tests

- `DeployAndUpgradeTest.sol`: A test suite to ensure the correct behavior of deployment and upgrades.

## Getting Started

1. Clone this repository:

   ```sh
   git clone https://github.com/PhoenixSatoshi/foundry-upgrades-f23-1.git
   cd box-upgrades

## Install Dependencies

npm install

## Compile the contracts

npx hardhat compile

## Run tests

npx hardhat test
Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to create an issue or a pull request.

## License

This project is licensed under the MIT License.
