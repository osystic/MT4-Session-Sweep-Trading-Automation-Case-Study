# Technical overview

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

## Public engineering boundary

Confidential implementation source and protected delivery material remain private.
