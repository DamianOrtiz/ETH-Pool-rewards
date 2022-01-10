# ETH-Pool-rewards
Eth Pool rewards challenge

> Simple contract to stake ETH to a pool and get rewards for staking, with the asumption that rewards are deposited only once per cycle.

# Algorithm

- Users are allocated a rewardDiscount when they stake ETH.
- The rewardDiscount is deducted from their holdings once they unstake.

# Deployment

A verified contract is deployed on ropsten at https://ropsten.etherscan.io/address/0x1a49e40ab949535120db98c95AeED68D9584c644

# Hardhat task to find the total staked ETH

Run `yarn totalStaked` to find the total staked eth in the contract.
