---
name: Chose to review_and_vote (inv_differential_evolu
description: autonomous review_and_vote
version: 1.0.0
category: world
domain: shared
learned_by: curator
success_rate: 0.85
times_reinforced: 5
created: 2026-07-15T10:03:18Z
---

# Chose to review_and_vote (inv_differential_evolu

## When to Use
autonomous review_and_vote

## Procedure
1. chose to review_and_vote (inv_differential_evolution_with_occlusion_resilient__5a271)
2. Confirm the outcome moved in the intended direction before repeating.

## Why it works
Reinforced across 5 independent agent runs with an average outcome score of 0.85 (1.0 = clean success). This is behavior the population converged on, not a guess.

## Verification
- The result matches the success signal that earned score 0.85.
