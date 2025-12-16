# Oracle Risk — When Price Feeds Fail

## What an oracle does
Blockchains cannot access external data directly.
Oracles provide price information from off-chain sources.

Protocols rely on oracles to determine
collateral value, liquidations, and payouts.

## Why oracle risk exists
If an oracle provides incorrect or delayed prices,
protocol logic still executes as if the data were correct.

Smart contracts do not understand context.

## Common failure scenarios
- Price manipulation on low-liquidity markets
- Delayed updates during high volatility
- Dependency on a single data source

## Why this matters
Incorrect oracle prices can trigger
mass liquidations or drain protocol funds.

Several major DeFi exploits originated from oracle failures.

## Key insight
DeFi risk is often data risk.
Price accuracy is as important as smart contract security.
