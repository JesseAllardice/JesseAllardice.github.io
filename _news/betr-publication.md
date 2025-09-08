---
title: "BETR: Language Models Improve When Pretraining Data Matches Target Tasks"
date: 2025-07-16
type: "publication"
# image: "img/news/betr-publication.png"
image: "img/news/betr-scaling-laws.png"
links:
  - type: "paper"
    url: "https://arxiv.org/abs/2507.12466"
tags: ["BETR", "language models", "efficiency"]
---

Forget vague heuristics—match your pretraining data directly to your benchmarks! Our latest work, **BETR (Benchmark-Targeted Ranking)**, does exactly that and delivers **1.8–2.8× compute multipliers** over standard baselines. Instead of relying on indirect heuristics like "Wikipedia is good data," BETR directly aligns pretraining data with benchmarks by ranking documents based on similarity to benchmark training examples.

The results are striking: we need only ~45–55% of the compute to reach the same performance. Our scaling laws reveal that when you scale up model size and compute, milder filtering becomes optimal. But there's a catch—over-optimizing for standard benchmarks can create narrow, brittle models, reminding us that the benchmarks we choose fundamentally shape what our models can become.