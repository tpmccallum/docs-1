# Uniswap Smart Contract Example
This page contains a blow by blow example of how to initialize, deploy and then interact with the Uniswap Smart Contracts. All work will be performed in the web3 console. At the end of this tutorial example we will be performing the necessary [Uniswap Frontend](https://github.com/Uniswap/uniswap-frontend) configuration. The outcome being your own complete Uniswap exchange application like the official [Uniswap Exchange](https://uniswap.exchange/swap).

## Vyper
The original [Solidity](https://github.com/Uniswap/old-solidity-contracts) Smart Contracts are out of date. Therefore we will be using the [current Vyper Smart Contracts](https://github.com/Uniswap/contracts-vyper) during this tutorial example. 

### Housekeeping
We will create some new accounts for demonstration purposes.
```javascript
 personal.newAccount()
```
### Factory

