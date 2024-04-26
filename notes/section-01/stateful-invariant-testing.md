# Stateful Invariant Testing

```solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

import {MyContract} from "../src/MyContract.sol";
import {Test} from "forge-std/Test.sol";
import {StdInvariant} from "forge-std/StdInvariant.sol";

contract MyContractTest is StdInvariant, Test {
  MyContract exampleContract;

  function setUp() public {
    exampleContract = new MyContract();
    targetContract(address(exampleContract));
  }

  function invariant_testAlwaysIsZero() public {
    assertEq(exampleContract.shouldAlwaysBeZero(), 0)
  }
}
```
