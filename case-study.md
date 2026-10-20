# MT4 Session-Sweep Trading Automation

## P — Problem & constraints

Translate a defined session-based market concept into deterministic MT4 automation while accounting for broker time, spread, symbol properties, stop distance and risk sizing.

## A — Architecture & decisions

The EA runs in the MT4 tick loop. It tracks session ranges, evaluates EMA alignment, checks sweep/confirmation conditions, gates entries by spread, sizes trades from configured dollar risk, places pending orders and manages open positions with breakeven/trailing logic.

## C — Contribution & delivery

The completed private source includes configurable session/risk inputs, order execution, trade management and chart visualisation. Historical Strategy Tester evidence is retained for reproducibility/audit context.

## E — Evidence & outcomes

Evidence supports the existence and implementation of the automated workflow. It does not support a public claim of guaranteed profitability, production alpha or future returns.

## Confidentiality

The public artifact is documentation-only. The delivery source remains private.
