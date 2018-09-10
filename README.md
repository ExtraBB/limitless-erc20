# Limitless ERC20 Smart Contract
This contract is setup as a demo contract to show how simple it is to distribute an ERC20 token. It has no supply limit and returns tokens equal to a conversion rate times the amount of ether you send to the contract.

## Testing
This project uses `Truffle` for testing. To run the tests:
```
npm i -g truffle
truffle compile
truffle test
```
NOTE: Make sure you have a geth instance running or `ganache`. For more info, look up the truffle documentation.
