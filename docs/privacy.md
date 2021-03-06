---
id: privacy
title: Privacy
sidebar_label: Privacy
---

Privacy in LatamLink is focused on making data only available to a specific list of participants. In order to accomplish this a mechanism must be implemented that ensures transactions are ditributed only to a list of participants who can send private transactions among them.

This brings up a couple of questions:

- Which accounts can see the transaction ?
- Which nodes can see the transaction ?
- Which nodes can see the smart contract ? 
- Who manages the list of permitted actors ? (on chain vs. off-chain)

## LatamLink ZPK

Blockchain technology provides the necessary tools to decentralize the information securely and unwaveringly. The introduction of Bitcoin made possible that thousand of nodes from around the world share and hold the same information. However, in the majority of the Blockchains, the central idea is to hold this information public for everyone accesses to it and verify it, without the necessity of a central authority, is for that we defined the public blockchains as *trustless*(no need to trust).

That is how a lot of companies and private entities that want to use the blockchain technology encounter with a very important question: how maintain the information private and at the same time keep the security and transparency of a public blockchain?

This is where Zero-Knowledge Protocols get into, also knows as ZPK. Is the method for which nodes operators can demonstrate that a transaction is valid without the necessity to reveal the values of the transaction.

The fact that this added value of privacy can be obtained through the cryptography is useful for the people and private entities that benefit from the use of blockchain technology without the fear of sharing confidential information.

LatamLink aims to integrate new primitives (intrinsics) for the verification of ZKP natively available to the Smart Contracts (Dapps) for the construction of applications with privacy requirements and at the same time can be validated for the same agents in the network (BPs + Full Nodes), without the necessity to add new agents to the network.



### Data privacy existent solutions in EOSIO
https://github.com/EOSIO/eosjs-ecc/issues/19#issuecomment-392941963

https://github.com/GetScatter/ScatterDesktop/issues/43


### Orion Layer

**Hyperledger Besu** has a pre-compile contract extension of ethereum client that uses orion keys to channel private transactions through orion nodes to prevent data from being visible on the public network.
