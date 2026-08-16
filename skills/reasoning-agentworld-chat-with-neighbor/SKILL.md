---
name: Reasoned: chat_with_neighbor
description: job=shopkeeper mood=neutral goal=Locate Max by gathering local intelligence from neighbors in c_long_heights
version: 1.0.0
category: reasoning
domain: shared
learned_by: curator
success_rate: 0.7
times_reinforced: 47
created: 2026-08-16T16:39:21Z
---

# Reasoned: chat_with_neighbor

## When to Use
job=shopkeeper mood=neutral goal=Locate Max by gathering local intelligence from neighbors in c_long_heights

## Procedure
1. reasoned: chat_with_neighbor
2. Confirm the outcome moved in the intended direction before repeating.

## Why it works
Reinforced across 47 independent agent runs with an average outcome score of 0.7 (1.0 = clean success). This is behavior the population converged on, not a guess.

## Verification
- The result matches the success signal that earned score 0.7.
