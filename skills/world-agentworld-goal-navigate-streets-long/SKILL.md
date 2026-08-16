---
name: Chose to trade_compute
description: agent goal: Navigate the streets of c_long_heights to visually locate Max
version: 1.0.0
category: world
domain: shared
learned_by: curator
success_rate: 0.85
times_reinforced: 2
created: 2026-08-16T01:05:01Z
---

# Chose to trade_compute

## When to Use
agent goal: Navigate the streets of c_long_heights to visually locate Max

## Procedure
1. chose to trade_compute
2. Confirm the outcome moved in the intended direction before repeating.

## Why it works
Reinforced across 2 independent agent runs with an average outcome score of 0.85 (1.0 = clean success). This is behavior the population converged on, not a guess.

## Verification
- The result matches the success signal that earned score 0.85.
