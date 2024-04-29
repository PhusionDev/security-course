# Where should I begin?

## This is what client sends us

https://sepolia.etherscan.io/address/0x2ecf6ad327776bf966893c96efb24c9747f6694b#code

### Answer

- Should ask if their team has written and performed any tests for their code
- What is the team's ultimate goal/outcome from this review?
- Has the team readied themselves for an audit? rekt test?
- Can offer to work with them as a consultant to develop a test suite for them

# Requirements

## What tools are needed to setup the codebase & test suite?

### Example

```bash
forge init
forge install OpenZeppelin/openzeppelin-contracts --no-commit
forge install vectorized/solady --no-commit
forge build
```

## Testing

### How to run tests. How to see test coverage

```bash
forge test
```

# Security Review Scope

The specific details of the security review. Nail down exactly what the protocol is planning on deploying, and how they plan on deploying it.

## Commit Hash

## Repo URL

## In scope vs out of scope contracts

## Compatibilities

- Solc Version: XXX
- Chain(s) to deploy contract to:
  - XXX (ie: ETH)
  - XXX (ie: Arbitrum)
- Tokens
  - XXX (ie: ERC20s)
    - XXX (ie: LINK)
    - XXX (ie: USDC)
  - XXX (ie: ERC721s)
    - XXX (ie: CryptoKitties)
  - List expected ERC20s and other specific tokens. If a protocol is expected to work with multiple or any tokens of a certain standard, you could do something like "All ERC20s". Or an ordered list like "USDC" etc

## Roles

What are the different actors of the system? What are their powers? What should/shouldn't they do?

## Known Issues

List any issues that the protocol team is aware of and will not be acknowledging/fixing.
