# Forking Mainnet

## Fork inside contract

```solidity
import {Test} from "forge-std/Test.sol";

function setUp() public {
  vm.createSelectFork({blockNumber: 0, urlOrAlias: "mainnet"})
}
```

## Fork using foundry.toml

```toml
[rpc_endpoints]
mainnet = "{MAINNET_RPC_URL}"
```
