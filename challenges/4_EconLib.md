# Moonshot #4 EconLib

## Participants:
Multiple participants are allowed and encouraged. Competitive or collaborative participants receive equal rewards.

[NONE]

## Reward Cap:
3,000,000 GAS Coins. 6% of Moonshots Funds. 0.3% of 0L Network supply.

## Brief
Create foundational econ primitives for the 0L Standard library at 0x0, to be used on 0L native GAS and third party tokens.
- ERC-20 standard token issuance
- Pay to contract
- conditional escrow
- generic staking, delegation, and yield
- vesting
- bonding curves
- constant product market makers

## Plausible Solutions:

- EconLib likely needs to leverage a MathLib with decimal precision calculus.
- However EVM has successfully created primitives without decimal precision, a pure MoveVM based solution may be acceptable.
- Many such primitives exist in EVM-land so many of these contracts may be straightforward ports without dependencies.
- The EconLib would be published in the 0L Move Stdlib 0x0 address.

## Evaluation and rewards:

- 100,000 - Plan - Develop a plan and roadmap.
- 200,000 - Prototype - ERC-20 Equivalent, conditional escrow, staking. 
- 200,000 - Features Development - Multisig wallet to control the above features.
- 400,000 - MVP - Includes bonding curves and AMM. 
- 100,000 - Ship - Merged to a mainline 0L branch.

## Milestones and Payments:
[NONE]
