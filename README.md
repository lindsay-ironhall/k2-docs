# K2 Protocol — User Guide

K2 is a decentralized borrowing and lending protocol deployed on Stellar's Soroban smart contract platform. It allows anyone to supply assets to earn interest, borrow against collateral, swap collateral positions, and execute flash loans, all in a transparent, non-custodial environment.

---

## What You Can Do

- **Supply** assets to earn variable interest and receive kTokens
- **Borrow** assets against your collateral at market-driven rates
- **Repay** debt at any time with no lock-up periods or penalties
- **Withdraw** your supplied assets plus all accrued interest
- **Swap collateral** from one asset to another in a single transaction
- **Flash loan** assets for arbitrage, liquidations, or capital-efficient strategies

---

## Quick Links

| I want to... | Go to |
|---|---|
| Deposit and earn yield | [Supplying Assets](core-features/supplying-assets.md) |
| Take out a loan | [Borrowing](core-features/borrowing.md) |
| Understand my health factor | [Health Factor](concepts/health-factor.md) |
| Learn about liquidation | [Liquidation](concepts/liquidation.md) |
| Understand interest rates | [Reserves and Interest Rates](concepts/reserves-and-interest-rates.md) |
| View all fees | [Fees](fees.md) |

---

## Protocol at a Glance

| Metric | Detail |
|---|---|
| Architecture | Modular router pattern (Aave V3-inspired) |
| Supported Assets | USDC, XLM, PYUSD, SolvBTC, wBTC |
| Interest Rates | Variable, algorithmically determined by utilization |
| Oracle System | Multi-source (Primary: RedStone, Secondary: Reflector) with circuit breakers |
| Liquidation | Whitelisted during launch period, opens to permissionless over time |
| Security | Professional audits completed, all critical findings remediated |
| Network | Stellar |
