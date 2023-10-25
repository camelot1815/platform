---
description: How are they utilized on the Platform?
---

# 🛰 Smart Contracts

Smart Contracts play a pivotal role by automating the [Escrow process](../crypto-escrow/), ensuring secure [asset](../../resources/glossary.md#assets) handling, and enforcing trust through [transparent and immutable execution](../../resources/glossary.md#decentralization). Their versatility and reliability make them a cornerstone of a trustful Escrow Platform.

<figure><img src="../../.gitbook/assets/Smart Contract2.png" alt=""><figcaption></figcaption></figure>

### How does it work?

Smart Contracts are self-executing agreements with predefined rules and conditions. In an Escrow service, these contracts serve as automated intermediaries, instilling trust between the Parties involved without the need for a centralized intermediary.

When an Escrow is initiated, the Smart Contract securely locks the assets of either the Buyer or the Seller. These assets can be various cryptocurrencies or tokens. The Smart Contract acts as a digital vault, ensuring that the assets are held in a tamper-proof and transparent manner.

To ensure the authenticity of the Smart Contract, it includes digital signatures from all Parties involved. Digital signatures are cryptographic proofs of agreement and consent.

{% hint style="info" %}
It is important to clarify that the Platform does not, under any circumstances, assume ownership or control of the assets placed in Escrow using Smart Contracts.
{% endhint %}

The most crucial aspect of a Smart Contract is its ability to enforce conditions. These conditions are agreed upon by the Buyer and Seller before initiating the Escrow. Common conditions might include the successful delivery of goods or services, confirmation of payment, or a specific date and time.

Once the predefined conditions are met or upon successful confirmation from all Parties, the Smart Contract autonomously executes the transaction. It releases the locked assets to the appropriate Party without requiring manual intervention or approval from a Third Party. This ensures a swift and efficient exchange process.

All actions performed by the Smart Contract are recorded on the blockchain, providing complete transparency. Users can verify the status of the Escrow and the execution of funds at any time by inspecting the blockchain's public ledger.

The blockchain's immutability ensures that once the Smart Contract's conditions are met, the transaction is irreversible. This eliminates the risk of either Party reneging on their agreement after the assets have been released.

The use of Smart Contracts significantly reduces the risk of fraud or default, as the execution is code-driven and based on verifiable events. This level of security and reliability makes Smart Contracts an ideal choice for Escrow services.

## Implementation

To proceed with Escrow creation, you need to outline the terms, conditions, and obligations of the deal. Ensure that all Parties involved have a mutual understanding of what is expected.

After that decide which Escrow Smart Contract suits your needs and expectations the best. It can be Automated, Manual or Custom. Most importantly you need to examine the prerequisites and consequences of the Smart Contract you wish to create. They can be found on the following pages:

<table data-view="cards" data-full-width="false"><thead><tr><th data-type="content-ref"></th></tr></thead><tbody><tr><td><a href="automated/">automated</a></td></tr><tr><td><a href="manual/">manual</a></td></tr><tr><td><a href="custom/">custom</a></td></tr></tbody></table>

All Parties involved in the agreement interact with the Smart Contract by sending transactions to it. These transactions trigger the execution of the code and enforce the terms of the agreement. Depending on the agreement, transactions can include actions like sending cryptocurrency, confirming the completion of a task, or triggering automated payments based on predefined conditions.

Parties involved in the agreement can monitor the Smart Contract's execution and adherence to the terms directly on the Platform and verify it on the blockchain. This information is publicly accessible and can ensure a clear and trustworthy Escrow process.

Escrow Smart Contract can hold assets securely until its conditions are met, while dispute resolution logic can result in avoiding those conditions when one of the Parties does not fulfill their part of the agreement.
