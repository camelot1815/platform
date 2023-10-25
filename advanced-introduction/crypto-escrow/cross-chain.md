---
description: How can users include assets from different blockchains?
---

# ⛓ Cross-chain

Cross-chain capability facilitates and manages [Escrow agreements](./) involving different cryptocurrencies or [blockchain networks](../../resources/glossary.md#blockchain). It means that users can engage in Escrow not only within a single blockchain network but also across multiple blockchain networks.

For example, a user could initiate an Escrow involving Bitcoin (BTC) and Ethereum (ETH) assets, and the Platform would facilitate and secure the transaction between these different blockchain networks.

## Implementation

The Platform requires users to connect a [EVM-compatible](../../resources/glossary.md#ethereum-virtual-machine-evm) wallet upon successful [Registration](../user-registration/). To encourage communication and data exchange between different blockchains, the Platform relies on [oracles](../../resources/glossary.md#oracle) and interoperability protocols.

When users initiate an Escrow, they can specify the assets from a list of supported blockchain networks they intend to use for the transaction. The Platform handles the technical aspects of the Escrow, including creating and signing the necessary [Smart Contracts](../smart-contracts/) which are compatible with multiple blockchain networks. This may involve interacting with different blockchain networks to lock the assets and ensure they are held securely in Escrow until the predetermined conditions are met.
