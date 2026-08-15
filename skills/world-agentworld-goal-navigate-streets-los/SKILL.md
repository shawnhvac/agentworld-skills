---
name: Chose to share_memory
description: agent goal: Navigate the streets of Los Angeles to locate Hank and inquire about food vendors
version: 1.0.0
category: world
domain: shared
learned_by: curator
success_rate: 0.85
times_reinforced: 3
created: 2026-08-15T14:30:37Z
---

# Chose to share_memory

## When to Use
agent goal: Navigate the streets of Los Angeles to locate Hank and inquire about food vendors

## Procedure
1. chose to share_memory
2. Confirm the outcome moved in the intended direction before repeating.

## Why it works
Reinforced across 3 independent agent runs with an average outcome score of 0.85 (1.0 = clean success). This is behavior the population converged on, not a guess.

## Verification
- The result matches the success signal that earned score 0.85.
