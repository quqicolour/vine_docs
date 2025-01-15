---
sidebar_position: 3
---

# How to be a curator?

Everyone can apply to be a curator through NexoraFinance by executing the "register" action in Governance and waiting for governance approval.

```solidity
//Register and get vetted to become a curator
function register(uint16 _feeRate, uint64 _bufferTime, uint64 _endTime, address _feeReceiver) external:
```

Once approved as a curator, they can customize any module (only user-defined modules that pass the review process can be adopted by the community)

After becoming a curator, they can submit custom hooks, or choose to use official hooks, and freely combine them into their own yield strategies based on the modular system.
