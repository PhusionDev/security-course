- Scope: the code that will be audited

## What a smart contract entails

1. Have clear documentation
2. Robust test suite ideally including fuzz tests
3. Code should be commented & readable
4. Modern best practices followed
5. Communication channel between developer and auditors
6. Do an initial video walkthrough of code
7. Post audit

## What an audit isnt

- doesn't guarantee code is bug-free

## Competitive vs. Private Audit Mindset

### Competitive

- Find as many high impact bugs as possible (optimize for time)

### Private

- Find as many high impact bugs as possible, and do whatever you can to make the client safer

## The Audit Process

1. Get context
2. Tools & manual review
3. Write report

## The Audit Process (more in-depth)

- 3 Phases

1. Initial Review
1. Scoping
1. Reconnaissance
1. Vulnerability identification
1. Reporting
1. Protocol fixes
1. Fixes issues
1. Retests and adds tests
1. Mitigation Review
1. (Repeat #1)

In your report it's your job to do whatever it takes to make the protocol more secure. (Private audit)

## What tools do we use in the smart contract review process

### Test Suites

### Static Analysis

- Slither
- aderyn
- Mythril

### Fuzz Testing

- Foundry

### Stateful Fuzz Testing

### Differential Tests

### Formal Verification

- Formal Verification (FV) is a generic term for applying formal methods (FM) to verify the correctness of hardware.
- Applying FM means anything based on mathematical proofs, in software often used as a proof of correctness or proof of "bug".

#### Symbolic Execution

- A form of FV where you convert software to a mathematical expression.
- TL;DR: Take solidity function -> Math. Math can be solved.

## Top kinds of hacks in Web3

- Stolen Private Keys
- Reward Manipulation
- Price Oracle Manipulation
- Misconfiguration
- Insufficient Function Access Control
- Logic Error
- Function Parameter Validation
- Read-Only Reentrancy
- Reentrancy
- Governance
