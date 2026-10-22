# WHAT IS BLOCKCHAIN? From Centralized Problems to a Decentralized Solution
Source: Cyfrin Updraft – Blockchain Basics, lesson 1


## Blockchain = a shared record book that nobody owns and nobody can secretly change.

## What it is
A shared record book (ledger) copied on thousands of computers (nodes).
No bank or middleman: rules are enforced by math + code, not trust.

## Example
```
Block 9          Block 10          Block 11
hash: A1   ◄──   prev: A1    ◄──   prev: B7
                 hash: B7          hash: C3

Change Block 10 → its hash becomes X9
Block 11 still says prev: B7 → ❌ chain broken → network rejects it
```

## Key words
- Node = one computer holding a copy
- Block = a page of transactions
- Hash = fingerprint of a block's data
- Immutable = can't be changed without everyone noticing

## Still unsure
- Who decides which block gets added next?