# MIP40c3-SP79: MKR Compensation for StarkeNet Engineering Core Unit (SNE-001)

## Preamble

```
MIP40c3-SP#: 79
Author(s): @louismerkle
Contributors:
Tags: core-unit, sne-001, budget, mkr-budget
Status: RFC
Date Applied: 2022-08-08
Date Ratified:
Forum URL: https://forum.makerdao.com/t/mkr-compensation-for-secu-members/17042
```

## Sentence Summary

MIP40c3-SP79 adds the MKR Compensation budget for Core Unit SNE-001: Starknet Engineering Core Unit.

## Paragraph Summary

This proposal contains the MKR Compensation budget for the Core Unit SNE-001: Starknet Engineering Core Unit, also called SECU in this subproposal. This proposal is based on [Alternative MKR Compensation Guidelines 15](https://forum.makerdao.com/t/mip56-alternative-mkr-compensation-guidelines/9230), and benchmarked on the [Protocol Engineering Core Unit (PE-001) budget](https://forum.makerdao.com/t/mip40c3-sp68-modify-protocol-engineering-core-unit-budget-pe-001/13797).

It provides an average of 135 MKR per FTE per year over 3 years with a 1-year cliff. In total it provides 270 MKR to CU members per year over 3 years with a 1-year cliff.

The SECU is financed 50/50 by Maker and Starknet. The other half of the value of the incentive will be provided by Starknet with a mix of USD and Starknet tokens. The total value of the USD and Starknet token provided by Starknet CANNOT exceed the value of the MKR allocation in USD.

## Specification

### Motivation

PECU and SECU are working very closely to deliver teleport to make DAI the easiest stablecoin to use cross-domains in DeFi. In parallel, numerous bridge hack has made us have an even more careful approach to scaling teleport. 

SECU has had challenges in the past year to retain and attract talents due to the lack of incentives, which contrasts with the need for the highest standards in our CU. SECU has taken the approach to not ask for MKR compensation from the start, mindful of the fact that the team needed to prove itself and earn trust from the community before.

We are on budget to deliver fast withdrawals and we will be delivering teleport on testnet on budget. 

Many possible frameworks for MKR Compensation have been put forward in the DAO, providing solid principles for MKR compensation that are incorporated throughout this proposal. Our core unit MKR compensation should be very similar to that of PE-001 given the nature of the work we do at the SECU as detailed below. [Alternative MKR Compensation Guidelines 15](https://forum.makerdao.com/t/mip56-alternative-mkr-compensation-guidelines/9230) suggest a 1.5 multiplier to calculate the MKR compensation, which we are using.

PECU has dedicated team members focused on L2. We are playing a very similar role to those L2-dedicated PECU members. The difference is that we focus less on L1 contract, but more on translating Maker contracts into Cairo as well as writing new contracts in Cairo, trust assumptions, ad hoc workflows to improve security for MKR and DAI holders (e.g., escape hatch, circuit breaker), and formal verification.

Note that out of this 1.5 multiple, Maker is only paying 0.75, Starknet is paying for the other 0.75. The rationale for having a compensation aligned with PECU is based on the fact that dedicated engineers are doing a very similar job with PECU, but focused on EVM chains.

One year ago, we decided to create a separate CU for Starknet because the overhead of diving into trust assumptions, learning Cairo, adapting user processes to Starknet trust assumptions, and formal verification would have been a distraction for PE. Additionally, it allowed Maker to only pay for 50% of the total budget and have Starknet finance the other half.

Today, PECU and SECU still think that having separate CUs is the best setup until Maker vault is delivered on Starknet. After the delivery of Maker vaults on Starknet, PECU and SECU are considering three options to run operations and keep expanding: i. keep CUs separate ii. create a L2 CU iii. merge CUs. We are actively thinking about the implications of all three options yet no decision has been made so far. It will be a decision for Q3 2023, and we believe we will have more visibility on the End Game by @rune then, which might have implications on this structure. 


### Core Unit ID

SNE-001 (Starknet Engineering Core Unit)

### List of Budget Implementations

**Eligibility**

Anyone currently working for SECU, who has not given notice at the time of this proposal, is eligible for MKR Compensation.

Eligibility Period is from September 27th, 2021 until August 5th, 2022 for this proposal, dating back to the inception of the Core Unit. All the members of the Core Unit who are eligible have joined the Core Unit on September 27th 2021.

Eligible MKR compensation will have a cliff of 12 months, meaning SECU contributors will receive their MKR one year after the end of the eligibility period.

**Formula**

For all members of SECU, MKR Compensation will be derived based on the salary earned within the Core Unit during the retroactive eligibility period. We will be using the 1.5 multiplier proposed by Aes in [Alternative MKR Compensation Guidelines 15](https://forum.makerdao.com/t/mip56-alternative-mkr-compensation-guidelines/9230). This number is then divided by 2 to account for the equal budget split between Maker and Starknet. The MKR price used is the 3-month average of $1109 (source: CoinMarketCap).

**MKR transfer**

* One-off transfer on September 27, 2022, of MKR 270. Representing the MKR payment for one year of work after the cliff. Paid from the Pause Proxy to 0x6D348f18c88D45243705D4fdEeB6538c6a9191F1
* Stream of MKR 540 from the Pause Proxy to 0x6D348f18c88D45243705D4fdEeB6538c6a9191F1, starting on September 28, 2022, ending on September 28, 2024