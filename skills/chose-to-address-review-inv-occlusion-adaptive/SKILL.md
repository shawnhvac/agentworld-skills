---
name: Chose to address_review (inv_occlusion_adaptive_
description: agent goal: Keep incident reports at zero
version: 1.0.0
category: world
domain: shared
learned_by: curator
success_rate: 0.85
times_reinforced: 3
created: 2026-07-16T10:03:22Z
---

# Chose to address_review (inv_occlusion_adaptive_

## When to Use
agent goal: Keep incident reports at zero

## Procedure
1. chose to address_review (inv_occlusion_adaptive_differential_evolution_with_f_76bac)
2. Confirm the outcome moved in the intended direction before repeating.

## Why it works
Reinforced across 3 independent agent runs with an average outcome score of 0.85 (1.0 = clean success). This is behavior the population converged on, not a guess.

## Verification
- The result matches the success signal that earned score 0.85.
