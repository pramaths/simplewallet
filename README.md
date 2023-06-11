# simplewallet
Secure and Easy-to-Use Wallet Contract: A Solidity smart contract for a secure and user-friendly wallet on the Ethereum blockchain.
A simple smart contract for managing a shared wallet.

## Description

The Simple Wallet project is a Solidity smart contract that allows users to manage a shared wallet. It provides functionality for setting an allowance for specific addresses, withdrawing funds, and keeping track of transactions.

## Installation

To use the Simple Wallet contract, follow these steps:

1. Install a compatible Ethereum development environment such as Remix or Truffle.
2. Import the required OpenZeppelin contracts: `Ownable.sol` and `SafeMath.sol`.
3. Import the `Allowance.sol` contract provided in this repository.
4. Import the `SharedWallet.sol` contract provided in this repository.

## Usage

### Setting Allowance

To set an allowance for an address, call the `setAllowance` function of the `Allowance` contract, specifying the address and the allowance amount. Only the owner of the contract can set the allowance.

### Withdrawing Funds

To withdraw funds from the shared wallet, call the `withdrawMoney` function of the `SharedWallet` contract, specifying the recipient address and the amount to be withdrawn. Only the owner of the contract or an address with sufficient allowance can initiate a withdrawal.

### Events

The Simple Wallet contract emits the following events:

- `MoneySent`: Triggered when funds are sent from the wallet to a recipient.
- `MoneyReceived`: Triggered when funds are received by the wallet.

## Testing

You can run tests for the Simple Wallet contract using a testing framework like Truffle or Hardhat. Refer to the documentation of your chosen development environment for instructions on running tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Authors

- [PRAMATH](https://github.com/pramaths)

## Contact

For any questions or suggestions, feel free to contact me at [your.email@example.com](mailto:pramaths848@gmail.com).
