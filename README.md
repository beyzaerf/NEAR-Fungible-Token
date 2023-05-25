# NEAR BYZ Token

This project is built using the [Fungible Tokens 101](https://docs.near.org/tutorials/fts/introduction) tutorial of the official NEAR site. 

## File Structure

| File                             | Description                                                                      |
| -------------------------------- | -------------------------------------------------------------------------------- |
| ft_core.rs       | Contains the logic for transferring and controlling FTs.                                         |
| lib.rs           | Holds the smart contract initialization functions and dictates what information is kept on-chain.|
| metadata.rs      | Defines the metadata structure.                                                                  |
| storage.rs       | Contains the logic for registration and storage                                          |                          
| contract.wasm    |  This is what we will be deploying to the blockchain.                                            |


```
skeleton
├── Cargo.lock
├── Cargo.toml
├── build.sh
├── out
    ├── contract.wasm
    ├── market.wasm
    └── nft-contract.wasm
└── src
    ├── ft_core.rs
    ├── lib.rs
    ├── metadata.rs
    └── storage.rs
```

