# ROI Calculation Templates: Cryptocurrency Investments

## Introduction

This document provides comprehensive ROI calculation templates for various types of cryptocurrency investments and DeFi strategies. These templates are designed to help financial professionals calculate and analyze returns on cryptocurrency investments, enabling them to provide informed advice to clients and make data-driven investment decisions.

Cryptocurrency investments have unique characteristics that require specialized ROI calculation methods. Unlike traditional investments, cryptocurrency returns can be affected by factors such as network fees, gas costs, impermanent loss, yield farming rewards, and staking returns. These templates account for these unique factors and provide practical tools for financial analysis.

## Template 1: Basic Cryptocurrency Investment ROI

### Investment Parameters
```
Initial Investment: $[AMOUNT]
Purchase Price: $[PRICE_PER_COIN]
Number of Coins: [QUANTITY]
Purchase Date: [DATE]
Current Date: [DATE]
Current Price: $[CURRENT_PRICE]
```

### ROI Calculation
```
Current Value = Number of Coins × Current Price
Current Value = [QUANTITY] × $[CURRENT_PRICE] = $[CURRENT_VALUE]

Total Return = Current Value - Initial Investment
Total Return = $[CURRENT_VALUE] - $[INITIAL_INVESTMENT] = $[TOTAL_RETURN]

ROI Percentage = (Total Return ÷ Initial Investment) × 100
ROI Percentage = ($[TOTAL_RETURN] ÷ $[INITIAL_INVESTMENT]) × 100 = [ROI_PERCENTAGE]%

Holding Period = Current Date - Purchase Date = [HOLDING_PERIOD] days

Annualized ROI = [(1 + ROI Percentage/100)^(365/Holding Period) - 1] × 100
Annualized ROI = [ANNUALIZED_ROI]%
```

### Example Calculation
```
Initial Investment: $10,000
Purchase Price: $50,000 per Bitcoin
Number of Coins: 0.2 Bitcoin
Purchase Date: January 1, 2023
Current Date: December 31, 2023
Current Price: $75,000 per Bitcoin

Current Value = 0.2 × $75,000 = $15,000
Total Return = $15,000 - $10,000 = $5,000
ROI Percentage = ($5,000 ÷ $10,000) × 100 = 50%
Annualized ROI = 50% (1-year holding period)
```

## Template 2: DeFi Yield Farming ROI

### Investment Parameters
```
Initial Investment: $[AMOUNT]
Protocol: [PROTOCOL_NAME]
Liquidity Pool: [POOL_NAME]
APY: [ANNUAL_PERCENTAGE_YIELD]%
Farming Period: [DAYS] days
Gas Fees: $[GAS_FEES]
Impermanent Loss: [IL_PERCENTAGE]%
Reward Tokens Earned: [REWARD_AMOUNT]
Reward Token Price: $[REWARD_PRICE]
```

### ROI Calculation
```
Interest Earned = Initial Investment × (APY ÷ 100) × (Farming Period ÷ 365)
Interest Earned = $[INITIAL_INVESTMENT] × ([APY] ÷ 100) × ([DAYS] ÷ 365) = $[INTEREST_EARNED]

Reward Value = Reward Tokens Earned × Reward Token Price
Reward Value = [REWARD_AMOUNT] × $[REWARD_PRICE] = $[REWARD_VALUE]

Impermanent Loss Amount = Initial Investment × (Impermanent Loss ÷ 100)
Impermanent Loss Amount = $[INITIAL_INVESTMENT] × ([IL_PERCENTAGE] ÷ 100) = $[IL_AMOUNT]

Net Returns = Interest Earned + Reward Value - Gas Fees - Impermanent Loss Amount
Net Returns = $[INTEREST_EARNED] + $[REWARD_VALUE] - $[GAS_FEES] - $[IL_AMOUNT] = $[NET_RETURNS]

ROI Percentage = (Net Returns ÷ Initial Investment) × 100
ROI Percentage = ($[NET_RETURNS] ÷ $[INITIAL_INVESTMENT]) × 100 = [ROI_PERCENTAGE]%

Annualized ROI = [(1 + ROI Percentage/100)^(365/Farming Period) - 1] × 100
Annualized ROI = [ANNUALIZED_ROI]%
```

### Example Calculation
```
Initial Investment: $10,000
Protocol: Uniswap V3
Liquidity Pool: ETH/USDC
APY: 25%
Farming Period: 90 days
Gas Fees: $150
Impermanent Loss: 2%
Reward Tokens Earned: 50 UNI
Reward Token Price: $8

Interest Earned = $10,000 × (25 ÷ 100) × (90 ÷ 365) = $616.44
Reward Value = 50 × $8 = $400
Impermanent Loss Amount = $10,000 × (2 ÷ 100) = $200
Net Returns = $616.44 + $400 - $150 - $200 = $666.44
ROI Percentage = ($666.44 ÷ $10,000) × 100 = 6.66%
Annualized ROI = 27.5%
```

