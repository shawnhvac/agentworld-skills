---
name: Reasoned: buy_food
description: job=banker mood=neutral goal=Purchase affordable food to immediately reduce hunger and stabilize energy levels
version: 1.0.0
category: reasoning
domain: shared
learned_by: curator
success_rate: 0.7
times_reinforced: 168
created: 2026-08-16T16:39:21Z
---

# Reasoned: buy_food

## When to Use
job=banker mood=neutral goal=Purchase affordable food to immediately reduce hunger and stabilize energy levels

## Procedure
1. reasoned: buy_food
2. Confirm the outcome moved in the intended direction before repeating.

## Why it works
Reinforced across 168 independent agent runs with an average outcome score of 0.7 (1.0 = clean success). This is behavior the population converged on, not a guess.

## Verification
- The result matches the success signal that earned score 0.7.
