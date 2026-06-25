# DRQ Miner — Beta

Public beta builds. Wider testing before stable promotion.

**Downloads:** [Releases](https://github.com/DQMining/DRQ-Miner-Beta/releases) — latest **v0.2.0**

| Asset | Platform |
|-------|----------|
| `DRQMiner-win64.zip` | Windows x64 |
| `drqminer-linux-x64.tar.gz` | Linux x64 |
| `drqminer-linux-arm64-phone.tar.gz` | Android Userland (arm64) |

## Linux x64

```bash
TAG=v0.2.0
wget "https://github.com/DQMining/DRQ-Miner-Beta/releases/download/${TAG}/drqminer-linux-x64.tar.gz"
tar xzf drqminer-linux-x64.tar.gz && chmod +x drqminer
./drqminer -a nm/1 -o us-east.hashmonkeys.cloud:12427 -u crb1YOURADDRESS.worker -p x
```

## Phone (Userland)

```bash
TAG=v0.2.0
wget -O drqminer-linux-arm64-phone.tar.gz \
  "https://github.com/DQMining/DRQ-Miner-Beta/releases/download/${TAG}/drqminer-linux-arm64-phone.tar.gz"
tar xzf drqminer-linux-arm64-phone.tar.gz
chmod +x drqminer mine-nm.sh
sed -i 's/^WALLET=.*/WALLET=crb1YOURADDRESS.worker/' mine-nm.sh
./mine-nm.sh
```

## Windows

Extract `DRQMiner-win64.zip`, edit `start-mining-nm.bat` (wallet), double-click it.

Beta builds **auto-install** updates (check shortly after start, then daily). Default dev donation **3%** (`--donate-level=0` to disable).

**Other channels:** [Stable](https://github.com/DQMining/DRQ-Miner) · [Alpha testing](https://github.com/DQMining/DRQ-Miner-Testing)

[www.dqmining.com](https://www.dqmining.com) · [Discord](https://discord.gg/Nku5N3WSBm)