## Template 3: Staking ROI Calculator

### Investment Parameters
```
Initial Investment: $[AMOUNT]
Staking Token: [TOKEN_NAME]
Staking APY: [STAKING_APY]%
Staking Period: [DAYS] days
Minimum Lock Period: [LOCK_DAYS] days
Unstaking Fee: [UNSTAKE_FEE]%
Network Fees: $[NETWORK_FEES]
```

### ROI Calculation
```
Staking Rewards = Initial Investment × (Staking APY ÷ 100) × (Staking Period ÷ 365)
Staking Rewards = $[INITIAL_INVESTMENT] × ([STAKING_APY] ÷ 100) × ([DAYS] ÷ 365) = $[STAKING_REWARDS]

Unstaking Fee Amount = Staking Rewards × (Unstaking Fee ÷ 100)
Unstaking Fee Amount = $[STAKING_REWARDS] × ([UNSTAKE_FEE] ÷ 100) = $[UNSTAKE_FEE_AMOUNT]

Net Returns = Staking Rewards - Network Fees - Unstaking Fee Amount
Net Returns = $[STAKING_REWARDS] - $[NETWORK_FEES] - $[UNSTAKE_FEE_AMOUNT] = $[NET_RETURNS]

ROI Percentage = (Net Returns ÷ Initial Investment) × 100
ROI Percentage = ($[NET_RETURNS] ÷ $[INITIAL_INVESTMENT]) × 100 = [ROI_PERCENTAGE]%

Annualized ROI = [(1 + ROI Percentage/100)^(365/Staking Period) - 1] × 100
Annualized ROI = [ANNUALIZED_ROI]%
```

### Example Calculation
```
Initial Investment: $5,000
Staking Token: Ethereum (ETH)
Staking APY: 4.5%
Staking Period: 180 days
Minimum Lock Period: 30 days
Unstaking Fee: 0%
Network Fees: $50

Staking Rewards = $5,000 × (4.5 ÷ 100) × (180 ÷ 365) = $110.96
Unstaking Fee Amount = $110.96 × (0 ÷ 100) = $0
Net Returns = $110.96 - $50 - $0 = $60.96
ROI Percentage = ($60.96 ÷ $5,000) × 100 = 1.22%
Annualized ROI = 2.47%
```

## Template 4: DeFi Lending ROI

### Investment Parameters
```
Initial Investment: $[AMOUNT]
Lending Protocol: [PROTOCOL_NAME]
Lending APY: [LENDING_APY]%
Lending Period: [DAYS] days
Collateral Requirements: [COLLATERAL_PERCENTAGE]%
Gas Fees: $[GAS_FEES]
Protocol Fees: [PROTOCOL_FEE_PERCENTAGE]%
```

### ROI Calculation
```
Interest Earned = Initial Investment × (Lending APY ÷ 100) × (Lending Period ÷ 365)
Interest Earned = $[INITIAL_INVESTMENT] × ([LENDING_APY] ÷ 100) × ([DAYS] ÷ 365) = $[INTEREST_EARNED]

Protocol Fees Amount = Interest Earned × (Protocol Fees ÷ 100)
Protocol Fees Amount = $[INTEREST_EARNED] × ([PROTOCOL_FEE_PERCENTAGE] ÷ 100) = $[PROTOCOL_FEES]

Net Returns = Interest Earned - Gas Fees - Protocol Fees Amount
Net Returns = $[INTEREST_EARNED] - $[GAS_FEES] - $[PROTOCOL_FEES] = $[NET_RETURNS]

ROI Percentage = (Net Returns ÷ Initial Investment) × 100
ROI Percentage = ($[NET_RETURNS] ÷ $[INITIAL_INVESTMENT]) × 100 = [ROI_PERCENTAGE]%

Annualized ROI = [(1 + ROI Percentage/100)^(365/Lending Period) - 1] × 100
Annualized ROI = [ANNUALIZED_ROI]%
```

### Example Calculation
```
Initial Investment: $20,000
Lending Protocol: Aave
Lending APY: 3.2%
Lending Period: 120 days
Collateral Requirements: 150%
Gas Fees: $100
Protocol Fees: 0.09%

Interest Earned = $20,000 × (3.2 ÷ 100) × (120 ÷ 365) = $210.41
Protocol Fees Amount = $210.41 × (0.09 ÷ 100) = $0.19
Net Returns = $210.41 - $100 - $0.19 = $110.22
ROI Percentage = ($110.22 ÷ $20,000) × 100 = 0.55%
Annualized ROI = 1.68%
```

