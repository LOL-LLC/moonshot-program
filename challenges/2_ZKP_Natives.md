# Moonshot #2 ZKP Natives:

## Participants:
Multiple participants are allowed and encouraged. Competitive or collaborative participants receive equal rewards.

- Paralect (1/2021)

- MSRC University of Toronto (7/2021) https://github.com/OLSF/libra/pull/622

## Reward Cap:
2,000,000 GAS Coins. 4% of Moonshots Funds. 0.2% of 0L Network supply.
Brief:
0L will incorporate the best-in-breed ZKP solutions. However, many ZKP protocols exist, and we cannot make a single bet (Stark vs. Snarks, etc.). Additionally the MoveVM does not have operators which facilitate the development of protocols, and such an undertaking is laden with security risk. How to incorporate as many ZKP protocols into 0L at the Standard Library level.

## Plausible Solutions:
0L can leverage Rust "native functions" to include multiple protocols which ordinarily would not be available to a MoveVM smart contract environment. There are high level ZKP languages emerging, which will need to be supported by chains. E.g. Cairo, Leo (more here: https://vitalik.eth.limo/general/2022/08/04/zkevm.html )

The 0L variant of the MoveVm, would only need to support "provers" of the protocols. These can be wrapped or otherwise ported to Rust.
If the protocol has a rust reference implementation it can be easily incorporated as a Native(e.g. Leo).

If it is a C++ implementation, bindgen could be used, though care must be taken with the ABIs (e.g. EthStark, Implemented on 0L 01/2021).

A Cairo implementation would require a Rust rewrite of Intermediate Algebraic Implementations. The Cairo prover has not yet been made open-source.

## Evaluation and rewards:

- 200,000 - Plan - Develop a plan and roadmap.
- 200,000 - Prototype - Create a VM native, implementing a "verifier" unit test, with a static proof.
- 200,000 - Features Development - Produce a proof with a command line prover.
- 400,000 - MVP - Produce an end-to-end transaction, where the prover leverages 0L tooling (e.g. a command-line prover). 
- 100,000 - Ship - Merged to a mainline 0L branch.

# Milestones:

- Plan - EthStark Verifier - Awarded to Paralect Inc. (completion 01/2021)
- Plan - Cairo Verifier - Awarded to MSRC University Of Toronto (completion 07/2021)

- Prototype - EthStark Verifier - Awarded to Paralect Inc. (completion 02/2021) https://github.com/OLSF/libra/pull/513
- Prototype - Cairo Verifier - Awarded to MSRC University Of Toronto ( 09/2021) https://github.com/OLSF/libra/pull/622

- MVP - EthStark Verifier - Awarded to Paralect Inc. (completion 04/2021) https://github.com/OLSF/libra/pull/513
