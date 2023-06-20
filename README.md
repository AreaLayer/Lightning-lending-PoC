# Lightning Lending (PoC)
Simple Proof of Concept on Lightning lending

### How Works?

- Alice and Bob enter in a DM or chat channel with his Npub 
- After is generated public/private key using DLCs and offer
- Now both decide open channel
- Later can close channel

### Run application

**Pay Attention**: The application is still in alpha/PoC, not Beta. Use at your own risk and protocol also is in testnet

Pre requisite

- LDK 
- Nostr
- Rust-DLC

You can add toml in your Cargo.toml

```toml
[dependencies]
Lightning-lending = "1.0.1"
```
### Add Cargo 

Or add cargo

```toml
[cargo]
cargo add Lightning-Lending
```

### NIP-XXX: TBA

[Check more](https://github.com/AreaLayer/NIP-xxx/blob/main/NIP/NIP-xxx.md)

### Roadmap

- [x] Released PoC
- [x] Presentation of New NIP
- [x] Testnet
- [x] Run application

## Demo video of PoC on Lightning Lending

![Demo video](https://github.com/AreaLayer/Lightning-lending-PoC/blob/main/demo-video/Test5.gif)
