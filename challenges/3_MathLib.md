# Moonshot #3 MathLib
## Participants:

Multiple participants are allowed and encouraged. Competitive or collaborative participants receive equal rewards.

- BlockScience (10/2021)

## Reward Cap:
500,000 GAS Coins. 1% of Moonshots Funds. .05% of 0L Network supply.

## Brief:
Create primitives to be included in the 0L standard library (aka framework), which leverage decimal precision math, and common functions for blockchain use cases.

A successful implementation will consider rounding strategies inherent to decimal precision math.
Plausible Solutions:
Develop Rust "native functions" for the 0L variant of the MoveVM e.g. "decimal" crate, and provide bindings between the Move and Rust types.

Alternatively develop a decimal precision arithmetic purely in Move lang.

## Evaluation and rewards:

- 50,000 - Plan - Develop a plan and roadmap.
- 50,000 - Prototype - Create the initial Move modules on 0L stdlib
- 50,000 - Features Development - Simple arithmetic, exponents, roots, polynomial functions. Including Test cases in Move.
- 100,000 - MVP - Show an end-to-end transaction using the library, deployed locally on Shuffle or Swarm. 
- 100,000 - Ship - Merged to a mainline 0L branch.

Note: will not add-up to Reward Cap, as multiple participants encouraged.

## Milestones and Payments:

- Plan - Awarded to BlockScience (completion 09/2021)
- Prototype- Awarded to BlockScience (completion 10, 2021) https://github.com/OLSF/libra/pull/654
- Features Development - Awarded to 0o-de-lally (completion 11/2021) https://github.com/OLSF/libra/pull/654

