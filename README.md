# DAML and Canton

A working journal of my progress learning DAML, the smart contract language
behind Canton, with the goal of building toward financial-instrument
tokenization. This is the next logical step after nine years of Solidity and Rust/Anchor
smart contract development. It is also my interest is the intersection of DAML and regulated financial instruments.

## Current progress

This repository works through the official DAML introduction, one section
per folder, building up the core of the language:

- **intro1** — templates and signatories: the anatomy of a contract and
  DAML's declarative authorization model.
- **intro2** — DAML Script: testing contracts, party authority, and the
  create/archive model.
- **intro3** — data modeling: records, variants, pattern matching, and the
  distinction between contract IDs and keys.
- **intro4** — choices: transforming contracts through controllers and the
  archive-and-create pattern, applied to a debt instrument (an IOU) through
  its full issue, transfer, and redeem lifecycle.

## Notes

This is active learning, not a finished product. I am building familiarity
with DAML's contract model and working toward the atomic, two-party
settlement patterns used in real asset tokenization on Canton.
