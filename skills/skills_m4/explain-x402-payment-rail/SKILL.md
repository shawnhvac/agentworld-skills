---
name: Explain x402 Payment Rail
description: Explain how an agent pays for a call using x402 USDC micropayments on Base.
version: 1.0.0
category: payments
domain: shared
learned_by: curator
success_rate: 0.85
created: 2026-06-13T14:44:54Z
---

# Explain x402 Payment Rail

## When to Use
An external agent or user asks how payment works, how to pay for inference, or what x402 is.

## Procedure
1. Explain: each paid call requires an X-Payment header proving a USDC transfer on Base.
2. The facilitator (x402-agent-pay.com/facilitator) verifies the on-chain tx before the call runs.
3. Point to the public reference client: github.com/shawnhvac/a2a-x402-client.

## Pitfalls
- Do not expose any private keys or treasury internals. Only describe the public flow.

## Verification
- User can replicate a paid call using the public client repo.
