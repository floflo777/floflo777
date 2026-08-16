## 0xFlorent

Security researcher and DeFi / ZK builder. I recover funds stuck in old contracts, solve
on-chain puzzles, hunt protocol bugs, and build privacy-preserving DeFi on Aleo.

Most of what I do starts from a self-hosted Ethereum node and a lot of reading old Solidity
by hand.

### White-hat recoveries

- **~1,003 ETH** unlocked from the failed 2016 HongCoin ICO, frozen for 9 years. I found the
  path (an unchecked overflow in the team's own admin function), proved it on a Foundry
  mainnet fork, and disclosed it to the original team, who executed it on-chain. No funds
  taken, no fee. See [hongcoin-recovery](https://github.com/floflo777/hongcoin-recovery).
- **~19.3 ETH** returned in earlier cases: a dormant 2018 ICO refund (5.1 ETH) and 7 expired
  Liquality HTLCs (14.2 ETH).

### On-chain puzzles

- **0.01 BTC** claimed from various on-chain puzzles, most of it four Bitcoin key puzzles
  hidden in Kary Finlow-Bates' book (BIP39 mnemonic repair, XOR of printed hashes, English
  to Italian wordlist localization, triple-SHA256 of a hidden phrase), unsolved for years,
  plus a couple of smaller ones. See [finlow-bates-solutions](https://github.com/floflo777/finlow-bates-solutions).
- **0.5 ETH** claimed on Teikhos bounty 735B, by recovering a winning ECDSA public key that
  had leaked in a failed 2022 attempt's calldata. See [teikhos-735b](https://github.com/floflo777/teikhos-735b).

### Protocol security

- **8 bugs** (Critical and High) reported on the Akash BME incentivized testnet, each with a
  reproduction: stuck mints, vault, lease and escrow state inconsistencies, and an oracle
  config mismatch. Earned **$320 in AKT** as a rewarded tester. See [akash-bme-testnet-bugs](https://github.com/floflo777/akash-bme-testnet-bugs).
- Ongoing differential research on Ethereum execution and consensus clients, and zkVM
  soundness.

### DeFi and ZK

- **Won a $100,000 hackathon** for a private lending protocol I built on Aleo, written in
  Leo. Ask me on X for details.

### Contact

X [@0xFlorent_](https://twitter.com/0xFlorent_) · ENS `0xflorent.eth`
