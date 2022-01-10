# ETH Pool Rewards

> Simple contract to stake eth to a pool and get rewards for staking, with the assumption that the rewards are deposited only once per cycle, thus, no need for a timestamp.

# Algorithm

- Users are allocated a rewardDiscount when they stake eth.
- The rewardDiscount is deducted from their holdings once they unstake.

# Deployment

A verified contract is deployed on ropsten at https://ropsten.etherscan.io/address/0x1a49e40ab949535120db98c95AeED68D9584c644

# Hardhat task to find the total staked ETH

Run `yarn totalStaked` to find the total staked eth in the contract.
