Payment Contract
================

This is a payment contract written in Solidity for the Binance Smart Chain. The contract allows two parties to make payments to each other using BNB or any other BEP20 token.

Getting Started
---------------

To get started with this contract, you will need to have a Binance Smart Chain wallet and some BNB or BEP20 tokens. You will also need to have the [Truffle](https://www.trufflesuite.com/docs/truffle/getting-started/installation) framework installed.

### Installation

1.  Clone this repository: `git clone https://github.com/Hexdee/Payment_Contract.git`
2.  Install dependencies: `npm install`

### Testing

To run tests, use the following command: `truffle test`

### Deployment

To deploy the contract, you will need to configure your Truffle environment to connect to a Binance Smart Chain node. You can do this by updating the `truffle-config.js` file with the appropriate network settings.

Once you have configured your environment, use the following command to deploy the contract: `truffle migrate --network <network>`

Usage
-----

The contract has the following functions:

### `makePayment(address recipient, uint256 amount)`

This function allows a user to make a payment to another user. The `recipient` parameter is the address of the user who will receive the payment, and the `amount` parameter is the amount of BNB or BEP20 tokens to send.

### `getBalance()`

This function returns the balance of the contract.

### `withdraw()`

This function allows the contract owner to withdraw the funds from the contract.

Contributing
------------

If you want to contribute to this project, please fork the repository and create a pull request with your changes.

License
-------

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
