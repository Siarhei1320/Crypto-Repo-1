# Uniswap v2 — AMM Basics

## What it is
Uniswap v2 is an automated market maker (AMM) that allows users to trade
tokens directly against a liquidity pool instead of an order book.

## How pricing works
Prices are determined by the constant product formula:

x * y = k

where x and y are token reserves in the pool.

A trade changes the reserves, which automatically changes the price.

## Why this matters
There is no centralized market maker.
Liquidity providers collectively take the role of market making
and earn fees for providing liquidity.

## Key risk
Liquidity providers are exposed to impermanent loss when price moves
significantly compared to the entry price.

Impermanent loss is not a direct loss, but an opportunity cost
relative to holding the tokens.
