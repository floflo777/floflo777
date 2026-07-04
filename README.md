## 0xFlorent

Security researcher and DeFi / ZK builder. I recover funds stuck in old contracts,
solve on-chain puzzles, hunt protocol bugs, and build privacy-preserving DeFi on Aleo.

Most of what I do starts from a self-hosted Ethereum node and a lot of reading old
Solidity by hand.

### White-hat recoveries

- **HongCoin ICO — ~1,003 ETH unlocked.** A 2016 crowdsale whose refund path had been
  broken for nine years. Found the unlock (an unchecked overflow in the team's own admin
  function), proved it end-to-end on a Foundry mainnet fork, disclosed it to the original
  team, who executed it on-chain. No funds taken, no fee. → [hongcoin-recovery](https://github.com/floflo777/hongcoin-recovery)
- **~19.3 ETH across earlier cases** — a dormant 2018 ICO refund (5.1 ETH) and seven
  expired Liquality HTLCs returned to their owner (14.2 ETH).

### On-chain puzzles

- **Finlow-Bates book puzzles — 4 solved.** BIP39/hash keys hidden in a published book;
  methods ranged from XOR of printed hashes to an EN→IT wordlist translation trick.
- **Teikhos bounty — 0.5 ETH claimed.** ECDSA public-key-reveal bounty (Johan Nygren's
  TeikhosBounty family).

### Protocol security

- **Akash BME incentivized testnet — 8 bugs reported** (Critical/High: stuck mints,
  vault/lease/escrow state inconsistencies, oracle config mismatch), each with a
  reproduction. → [akash-bme-testnet-bugs](https://github.com/floflo777/akash-bme-testnet-bugs)
- Ongoing differential research on Ethereum execution/consensus clients and zkVM
  soundness.

### DeFi & ZK

- **Eclipse — private lending protocol on Aleo.** Decentralized price oracle (staking,
  slashing, on-chain median aggregation) plus an over-collateralized USDA vault and a
  permissionless lending pool, in Leo. **1st place, Aleo Hackathon (KRYPTOSPHERE ×
  zSociety, 2025 — $100k pool).** → [aleo-eclipse](https://github.com/floflo777/aleo-eclipse)
- **MBC-20** — inscription-style token standard and indexer on Base. → [mbc20](https://github.com/floflo777/mbc20)

### Approach

I use AI (Claude Code) to accelerate the search and clustering pipeline, not to read the
contracts — automated tooling tends to give up on exactly the contracts worth a closer
look. The judgment stays manual.

### Contact

X [@0xFlorent_](https://twitter.com/0xFlorent_) · ENS `0xflorent.eth`
