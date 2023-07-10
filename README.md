# MyToken Contract

This repository contains the smart contract code for the MyToken ERC20 token on the Hardhat  network. The contract is implemented using Solidity and inherits from the OpenZeppelin ERC20 contract.

## Contract Details

- Name: Polygon
- Symbol: MTC
- Decimals: 18

## Prerequisites

To interact with the MyToken contract, you need to set up the following:

1. Install Node.js: Make sure you have Node.js installed on your machine. You can download it from [here](https://nodejs.org).

2. Install Hardhat: Hardhat is a development environment for Ethereum. Install it globally by running the following command in your terminal:

    ```
    npm install -g hardhat
    ```

3. Set up the project: Clone this repository and navigate to the project directory.



4. Install dependencies: Install the project dependencies using npm.

    ```
    npm install
    ```

## Usage

Here are some commonly used Hardhat commands to interact with the MyToken contract:

- Compile the contracts:

    ```
    npx hardhat compile
    ```


- Deploy the contract locally (Hardhat network):

    ```
    npx hardhat run scripts/deploy.js --network localhost
    ```


Make sure to configure the network settings in the `hardhat.config.js` file.

## License

This project is licensed under the [MIT License](LICENSE).
