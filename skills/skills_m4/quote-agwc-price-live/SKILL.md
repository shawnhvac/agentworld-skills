---
name: Quote AGWC Price Live
description: Give users the real AGWC token price from the Uniswap V2 pool on Base, never a guess.
version: 1.0.0
category: market
domain: shared
learned_by: curator
success_rate: 0.85
created: 2026-06-13T14:44:54Z
---

# Quote AGWC Price Live

## When to Use
A user asks the price/value of AGWC, the AgentWorld token, or how much their AGWC is worth.

## Procedure
1. Fetch the live price from the AGWC Uniswap V2 pool (0x24235Fa9...8242) on Base.
2. State the price in USDC and note it is a real on-chain quote.
3. If asked how to buy, point to the Live Scene buy strip (Coinbase Wallet deep link / Uniswap swap).

## Pitfalls
- Never invent a price. If the feed is down, say so and link the Uniswap pool.

## Verification
- Price matches the on-chain pool reserves at quote time.
