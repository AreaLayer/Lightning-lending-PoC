# Lightning Lending (PoC)
Simple Proof of Concept on Lightning lending

## How Works?

- Alice and Bob enter in a DM or chat channel with his Npub 
- After is generated public/private key using DLCs and offer
- Now both decide open channel
- Later can close channel

## Run application

**Pay Attention**: The application is still in alpha/PoC, not Beta. Use at your own risk. The protocol also is in testnet

Pre requisite

- LDK 
- Nostr
- Rust-DLC

You can add toml in your Cargo.toml

```toml
[dependencies]
Lightning-lending = "1.0.0"
```
### Add Cargo 

Or add cargo

```toml
[cargo]
cargo add Lightning-Lending
```
## Roadmap

- [x] Released PoC
- [ ] Presentation of New NIP
- [x] Testnet
- [x] Run application