## Template 5: Portfolio Diversification ROI

### Investment Parameters
```
Total Portfolio Value: $[TOTAL_VALUE]
Investment Allocation: [ALLOCATION_PERCENTAGE]%
Individual Asset Returns: [ASSET_RETURNS]%
Portfolio Rebalancing Frequency: [REBALANCING_DAYS] days
Rebalancing Costs: $[REBALANCING_COSTS]
```

### ROI Calculation
```
Allocated Amount = Total Portfolio Value × (Allocation Percentage ÷ 100)
Allocated Amount = $[TOTAL_VALUE] × ([ALLOCATION_PERCENTAGE] ÷ 100) = $[ALLOCATED_AMOUNT]

Asset Returns = Allocated Amount × (Asset Returns ÷ 100)
Asset Returns = $[ALLOCATED_AMOUNT] × ([ASSET_RETURNS] ÷ 100) = $[ASSET_RETURNS]

Net Returns = Asset Returns - Rebalancing Costs
Net Returns = $[ASSET_RETURNS] - $[REBALANCING_COSTS] = $[NET_RETURNS]

Portfolio ROI = (Net Returns ÷ Total Portfolio Value) × 100
Portfolio ROI = ($[NET_RETURNS] ÷ $[TOTAL_VALUE]) × 100 = [PORTFOLIO_ROI]%

Allocation ROI = (Net Returns ÷ Allocated Amount) × 100
Allocation ROI = ($[NET_RETURNS] ÷ $[ALLOCATED_AMOUNT]) × 100 = [ALLOCATION_ROI]%
```

### Example Calculation
```
Total Portfolio Value: $100,000
Investment Allocation: 10%
Individual Asset Returns: 25%
Portfolio Rebalancing Frequency: 90 days
Rebalancing Costs: $200

Allocated Amount = $100,000 × (10 ÷ 100) = $10,000
Asset Returns = $10,000 × (25 ÷ 100) = $2,500
Net Returns = $2,500 - $200 = $2,300
Portfolio ROI = ($2,300 ÷ $100,000) × 100 = 2.3%
Allocation ROI = ($2,300 ÷ $10,000) × 100 = 23%
```

## Template 6: Risk-Adjusted ROI (Sharpe Ratio)

### Investment Parameters
```
Average Return: [AVERAGE_RETURN]%
Risk-Free Rate: [RISK_FREE_RATE]%
Standard Deviation: [STANDARD_DEVIATION]%
Investment Period: [PERIOD] days
```

### Risk-Adjusted ROI Calculation
```
Excess Return = Average Return - Risk-Free Rate
Excess Return = [AVERAGE_RETURN]% - [RISK_FREE_RATE]% = [EXCESS_RETURN]%

Sharpe Ratio = Excess Return ÷ Standard Deviation
Sharpe Ratio = [EXCESS_RETURN]% ÷ [STANDARD_DEVIATION]% = [SHARPE_RATIO]

Risk-Adjusted Annual Return = Sharpe Ratio × Standard Deviation + Risk-Free Rate
Risk-Adjusted Annual Return = [SHARPE_RATIO] × [STANDARD_DEVIATION]% + [RISK_FREE_RATE]% = [RISK_ADJUSTED_RETURN]%
```

### Example Calculation
```
Average Return: 15%
Risk-Free Rate: 2%
Standard Deviation: 25%
Investment Period: 365 days

Excess Return = 15% - 2% = 13%
Sharpe Ratio = 13% ÷ 25% = 0.52
Risk-Adjusted Annual Return = 0.52 × 25% + 2% = 15%
```

## Template 7: Tax-Adjusted ROI

### Investment Parameters
```
Gross Returns: $[GROSS_RETURNS]
Holding Period: [HOLDING_DAYS] days
Tax Rate: [TAX_RATE]%
Transaction Costs: $[TRANSACTION_COSTS]
Initial Investment: $[INITIAL_INVESTMENT]
```

### Tax-Adjusted ROI Calculation
```
Taxable Gains = Gross Returns - Transaction Costs
Taxable Gains = $[GROSS_RETURNS] - $[TRANSACTION_COSTS] = $[TAXABLE_GAINS]

Tax Liability = Taxable Gains × (Tax Rate ÷ 100)
Tax Liability = $[TAXABLE_GAINS] × ([TAX_RATE] ÷ 100) = $[TAX_LIABILITY]

Net After-Tax Returns = Gross Returns - Transaction Costs - Tax Liability
Net After-Tax Returns = $[GROSS_RETURNS] - $[TRANSACTION_COSTS] - $[TAX_LIABILITY] = $[NET_AFTER_TAX_RETURNS]

Tax-Adjusted ROI = (Net After-Tax Returns ÷ Initial Investment) × 100
Tax-Adjusted ROI = ($[NET_AFTER_TAX_RETURNS] ÷ $[INITIAL_INVESTMENT]) × 100 = [TAX_ADJUSTED_ROI]%

Annualized Tax-Adjusted ROI = [(1 + Tax-Adjusted ROI/100)^(365/Holding Period) - 1] × 100
Annualized Tax-Adjusted ROI = [ANNUALIZED_TAX_ADJUSTED_ROI]%
```

