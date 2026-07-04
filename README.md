## 0xFlorent

Security researcher and DeFi / ZK builder. I recover funds stuck in old contracts, solve
on-chain puzzles, hunt protocol bugs, and build privacy-preserving DeFi on Aleo.

Most of what I do starts from a self-hosted Ethereum node and a lot of reading old Solidity
by hand.

### White-hat recoveries

- **HongCoin ICO, ~1,003 ETH unlocked.** A 2016 crowdsale whose refund path had been broken
  for nine years. I found the unlock, an unchecked overflow in the team's own admin
  function, proved it end to end on a Foundry mainnet fork, and disclosed it to the original
  team, who executed it on-chain. No funds taken, no fee.
  See [hongcoin-recovery](https://github.com/floflo777/hongcoin-recovery).
- **~19.3 ETH across earlier cases:** a dormant 2018 ICO refund (5.1 ETH) and seven expired
  Liquality HTLCs returned to their owner (14.2 ETH).

### On-chain puzzles

- **Finlow-Bates book puzzles, 4 solved.** Small BTC rewards with keys hidden in a published
  blockchain book. The methods ran from repairing a planted BIP39 mnemonic to XOR-ing printed
  hashes and an English to Italian wordlist localization.
  See [finlow-bates-solutions](https://github.com/floflo777/finlow-bates-solutions).
- **Teikhos (TeikhosBounty), 735B solved for 0.5 ETH.** Recovered the winning ECDSA public
  key for one of Johan Nygren's on-chain key-reveal bounties.

### Protocol security

- **Akash BME incentivized testnet, 8 bugs reported.** Critical and High severity: stuck
  mints, vault, lease and escrow state inconsistencies, oracle config mismatch, each with a
  reproduction. See [akash-bme-testnet-bugs](https://github.com/floflo777/akash-bme-testnet-bugs).
- Ongoing differential research on Ethereum execution and consensus clients, and zkVM
  soundness.

### DeFi and ZK

- **Eclipse, a private lending protocol on Aleo.** A decentralized price oracle (staking,
  slashing, on-chain median aggregation) plus an over-collateralized USDA vault and a
  permissionless lending pool, written in Leo. 1st place at the Aleo Hackathon
  (KRYPTOSPHERE x zSociety, 2025, $100k pool). See [aleo-eclipse](https://github.com/floflo777/aleo-eclipse).
- **MBC-20**, an inscription-style token standard and indexer on Base.
  See [mbc20](https://github.com/floflo777/mbc20).

### Approach

I use AI (Claude Code) to accelerate the search and clustering pipeline, not to read the
contracts. Automated tooling tends to give up on exactly the contracts worth a closer look,
so the judgment stays manual.

### Contact

X [@0xFlorent_](https://twitter.com/0xFlorent_) · ENS `0xflorent.eth`
