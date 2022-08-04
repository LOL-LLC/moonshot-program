# Moonshot #1: Optimistic EVM Bridge:
## Participants:
Multiple participants are allowed and encouraged. Competitive or collaborative participants receive equal rewards.

Iqlusion Inc. (3/2022)
Coin1111 (3/2022)

## Brief:
Chain interoperability is critical to the success of layer-1 blockchains in the coming decade. 
Bridges may be third-party infrastructure themselves (wormhole), on-chain protocols (Nomad), or be protocol level (IBC in cosmos). What is the minimal bridging service which 0L validators can provide, to the most chains?

## Plausible Solutions:
0L's strategy is to have bridges be part of the service offering of the Layer-1, meaning that the security of the chain is provided by the 0L validators.

There are multiple strategies in bridging: on-chain light clients, zkp rollups, or optimistic. Optimistic bridges are the lowest hanging fruit and demonstrated to work across multiple EVM chains.

## Evaluation and rewards:

- 200,000 - Plan - Develop a plan and roadmap.
- 200,000 - Prototype - Create the Move and EVM contracts and transactions
- 200,000 - Features Development - Create the tooling necessary for the transactions to be issued on both sides of the bridge.
- 400,000 - MVP - Include bridge registration and escrow deposits. 
- 100,000 - Ship - AUDITS! Merged to a mainline 0L branch.

## Milestones:

- Plan - Optimistic Bridge - Iqlusion Inc (completion 04/2021)

- Prototype - Optimistic Bridge  -  Awarded to Coin1111 - (completion 06/2022) https://github.com/coin1111/libra/tree/bridge
