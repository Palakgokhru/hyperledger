---
layout: default
title: Hyperledger Fabric Overview
---

# Hyperledger Fabric Overview

Hyperledger Fabric is a permissioned blockchain framework designed for enterprise-grade applications.

## Key Features
- Permissioned membership
- Modular architecture
- High performance and scalability
- Pluggable consensus mechanisms

## Core Components
### Peers
Peers host ledgers and smart contracts (chaincode).

### Ordering Service
Ensures total order of transactions across the network.

### Certificate Authority
Manages identities using PKI.

## Transaction Flow
1. Client submits proposal
2. Endorsing peers simulate transaction
3. Ordering service creates blocks
4. Peers validate and commit

## Use Cases
- Supply Chain
- Healthcare
- Banking & Finance
