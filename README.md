


# Nostr Reputation Wallet Prototype

This repository contains a minimal prototype that integrates Nostr messaging, Lightning (LND), and a reputation scoring layer (BSRL). It demonstrates an architecture for sending/receiving Bitcoin payments, publishing attestation/reputation events to Nostr, and locally computing reputation scores.

> Warning: this is a prototype. Do not use in production without proper hardening, auditing, and legal review.

## Quick start (local, non-Docker)

1. Clone and install:
```bash
git clone <repo>
cd nostr-ln-rep-proto
cp .env.example .env
# edit .env with your LND paths and NOSTR relays
npm install