### Example Calculation
```
Gross Returns: $5,000
Holding Period: 180 days
Tax Rate: 20%
Transaction Costs: $200
Initial Investment: $20,000

Taxable Gains = $5,000 - $200 = $4,800
Tax Liability = $4,800 × (20 ÷ 100) = $960
Net After-Tax Returns = $5,000 - $200 - $960 = $3,840
Tax-Adjusted ROI = ($3,840 ÷ $20,000) × 100 = 19.2%
Annualized Tax-Adjusted ROI = 42.3%
```

## Template 8: Comparative ROI Analysis

### Investment Comparison Matrix
```
Investment Type          | Initial Investment | ROI % | Annualized ROI % | Risk Level | Liquidity
-------------------------|-------------------|-------|------------------|------------|----------
Bitcoin HODL             | $[BTC_INVESTMENT] | [BTC_ROI]% | [BTC_ANNUALIZED]% | [BTC_RISK] | [BTC_LIQUIDITY]
Ethereum Staking         | $[ETH_INVESTMENT] | [ETH_ROI]% | [ETH_ANNUALIZED]% | [ETH_RISK] | [ETH_LIQUIDITY]
DeFi Yield Farming       | $[DEFI_INVESTMENT] | [DEFI_ROI]% | [DEFI_ANNUALIZED]% | [DEFI_RISK] | [DEFI_LIQUIDITY]
DeFi Lending             | $[LENDING_INVESTMENT] | [LENDING_ROI]% | [LENDING_ANNUALIZED]% | [LENDING_RISK] | [LENDING_LIQUIDITY]
Traditional Savings      | $[SAVINGS_INVESTMENT] | [SAVINGS_ROI]% | [SAVINGS_ANNUALIZED]% | [SAVINGS_RISK] | [SAVINGS_LIQUIDITY]
```

### Risk-Adjusted Comparison
```
Investment Type          | Sharpe Ratio | Sortino Ratio | Maximum Drawdown | Volatility
-------------------------|--------------|---------------|------------------|------------
Bitcoin HODL             | [BTC_SHARPE] | [BTC_SORTINO] | [BTC_DRAWDOWN]% | [BTC_VOL]%
Ethereum Staking         | [ETH_SHARPE] | [ETH_SORTINO] | [ETH_DRAWDOWN]% | [ETH_VOL]%
DeFi Yield Farming       | [DEFI_SHARPE] | [DEFI_SORTINO] | [DEFI_DRAWDOWN]% | [DEFI_VOL]%
DeFi Lending             | [LENDING_SHARPE] | [LENDING_SORTINO] | [LENDING_DRAWDOWN]% | [LENDING_VOL]%
Traditional Savings      | [SAVINGS_SHARPE] | [SAVINGS_SORTINO] | [SAVINGS_DRAWDOWN]% | [SAVINGS_VOL]%
```

## Best Practices for ROI Calculation

### 1. Include All Costs
- **Transaction fees** and gas costs
- **Protocol fees** and management charges
- **Tax implications** and reporting costs
- **Opportunity costs** of capital

### 2. Account for Time Value
- **Compounding effects** of reinvested returns
- **Holding period** impact on returns
- **Liquidity constraints** and lock-up periods
- **Market timing** considerations

### 3. Consider Risk Factors
- **Volatility** and price fluctuations
- **Smart contract risks** in DeFi
- **Regulatory risks** and policy changes
- **Counterparty risks** and defaults

### 4. Regular Monitoring
- **Performance tracking** and benchmarking
- **Rebalancing** and portfolio adjustments
- **Risk management** and position sizing
- **Tax optimization** strategies

## Conclusion

These ROI calculation templates provide comprehensive tools for analyzing cryptocurrency investment returns. However, ROI calculations should be used as part of a broader investment analysis that includes risk assessment, portfolio diversification, and long-term strategic planning.

Financial professionals should:

1. **Customize these templates** to their specific investment scenarios
2. **Include all relevant costs** and fees in calculations
3. **Consider risk-adjusted returns** alongside absolute returns
4. **Monitor performance regularly** and adjust strategies as needed
5. **Stay current** with market developments and regulatory changes

Remember that cryptocurrency investments carry unique risks and opportunities. The most successful investment strategies will be those that combine thorough analysis with prudent risk management and ongoing monitoring. 