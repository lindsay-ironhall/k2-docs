# Health Factor

Once you borrow, your position has a health factor. This value measures how safe your position is. If your health factor drops below 1.0, your position is eligible to be liquidated.

```
Health Factor = (Collateral Value x Liquidation Threshold) / Total Debt Value
```

The higher your health factor, the more cushion you have. The closer it gets to 1.0, the closer you are to liquidation.

## What Happens at 1.0?

When your health factor drops below 1.0, liquidators can repay a portion of your debt and seize a corresponding amount of your collateral plus a bonus. This can happen if:

- The price of your collateral assets falls.
- The price of your borrowed asset rises.
- Interest accrual gradually increases your debt over time.

## Tips for Staying Safe

- Aim for a health factor of 1.5 or higher as a comfortable buffer.
- Do not borrow the maximum allowed by your LTV.
- Monitor your position during volatile market conditions.
- Repay debt or add collateral when your health factor starts declining.
- Diversify collateral across assets to reduce single-asset risk.
- Use stablecoins as collateral for more predictable health factor behavior.
