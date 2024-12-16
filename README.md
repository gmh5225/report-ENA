# ENA

## Contract Information
- **Contract Name:** ENA
- **Compiler Version:** v0.8.20+commit.a1b79de6
- **Optimization Enabled:** Yes with 20000 runs
- **Contract Address:** 0x57e114b691db790c35207b2e685d4a43181e6061
- **EVM Version:** shanghai
- **Chain:** Ethereum Mainnet
- **Creator:** 0x32a12e3f8b1e1f521bb4fbc47ca473d10d0477de
- **Creation Transaction:** 0x143955622501605a763c6f373edef7c4a9139efffbbecb82d1833324dd558be1

## Source Code Structure
```
└── contracts
    ├── ENA.sol
    ├── interfaces
    │   └── IENADefinitions.sol
└── lib
    └── openzeppelin-contracts
        └── contracts
            └── token
                ├── ERC20
                │   └── ERC20.sol
                │   └── extensions
                │       ├── ERC20Burnable.sol
                │       ├── ERC20Permit.sol
                │       ├── IERC20Metadata.sol
                │       ├── IERC20Permit.sol
                │   └── IERC20.sol
            └── access
                ├── Ownable2Step.sol
                ├── Ownable.sol
            └── utils
                ├── Context.sol
                ├── cryptography
                │   ├── ECDSA.sol
                │   ├── EIP712.sol
                ├── Counters.sol
                ├── Strings.sol
                ├── ShortStrings.sol
                ├── math
                │   ├── Math.sol
                │   ├── SignedMath.sol
                ├── StorageSlot.sol
            └── interfaces
                └── IERC5267.sol

```