# NEXUS-VERSION
```bash
curl --proto '=https' --tlsv1.2 -sSf h ttps://sh.rustup.rs | sh
```
```bash
source $HOME/.cargo/env
```
```bash
sudo apt update
```
```bash
sudo apt install git
```
```bash
git clone https://github.com/nexus-xyz/nexus-cli.git
```
```bash
cd nexus-cli/clients/cli
```
```bash
git checkout tags/v0.8.14
```
```bash
cargo build --release
```
```bash
sudo cp target/release/nexus-network /usr/local/bin/
```
```bash
nexus-network start --node-id yourid
```
