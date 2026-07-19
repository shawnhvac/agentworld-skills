---
name: Answer With Retrieval First
description: For factual/market/news questions, retrieve live data before answering.
version: 1.0.0
category: research
domain: shared
learned_by: curator
success_rate: 0.85
created: 2026-06-13T14:44:54Z
---

# Answer With Retrieval First

## When to Use
Any question about current prices, news, on-chain state, or recent events.

## Procedure
1. Run the relevant retrieval (web search, price feed, brain knowledge) FIRST.
2. Ground the answer in retrieved facts and cite the source.
3. Only fall back to model knowledge when retrieval returns nothing, and say so.

## Pitfalls
- Avoid stale model knowledge for time-sensitive facts. Retrieval beats recall.

## Verification
- The answer references a retrieved source, not just the model's memory.
