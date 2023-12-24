# Proveably Random Raffle Contract

# About

Creates a proveably random smart contract lottery.

## What it is supposed to do?

1. Users can enter by paying for a ticket
    1. The ticket fee will go for a winner during the draw
2. After X period of time, the lottery will automatically draw a winner
    1. And this will be done programtically
3. Using chainlink VRF & Chainlink Automation
    1. Chainlink VRF -> Randomness
    2. Chainlink automation -> Time based trigger


## Installing brownie contracts
1. forge install smartcontractkit/chainlink-brownie-contracts@0.6.1 --no-commit
2. Go to .toml and add remappings ie.
  1.  remappings = [
    '@chainlink/contracts=/lib/chainlink-brownie-contracts/contracts/',
]

## Tests
1. Write some deploy scripts
2. Write our tests
  1. Work on a local chain
  2. Forked Testnet
  3. Forked Mainnet
  4. 
