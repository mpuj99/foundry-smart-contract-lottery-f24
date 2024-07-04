# Proevably Random Raffle Contracts

## About

This code is create a proveably random smart contract lottery

## What we want it to do?
1. Users can enter by paying for a ticket
    1. The ticket fees are goign to go to the winner during the draw
2. After X period of time, the lottery will automatically draw a winner
    1. And this will be done programatically
3. Using Chainlink VRF and Chainlink Automation
    1. Chainlink VRF -> Randomness
    2. Chainlink Automation -> Time based trigger

## Tests!

1. Write deploy scripts
    1. Will not work on zkSync
2. Write tests
    1. Local chain
    2. Forked testnet
    3. Forked mainnet


## Results comments!

- It deploys the contract, but didn't fund it. Need to update the code for it. But it works locally perfectly with our mocks.
- If you want to deploy it on Sepolia for instance, you will need to change some hardcoded things like subscription ID, address account.
- Mostly all of the hardcoded changes will be on the HelperConfig.sol (addreses and more). 