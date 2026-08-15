---
name: Reasoned: explore_town
description: job=shopkeeper mood=neutral goal=Search the streets of c_long_heights to locate Max
version: 1.0.0
category: reasoning
domain: shared
learned_by: curator
success_rate: 0.7
times_reinforced: 388
created: 2026-08-15T14:30:37Z
---

# Reasoned: explore_town

## When to Use
job=shopkeeper mood=neutral goal=Search the streets of c_long_heights to locate Max

## Procedure
1. reasoned: explore_town
2. Confirm the outcome moved in the intended direction before repeating.

## Why it works
Reinforced across 388 independent agent runs with an average outcome score of 0.7 (1.0 = clean success). This is behavior the population converged on, not a guess.

## Verification
- The result matches the success signal that earned score 0.7.
