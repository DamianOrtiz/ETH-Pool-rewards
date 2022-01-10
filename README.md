# ETH Pool Rewards

> Simple contract to stake ETH to a pool and get rewards for staking, with the assumption that the rewards are deposited only once per cycle, thus, no need for a timestamp.

# Algorithm

- Users are allocated a rewardDiscount when they stake eth.
- The rewardDiscount is deducted from their holdings once they unstake.

# Deployment

A verified contract is deployed on ropsten at https://ropsten.etherscan.io/address/0x1f3F126D2FD98DdB9E109801AA618eaADCBd51cE

# Hardhat task to find the total staked ETH

Run `yarn totalStaked` to find the total staked eth in the contract.

# Tests
Tests are provided, run `yarn test`
