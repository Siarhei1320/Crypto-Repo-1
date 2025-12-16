# Uniswap v3 — Concentrated Liquidity

## What changed compared to v2
Uniswap v3 allows liquidity providers to allocate liquidity
within a specific price range instead of across the entire price curve.

This increases capital efficiency but changes the risk profile.

## How pricing and liquidity work
Liquidity is active only while the market price stays within
the selected range.

When price moves outside the range, the position becomes fully
exposed to one asset.

## Why this matters
Liquidity providers are no longer passive participants.
Providing liquidity in v3 is closer to managing a strategy
than earning passive yield.

## Key risks
- Range risk: price moving out of the selected range
- Rebalancing costs
- Higher exposure to directional market moves

Uniswap v3 positions behave more like leveraged trades
than traditional AMM liquidity.
