# DRQ Miner — Beta

Public beta builds. Wider testing before stable promotion.

**Downloads:** [Releases](https://github.com/DQMining/DRQ-Miner-Beta/releases)

| Asset | Platform |
|-------|----------|
| `DRQMiner-win64.zip` | Windows x64 |
| `drqminer-linux-x64.tar.gz` | Linux x64 |
| `drqminer-linux-arm64-phone.tar.gz` | Android Userland (arm64) |

```bash
TAG=v0.1.0   # use latest tag from Releases
wget "https://github.com/DQMining/DRQ-Miner-Beta/releases/download/${TAG}/drqminer-linux-x64.tar.gz"
tar xzf drqminer-linux-x64.tar.gz && chmod +x drqminer
./drqminer -a nm/1 -o POOL:12427 -u WALLET.WORKER -p x
```

Beta builds **auto-install** updates (check shortly after start, then daily). Default dev donation **3%** (`--donate-level=0` to disable).

**Other channels:** [Stable](https://github.com/DQMining/DRQ-Miner) · [Alpha testing](https://github.com/DQMining/DRQ-Miner-Testing)

[www.dqmining.com](https://www.dqmining.com) · [Discord](https://discord.gg/Nku5N3WSBm)
