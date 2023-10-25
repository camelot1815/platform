---
description: How can users earn profit by investing in the Platform?
---

# ⏱ Staking

Staking is a mechanism where users can lock up or "stake" a certain amount of the [Platform's Native Tokens](../../native-token/tokenomics.md) to receive rewards in return.

### Annual Percentage Rate

Annual Percentage Rate (APR) is a common metric used in the context of staking cryptocurrencies. APR represents the annualized rate of return that a user can potentially earn by participating in Staking on the Platform.

APR is calculated as a percentage that reflects the annualized rate of return on the staked assets. It takes into account the rewards earned over the course of a year relative to the amount initially staked.

{% hint style="info" %}
It's important to note that APR can vary based on several factors, including the blockchain network's protocol and market conditions. APR can fluctuate over time, and users should be aware that the rate they receive may not remain constant.
{% endhint %}

### Staking Period to APR

The APR is significantly affected by the duration of assets lock-up. A longer Staking period results in a higher APR. The table below displays an approximate Annual Percentage Rate (APR) dependent on a Staking period.

<table><thead><tr><th width="380">Staking Period, days</th><th>Approx. APR, %</th></tr></thead><tbody><tr><td>under or equal to 30</td><td>3</td></tr><tr><td>more than 30 and under or equal to 90</td><td>6</td></tr><tr><td>more than 90 and under or equal to 180</td><td>9</td></tr><tr><td>more than 180 and under or equal to 360</td><td>12</td></tr><tr><td>more than 360 and under or equal to 540</td><td>16</td></tr><tr><td>more than 540</td><td>20</td></tr></tbody></table>

### Reputation to Coefficient

The level of rewards a user receives may be influenced by their [Reputation](../../crypto-escrow/reputation.md) on the Platform. Users who consistently perform well in [Voting](../../dispute-resolution/voting.md) or engage in successful Escrow may earn higher rewards.

{% hint style="info" %}
Reputation rankings are provided for each action separately, underscoring the importance of simultaneously maintaining both Voting and Escrow involvement.
{% endhint %}

Since Reputation is not constant and changes over time, the coefficient is consistently applied to the staked amount. Whenever there is a Reputation change, the coefficient may be recalculated for future periods.

{% code title="Staking Example" %}
```
Let's look at the Stake claim for 180 days 
with APR equal to 5% on 500$ worth of Platform's Native Token.

For the first 3 months, the user's Voting Reputation and 
Escrow Reputation were equal to 1000.
Earned for 3 months = 500$ * (5% / 12) * 3 * 1 * 1 = 6.25$

For the following month, the user increased his Reputation on
Arbirage to 2500, but the Escrow Reputation was left untouched.
Earned for 1 month = 500$ * (5% / 12) * 1 * 1.2 * 1 = 2.5$

After the next 2 months, the user decreased his Voting 
Reputation to 1500, but at the same time successfully finished
a lot of  Escrow transactions and increased Escrow Reputation 
to 4500.
Earned for 2 months = 500$ * (5% / 12) * 2 * 1.1 * 1.3 = 5.96$

Total earned for 6 months = 6.25$ + 2.5$ + 5.96$ = 14.71$
Total earned for 6 months plain = 500$ * (5% / 12) * 6 = 12.5$

So the user's profit from being involved in the Platform
activities brought him 2.21$ or ~18% of extra profit.
```
{% endcode %}

<table><thead><tr><th width="418">Escrow / Voting Reputation</th><th>Coefficient</th></tr></thead><tbody><tr><td>under or equal to 1,000</td><td>1.0</td></tr><tr><td>more than 1,000 and under or equal to 2,000</td><td>1.1</td></tr><tr><td>more than 2,000 and under or equal to 3,500</td><td>1.2</td></tr><tr><td>more than 3,500 and under or equal to 5,000</td><td>1.3</td></tr><tr><td>more than 5,000 and under or equal to 7,500</td><td>1.4</td></tr><tr><td>more than 7,500 and under or equal to 10,000</td><td>1.5</td></tr><tr><td>more than 10,000 and under or equal to 15,000</td><td>1.6</td></tr><tr><td>more than 15,000 and under or equal to 20,000</td><td>1.7</td></tr><tr><td>more than 20,000 and under or equal to 25,000</td><td>1.8</td></tr><tr><td>more than 25,000 and under or equal to 30,000</td><td>1.9</td></tr><tr><td>more than 30,000</td><td>2.0</td></tr></tbody></table>
