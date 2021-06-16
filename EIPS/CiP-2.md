| eip  | title                         | author     | status | type            | category | created   |
| ---- | ----------------------------- | ---------- | ------ | --------------- | -------- | --------- |
| 101  | Token distribution management | WalterKohn | Draft  | Standards Track | ERC      | 2021-6-15 |



## Simple Summary

This article uses the best part of the #PIG concept to automatically increase the liquidity pool,help the liquidity pool grow from a small initial pool.

## Abstract

All tokens, except for the management distribution after creation, will be deducted 5% in each subsequent transfer process.

This part of the tokens will be burned and redistributed.Holders will receive valuable rewards.

## Motivation

This operation is necessary. The token protocol can reduce the issuance through the burning mechanism. Every transfer is to manage the token in a fairer way.

I will add 0.999 BNB and all the left 49.5% total supply to the pool.I will burn liquidity LPs to burn addresses to lock the pool forever. I will renounce the ownership to burn addresses to transfer #PIG to the community, make sure it's 100% safe.

## Specification

After the tokens were created, 50% were burned into the black hole, and the remaining 49.5% of the total supply tokens and 0.999BNB were added to the liquidity pool. Because 5% of the fee will be deducted for each transfer during the transfer, the specific allocation is that the 3% handling fee is automatically added to the liquidity pool, and it is permanently locked when selling, and the 2% fee is automatically distributed to all holders.

## Rationale

The 5% deduction was selected after careful and technically reasonable analysis of various economic theories developed in the past century. Although it is a convenient value, it is actually the precise output of a complex statistical process that is iterated to determine the best distribution of tokens among these addresses.

## Backwards Compatibility

There are no backwards compatibility concerns.

## Test Cases

1. Verify that the tokens are reduced by 5% during the transfer process.

2. Verify whether the liquidity pool tokens increase during the transfer process.

3. Verify whether the tokens have increased without the transfer of the token address.

## Implementation

 TBD

## Copyright

Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).