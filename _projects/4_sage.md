---
layout: page
title: "SAGE: Benchmarking and Improving Retrieval for Deep Research Agents"
description: "Preprint &middot; Under review at ACL ARR 2026"
importance: 3
category: paper
---

**Preprint** &nbsp;|&nbsp; Under review at ACL ARR 2026 &nbsp;|&nbsp; Sep. 2025 – Feb. 2026

*Research assistant. With Prof. Chen Zhao.*

<a href="https://arxiv.org/abs/2602.05975" target="_blank" class="btn btn-sm z-depth-0" role="button">arXiv</a>

---

### Overview

Deep research agents have emerged as powerful systems for addressing complex queries, yet the role of retrieval remains underexplored. We introduce **SAGE**, a benchmark for scientific literature retrieval.

---

### Contributions

- Built **SAGE**, a benchmark for reasoning-intensive scientific literature retrieval with **1,200 queries across four domains** and a **200K-paper corpus**, supporting short-form and open-ended questions.
- Evaluated six deep research agents under both **web search and corpus retrieval settings**, revealing that BM25 outperforms LLM-based retrievers by **~30%** due to keyword-oriented sub-query generation.
- Proposed a **corpus-level test-time scaling framework** that augments documents with metadata and keywords using LLMs, improving retrieval accuracy by **+8% (short-form)** and **+2% (open-ended)**.
