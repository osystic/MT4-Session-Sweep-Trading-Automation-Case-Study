# MT4 Session-Sweep Trading Automation — Engineering Case Study

> **OSYSTIC ENGINEERING CASE STUDY · PUBLIC SHOWCASE · SANITIZED · PORTFOLIO-SAFE**

This case-study draft documents an MT4 Expert Advisor engineering engagement without publishing the confidential delivery source, client identity, account details or credentials.

## Problem & constraints

The delivery required converting a rules-based session-sweep trading concept into an MT4 Expert Advisor with explicit session windows, trend filtering, spread control, risk-based position sizing and automated trade management.

The implementation had to operate within broker-dependent MT4 constraints such as symbol digits, tick value, spread and broker-time sessions.

## Architecture & decisions

The private implementation uses the MT4 `OnTick` event loop and separates:

- session range tracking
- 50 / 100 / 200 EMA trend filtering
- sweep and confirmation logic
- spread gating
- pending order creation
- fixed-dollar risk sizing
- stop-loss / take-profit calculation
- breakeven and trailing-stop management
- chart visualisation

## Contribution & delivery

OSYSTIC retained the completed MQL4 source together with historical MetaTrader Strategy Tester evidence and documented operational assumptions.

## Evidence & outcomes

The retained repository proves that the strategy logic, risk-sizing path, order-management path and testing artifact exist. The Strategy Tester evidence is intentionally **not** presented as proof of profitability or future performance.

## Confidentiality

Client identity, private source code, account identifiers, broker credentials and private conversations remain excluded from this public artifact.

## Important limitation

Automated trading can result in financial loss. Historical backtests are environment-specific and do not guarantee future results.


## Public vs. private repository boundary

This repository contains **sanitized public proof only**. The confidential delivery/source repository remains private. Implementation source, client identity, credentials, private infrastructure, payment/contract details, private conversations, and protected raw evidence are intentionally excluded.
