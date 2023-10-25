---
description: Are you able to incorporate everything into the Smart Contract?
---

# ⚒ Custom

Exactly! Writing any agreement into a [Smart Contract](../) involves translating the terms and conditions of the deal into code that can be executed on a [blockchain](../../../resources/glossary.md#blockchain).&#x20;

Custom Escrow Smart Contracts are used when standard [Automated](../automated/) or [Manual](../manual/) contracts do not fully align with the intricacies of the transaction. For example, in a real estate deal, a custom contract might incorporate various conditions, including inspections, legal reviews, and payment milestones, each requiring manual or automated actions.

Custom Escrow Smart Contracts offer the highest degree of flexibility. Users can define and customize the specific conditions, rules, and actions that the contract should follow. These contracts are tailored to accommodate unique or complex transaction scenarios.

{% hint style="info" %}
The only key difference between Custom Smart Contracts is the release mechanism. If it is Manual, it's mandatory for all Parties to have a Legal Agreement between themselves in case of a dispute claim. All Escrow Smart Contracts with Automatic release can not issue a dispute claim even in case of conflicts between Parties.
{% endhint %}

## Use Cases

#### Complex Agreements (Manual Release)

Complex agreements often involve significant amounts of money and a variety of conditions. Custom Escrow Smart Contracts can facilitate the secure transfer of property deeds and funds upon the completion of inspections, approvals, and legal requirements.

{% content-ref url="complex-agreement.md" %}
[complex-agreement.md](complex-agreement.md)
{% endcontent-ref %}

#### **Competition (Automated Release)**

For events with unique outcomes, such as the result of a specific sports match or an entertainment industry award, Custom Escrow Smart Contracts can automatically distribute winnings based on the outcome.

{% content-ref url="competition.md" %}
[competition.md](competition.md)
{% endcontent-ref %}

## Implementation

To create a Custom Smart Contract you need to convert the Terms and Conditions of the agreement into code. This may include defining variables for the Parties involved, specifying the actions required for each Party, and setting conditions for contract execution. Also implementing functions or methods within the Smart Contract code to handle various aspects of the agreement, such as fund transfers, deadlines, and dispute resolution.

Before deploying thoroughly test the Smart Contract code on a testnet to identify and fix any errors or vulnerabilities. Smart Contract bugs can have serious consequences, so testing is critical.

Once the Smart Contract is thoroughly tested and debugged, it can be deployed to the mainnet, where it becomes operational and immutable. Deployment typically incurs a cost, as it involves interacting with the blockchain's consensus mechanism.

Smart Contracts may require occasional maintenance, updates, or adjustments to adapt to changing circumstances or legal requirements. Smart Contract upgrades must be handled carefully to avoid disruption or disputes.

## **Dispute Resolution**

In some rare cases, you may need to involve legal authorities in form of Litigation to resolve disputes, particularly in cases where the law is relevant or where legal agreements govern the transaction.

Disputes can be escalated to legal authorities who apply relevant legal principles and make decisions based on applicable laws and contracts.

In cases involving complex legal issues, Litigation can provide expertise and enforceable decisions. This approach ensures that legal agreements are upheld.

Involving legal authorities may introduce higher costs and potentially lengthy legal processes. It may also reduce the decentralized and trustless aspects of crypto transactions.

{% content-ref url="../../dispute-resolution/litigation.md" %}
[litigation.md](../../dispute-resolution/litigation.md)
{% endcontent-ref %}
