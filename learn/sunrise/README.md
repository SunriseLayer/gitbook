# Sunrise

Sunrise is a L1 blockchain that serves Data Availability in the modular paradigm.

Sunrise DA layer has compatibility with the Celestia's architecture. Rollup-as-a-Service (RaaS) providers who integrated Celestia can integrate Sunrise easily, and Rollup SDKs (e.g. OP stack, Polygon CDK, Rollkit, Sovereign SDK, and so on) which support Celestia, can also support Sunrise easily.

Celestia-compatible features:

* Blob Tx
* BlobStream

In addition, Sunrise has unique features:

* Proof of Liquidity
* DA Fee Abstraction
* Sovereign Proof of Liquidity (SPoL)
* Incentive for optional long term data availability

Sunrise utilizes Proof of Liquidity mechanism to enhance the security of Sunrise L1, and the liquidity and sovereignty of L2s on Sunrise.
Sunrise also has a mechanism to incentivize DA network whereas other DA networks depends on altruism or voluntary contributions, hence Sunrise can enhance the throughput of the DA network. This feature and the incentive for optional long term data availability enables developers to build not only scalable L2s but also full-onchain new technologies like AI, game, and so on.

Furthermore, Sunrise is IBC (Inter Blockchain Communication) compatible.

The protocol will capture these values

* The revenue of tx fees
* The revenue of swap fees in the liquidity pool
* MEV captured with [Skip Protocol](https://docs.skip.money/blocksdk/overview/)

## Why should developers use Sunrise?

* Users can use DA without fee only with liquidity providing.
* Liquidity providing is needed in some DEXs in any case. Then there is no reason not to provide liquidity to Sunrise.

## Integration stages

### Sunrise v0: Minimum Viable Product

* `x/blob` module
* `x/blobstream` module
* Staking supports only `$SR`

### Sunrise v1: Complete user experiences

* `x/liquiditypool` module
* `x/blobgrant` module

### Sunrise v2: Security and Incentive

* `x/liquiditystaking` module
* `x/gauge` module
* `x/votingreward` module
* `x/spol` module

### Future possibility of the integration

* DasIncentive
* Long term data persistence