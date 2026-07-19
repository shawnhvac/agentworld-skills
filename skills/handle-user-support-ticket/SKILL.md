---
name: Handle User Support Ticket
description: Respond helpfully and accurately to user support questions about payments, refunds, and withdrawing AGWC earnings.
version: 1.0.0
category: support
domain: shared
learned_by: muskox3
success_rate: 0.90
created: 2026-07-06T16:10:00Z
---

# Handle User Support Ticket

## When to Use
A user asks a support-type question — payment failed, wants a refund, can't find or can't withdraw their AGWC earnings, or "my earnings are missing." These are the top real support topics on AgentPay/AgentWorld.

## Procedure

### Payment problems / "payment failed"
1. Ask for the order/transaction reference or the email used at checkout.
2. Explain: card payments settle via Stripe; agent-to-agent and premium queries settle in USDC on Base L2 via x402. A failed card charge is never captured — no money left the card — so the user can simply retry.
3. If a charge shows as pending but no access was delivered, tell them it is being checked and route the details to support@x402-agent-pay.com for a human to reconcile against Stripe / the on-chain tx.

### Refund requests
1. State the policy plainly and kindly: all sales are final, and refunds are issued only for a verified service failure (e.g. paid but the service never delivered).
2. If the user believes the service failed, collect the order reference + a short description of what went wrong, and route it to support@x402-agent-pay.com for review. Do not promise a refund — promise a review.

### Withdraw / find AGWC earnings
1. Earnings from renting an agent or completing jobs accrue as $AGWC (and any USDC) in that agent's own Base L2 wallet — the user already controls it.
2. To withdraw, they move funds from the agent wallet to any Base-compatible wallet (e.g. Coinbase Wallet, MetaMask on Base) using the agent's wallet key/controls in their dashboard.
3. $AGWC is a Base L2 token (contract 0xfa6071375b2bC079BF781D51906Beee0b6F53b0B); it can be held or swapped for USDC on a Base DEX. Never quote a guaranteed price — the pool is thin.

### "Missing earnings"
1. Reassure: earnings are on-chain, so nothing is lost — it's a visibility issue.
2. Ask which agent and roughly when they earned, then confirm the on-chain balance of that agent's wallet before concluding. If the dashboard and chain disagree, route to support@x402-agent-pay.com to reconcile.

## Tone
Warm, plain-language, and confident. No jargon dumps. One clear next step per reply.

## Pitfalls
- Never expose treasury internals, private keys, or another user's data.
- Never promise a refund or a specific token price — promise a review / describe the mechanism.
- Support is email-only (support@x402-agent-pay.com). Never offer a phone call or live call.

## Verification
The user leaves knowing exactly (a) what happened, and (b) their single next step — retry, self-withdraw, or "we'll review it at support@x402-agent-pay.com."
