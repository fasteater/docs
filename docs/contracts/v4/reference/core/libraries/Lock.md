# Lock
[Git Source](https://github.com/uniswap/v4-core/blob/80311e34080fee64b6fc6c916e9a51a437d0e482/src/libraries/Lock.sol) - Generated with [forge doc](https://book.getfoundry.sh/reference/forge/forge-doc)

This is a temporary library that allows us to use transient storage (tstore/tload)
TODO: This library can be deleted when we have the transient keyword support in solidity.


## State Variables
### IS_UNLOCKED_SLOT

```solidity
bytes32 internal constant IS_UNLOCKED_SLOT = 0xc090fc4683624cfc3884e9d8de5eca132f2d0ec062aff75d43c0465d5ceeab23;
```


## Functions
### unlock


```solidity
function unlock() internal;
```

### lock


```solidity
function lock() internal;
```

### isUnlocked


```solidity
function isUnlocked() internal view returns (bool unlocked);
```

