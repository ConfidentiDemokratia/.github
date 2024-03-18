# DEMOKRATIA

The system allows users to train an AI agent on their device with their personal preferences. These preferences are then compressed using a Bert Large Language Model (LLM) into an embedding, which is sent to a semi-trusted server tasked with executing automated votes. For each new poll, the server calculates the user's vote using a straightforward ML model and produces a Zero-Knowledge Machine Learning (ZKML) attestation to verify the vote's correctness. This attestation encrypts the vote for publication on the blockchain. Users have the option to decrypt and review their vote; if dissatisfied with the automated choice, they can manually revote.

This project addresses the fundamental issue of low voter participation, which often stems from people's reluctance to make decisions. By creating a system that autonomously makes decisions on behalf of the user—in a manner consistent with their preferences—we aimed to increase participation by simplifying the voting process.

### Presentation of our project
- [presentation](https://github.com/ConfidentiDemokratia/.github/blob/main/dao_2_compressed.pdf)


![App](https://github.com/ConfidentiDemokratia/.github/blob/main/sim.gif)

## Solution
![Image alt](https://github.com/ConfidentiDemokratia/.github/blob/main/scheme.png)

## iOS Mobile client with Web3, Blockchain, and SwiftUI

- [ios-client](https://github.com/ConfidentiDemokratia/ios-client)

## Backend service facilitating autonomous voting through ZK ML

- [delegator-api](https://github.com/ConfidentiDemokratia/delegator-api)

## Minimal Anti-Collusion Infrastructure

- [maci](https://github.com/ConfidentiDemokratia/maci)

## MACI with Rust cryptography

- [maci-crypto-rust](https://github.com/ConfidentiDemokratia/maci-crypto-rust)


## Implementation EZKL and running it on the server

- [ZKML](https://github.com/ConfidentiDemokratia/ZKML)


## Delegator-Circom

- [delegator-circom](https://github.com/ConfidentiDemokratia/delegator-circom)

#### Contacts:
- artem.grigor.23@ucl.ac.uk
- nikita.krvchnk1@gmail.com


