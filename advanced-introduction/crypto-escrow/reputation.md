---
description: How can the users trust each other?
---

# ⚜ Reputation

Reputation is a measure of how trustworthy and reliable a user is perceived to be within the Platform's community. It reflects a user's track record of fulfilling their commitments and conducting fair and honest transactions.

Reputation helps users assess the trustworthiness of their transaction partners. A high Reputation score can instill confidence in potential trading partners. Positive actions, such as completing transactions as agreed and receiving positive feedback, contribute to a higher reputation score.

In case of disputes or disagreements, Reputation is a factor considered by the [Voting](../dispute-resolution/voting.md) or [Arbitration](../dispute-resolution/arbitration.md). Users with a history of fair dealings may be more likely to receive favourable outcomes.

{% hint style="warning" %}
Reputation can be publicly seen for users with [verified](../user-registration/kyc-verification.md) accounts only. The non-verified users can still earn Reputation, but it can not be viewed by anyone else.
{% endhint %}

## Implementation

Users begin with a neutral Reputation score equal to **1000 points** when they [register](../user-registration/) on the Platform. Over time, their Reputation score will be influenced by their actions, transactions, and interactions on the Platform.

Reputation points are cumulative, reflecting the overall history of a user's conduct on the Platform. The more positive actions a user accumulates, the higher their Reputation score. At the same time, Reputation is dynamic and can change over time based on user behaviour. Users are incentivized to maintain a positive reputation by consistently engaging in trustworthy actions.

Users with higher Reputation may enjoy benefits such as enhanced visibility within the Platform, [reduced transaction fees](../platform-fees.md#transaction-fees) and [faster dispute resolution](../dispute-resolution/).

### Escrow Reputation

The [Escrow Reputation](./) reflects the level of trustworthiness a user has when it comes to successfully concluding [Manual Escrow](../smart-contracts/manual/) transactions. Users have the opportunity to accumulate positive Escrow Reputation points in range of **0 to 100** through successful Escrow closures, whether or not a [dispute](../../resources/glossary.md#dispute) was initiated. Conversely, making false claims in disputes or being on the wrong side of a dispute can lead to a reduction in Reputation points in range of **-100 to 0**. The Escrow Reputation is represented as a decimal number within **a range of 0 to 35,000**.&#x20;

### Voting Reputation

The Voting Reputation indicates the user's reliability in reaching resolutions for disputes. Users can boost their Voting points by actively participating in [Dispute Resolution Voting](../dispute-resolution/voting.md), with the points in range of **0 to 100** being awarded after verification by the [Arbitration Team](../dispute-resolution/arbitration.md). The votes that have been identified as false will result in a deduction of points within the range of **-100 to 0**. The Voting Reputation is represented as a decimal number within **a range of 0 to 35,000**.&#x20;
