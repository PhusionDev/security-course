# Section 1 - Solidity Refresher

## Foundry

### Foundry Website

- https://book.getfoundry.sh/

### Install Foundry

- curl -L https://foundry.paradigm.xyz | bash

### Foundry utilities

- foundryup
- forge --help
- cast --help
- chisel --help

### Useful tools/links

- https://phind.com
- https://peeanha.io
- https://etehereum.stackexchange.com

### Forge Commands

- forge init
- forge build
- forge test
- forge test --mt testFunctionName

### Fuzz Testing

- Foundry Fuzzing = Stateless Fuzzing
- Foundry Invariant = Stateful Fuzzing

#### Invariants:

- New tokens minted < inflation rate
- Only possible to have 1 winner in a lottery
- Only withdraw what they deposit

#### Steps for Testing

1. Understand what the invariants are
2. Write functions that can execute them
