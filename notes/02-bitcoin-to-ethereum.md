# The Genesis of Blockchain: From Digital Cash to Bitcoin
Source: Updraft – Blockchain Basics, lesson 2

## What it is
The history that led to smart contracts:
Digital cash problem → Bitcoin (2008) → Ethereum (2015)

## Example
```
Double-spend problem (digital copy-paste):

  You ──$100──▶ Friend
  You ──$100──▶ Shop     ← same $100 sent twice!

Old fix (DigiCash): one company keeps the master ledger → can freeze/censor you
Bitcoin fix:        everyone holds the ledger → the network rejects the 2nd spend
```

```
Bitcoin  = calculator      → store + send value (simple, secure)
Ethereum = world computer  → runs code = smart contracts

Smart contract example (flight insurance):
IF flight delayed > 24h  THEN  refund ticket automatically
```

## Key words
- Double-spend = spending the same digital money twice
- Byzantine Generals Problem = how to agree on the truth when some participants may lie
- Credibly neutral = rules in open code, enforced by the network, so it treats everyone equally
- Smart contract = an agreement written as code that runs on the blockchain by itself
- Ether (ETH) = Ethereum's currency, used to pay for the network
- Turing complete = can run any kind of program (Ethereum yes, Bitcoin no)

## Still unsure
- How exactly does the network "collectively verify" a transaction? (probably consensus)
- How does a smart contract get real-world data like flight delays?