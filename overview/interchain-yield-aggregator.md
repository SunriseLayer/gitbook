# Interchain Yield Aggregator

{% hint style="info" %}
This feature is available on the testnet, but does not yet exist on the mainnet.
{% endhint %}

## What is the Yield Aggregator?

The Yield Aggregator on the UnUniFi protocol is the function for yield aggregation.

Users deposit their funds to the **Vault**, and then the funds earn yield automatically.

In addition, it supports **interchain** yield aggregation. So this is also called as Interchain Yield Aggregator (IYA).

## What is the Vault?

- One token many Vaults
  There can be multiple vaults for a single token. You can choose the Vault that best suits your preferences and manage your assets.

- Users can create Vaults
  Users can create Vaults without governance.
  However, it needs a fee and deposit. The fee is to prevent spam and the deposit is to provide an incentive to remove unnecessary vaults.

  The vault creator can configure the commission rate. It makes the vault creation competitive and creates an incentive for creation.

- One Vault has a combination of many strategies
  The Vault can be created by combining the strategies described below.
  You can create a Vault by selecting the strategies to be used and their weights.
  The strategy weights cannot be changed. If you want to change the weights, abolish the vault and let them go to another vault of the same token.

### What is the Strategy?

Strategies are methods of how the tokens will be managed to earn a yield. Users can add available strategies through governance with proposals.
Strategies can be developed using the **CosmWasm** smart contract.

For development of a strategy, visit [Strategy reference](../develop/strategy.md) page.