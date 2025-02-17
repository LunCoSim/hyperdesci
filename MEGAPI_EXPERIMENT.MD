# Experiment Three: Conviction Voting & Grants Eligibility

## Overview
This experiment proposes a framework to accelerate early-stage DeSci projects, which are often the most promising but also the riskiest.

### Core Principles
1. **Convertible Grants**: Projects receiving grants pledge to volunteerly replenish the treasury upon reaching maturity
2. **Decentralized Eligibility**: Through conviction voting
3. **Continuous Distribution**: Continuous grant distribution through Streaming QF

**Join the Discussion: [Telegram](https://t.me/hyperdesci_chat)**

## Token Economics: $MEGAPI

### Initial Distribution
Total Supply: 3,141,593 $MEGAPI (π × 10^6)

| Percentage | Amount | Usage |
|------------|--------|-------|
| 10% | 314,159 $MEGAPI | Liquidity Pool with ~0.15 ETH from current treasury |
| 10% | 314,159 $MEGAPI | StreamingQF distribution over 3 months |
| 3.5% | 110,000 $MEGAPI | Builder subsidies (subsidies half of the cost of the grant) |
| 5% | 157,078 $MEGAPI | Airdrop to DeSci supporters (later) |
| 12.5% | 392,798 $MEGAPI | Operations, marketing, and community development |
| 60% | 1,853,399 $MEGAPI | Treasury reserve for future distribution |

### Initial LP setup

1. Uniswap V3 LP with 3,141,593 $MEGAPI with 0.15 $ETH
2. Price Range: +- 2% - 30% of liquidity pool
                +- 5% - 30% of liquidity pool
                +- 10% - 40% of liquidity pool

### Community Participation

To nominate a project for grants via Gardens, a citizen must:

- Entry Requirement: 10k $MEGAPI stake + 1,000 $MEGAPI treasury contribution

- Target: 20 initial members
  - Expected Total Stake: 200,000 $MEGAPI
  - Treasury Contribution: 20,000 $MEGAPI

### Treasury Sustainability

Projects receiving grants commit to voluntarily replenishing the treasury through:
- Direct treasury donations
- Adding liquidity pairs
- Other community-approved methods

## Implementation Process

1. **Citizenship Acquisition**
   - Stake 10,000 $MEGAPI
   - Contribute 1,000 $MEGAPI to treasury

2. **Project Creation**
   - Citizens can propose new projects
   - Projects must reach %ELIGIBILITY_THRESHOLD for grant consideration

3. **Grant Distribution**
   - Activation requires %MIN_PROJECTS (e.g., 5) reaching %ELIGIBILITY_THRESHOLD
   - Distribution methods:
     - Primary: StreamingQF
     - Alternative: Gardens voting system with QF integration

4. **Treasury Allocation**
   - Dedicated portions for:
     - Project grants
     - Marketing initiatives
     - Community development
     - Operational expenses

## Background

This experiment builds upon:
- Gardens HyperDeSci funding
- [Gardens Popup Commons Experiment](https://app.gardens.fund/gardens/42161/0x912ce59144191c1204e64559fe8253a0e49e6548/0x0f143af46eef341b3f0dbf98c3ecb47f57067fef)
- [1Hive Gardens v2 Community](https://app.gardens.fund/gardens/100/0x71850b7e9ee3f13ab46d67167341e4bdc905eef9/0xe2396fe2169ca026962971d3b2e373ba925b6257)

### Related Documentation
- [On Continuous Grants Distribution](./On%20Continues%20Grants%20distribution.md)
- [Sustaining HyperDeSci](./Sustaining%20HyperDeSci.md)
- [Thoughts on Token Engineering for HyperDeSci](./Thought%20on%20Token%20Engineering%20for%20HyperDeSci.md)