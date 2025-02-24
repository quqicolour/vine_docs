---
sidebar_position: 3
---

# How to be a curator?

Everyone can apply to be a curator through VineFinance by executing the "register" action in Governance and waiting for governance approval.

```solidity
struct MarketInfo{
    bool validState;
    uint16 feeRate;
    uint64 bufferTime;
    uint64 endTime;
    address feeReceiver;
    address creator;
}

struct HookCrossRecord {
    uint32 destinationDomain;
    uint64 lastestTime;
    uint64 lastestBlock;
    uint64 usdcNonce;
    bytes32 destHook; 
    uint256 lastestCrossAmount;
}

//Register and get vetted to become a curator
function register(uint16 _feeRate, uint64 _bufferTime, uint64 _endTime, address _feeReceiver) external:
```

Once approved as a curator, they can customize any module (only user-defined modules that pass the review process can be adopted by the community)

After becoming a curator, they can submit custom hooks, or choose to use official hooks, and freely combine them into their own yield strategies based on the modular system.
