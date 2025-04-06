# Soundness-access

Use Github codespace or vps

For vps 

### Install Dependencies 
```
sudo apt update && sudo apt upgrade
sudo apt install htop ca-certificates curl wget libleveldb-dev build-essential pkg-config lsb-release libssl-dev libreadline-dev libffi-dev jq gcc screen unzip lz4
```

### Install protobuf-complier
```
sudo apt install protobuf-compiler
```

### Install Rust
```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
- Select option 1
```
source $HOME/.cargo/env
```
### Soundness Install
```
curl -sSL https://raw.githubusercontent.com/soundnesslabs/soundness-layer/main/soundnessup/install | bash
source ~/.bashrc 
soundnessup install
```
```
soundnessup update
```
### Create a wallet
```
soundness-cli generate-key --name my-key
```
- Type password(not visible)
- **Save mnemonic** and get the access key

### list keys
```
soundness-cli list-keys
```

- Visit : https://discord.gg/dU3kSh9Grg
- Goto testnet access
- paste : !access your-access-key

---

**Follow** : https://x.com/cryptoconsol
