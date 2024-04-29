# Archive

Generally modular Data Availability layer serves data availability for a certain period like the challenge period of fraud proofs of Optimistic rollup or the latency of validity proofs of ZK Rollup, because Layer 2 doesn't require data availability after the finalization of the L2 state accomplished. It means that the data of Data Availability layer like Celestia, Avail and so on will be generally "pruned".

Sunrise hears the voices of the market like Blockchain Game developers that Layer 2 BCGs want the persistence of the data even after the L2 state gets finalized, to utilize the gaming history. So we will serve as a mechanism to preserve full archive data in the DA network.

`archive` module manage the long term data availability by periodically generate the DA attestations and the payment for the fee of long term DA attestation and data preservation.